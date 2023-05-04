{% macro map(longitude, latitude, message, zoom='15') -%}

<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.3/dist/leaflet.css"
    integrity="sha256-kLaT2GOSpHechhsozzB+flnD+zUyjE2LlfWPgU04xyI="
    crossorigin=""/>

<!-- Make sure you put this AFTER Leaflet's CSS -->
<script src="https://unpkg.com/leaflet@1.9.3/dist/leaflet.js"
    integrity="sha256-WBkoXOwTeyKclOHuWtc+i2uENFpDZ9YPdf5Hf+D7ewM="
    crossorigin=""></script>

<div id="map" class="osm-inset"></div>
[Show a larger map](https://www.openstreetmap.org/?mlat=48.81453&mlon=9.16980#map=19/48.81453/9.16980)

<script>
	const map = L.map('map').setView([{{ longitude }}, {{ latitude }}], {{ zoom }});
	const tiles = L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
		maxZoom: 19,
		attribution: '&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
	}).addTo(map);
    var marker = L.marker([{{ longitude }}, {{ latitude }}]).addTo(map);
    marker.bindPopup("{{ message }}").openPopup();
</script>

{%- endmacro %}
