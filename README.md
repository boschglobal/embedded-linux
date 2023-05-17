# ELIOD website

This repository hosts the sources of the website for the Bosch Embedded IoT
Linux and OSS Day (ELIOD in short). The website is hosted using GitHub Pages
and can be reached at https://boschglobal.github.io/embedded-linux/

The website is written with markdown files and utilizes
[MkDocs](https://www.mkdocs.org/) for rendering in combination with a customized
version of the [Material fo MkDocs
theme](https://squidfunk.github.io/mkdocs-material/).

## Modifications

All of the pages are generated from markdown files. Making changes to these
markdowns should be easy, as long as you stick to the proper [markdown
syntax](https://www.markdownguide.org/basic-syntax/).

Some page content is generated using [jinja2
templates](https://jinja.palletsprojects.com), that process data from
[YAML](https://yaml.org/) files. This especially holds for the
[keynotes](https://boschglobal.github.io/embedded-linux/keynotes/) and
[talks](https://boschglobal.github.io/embedded-linux/talks/) pages. Here a few
additional things should be taken into account.

Modifications to exisiting keynotes or talks are to be made in the file
[keynotes.yaml](docs/data/keynotes.yaml) or [talks.yaml](docs/data/talks.yaml)
respectively.

When adding an *additional* talk or keynote entry, extra steps are required:
- Add an additional entry to [keynotes.yaml](docs/data/keynotes.yaml) or
  [talks.yaml](docs/data/talks.yaml) for a new keynote or talk respectively.
- The new entry should have an unique identifiable name tag, referenced here as
  `<presentation_tag>`. This tag is to be replaced in the following instructions
  with the name tag you created.
- Stick to the same YAML structure as the other entries.
- Add a markdown file named `<presentation_tag>.md` for each keynote or talk to
  the [keynotes](docs/keynotes/) or [talks](docs/talks/) directory respectively.
  This file should have the following content (don't forget to replace
  `<presentation_tag>` with your unique name tag):
  ```yaml
  ---
  hide:
  - toc
  presentation: <presentation_tag>
  ---
  
  {% import 'presentation.md' as presentation %}
  
  {{ presentation.overview(metadata=keynotes[page.meta.presentation]) }}
  ``` 
- Add a link entry to the nav section in the [global mkdocs settings
  file](mkdocs.yml), with the following syntax 
  ```yaml
  - <presentation_name>: keynotes/<presentation_name>.md
  ```
  or 
  ```yaml
  - <presentation_name>: talks/<presentation_name>.md
  ```
  for keynotes and talks respectively.  
  Here, `<presentation_name>` should be replaced with the keynote/talk
  designation that should appear in the left hand side section menu on the
  speakers page. Also make sure, that the link entry is placed at the correct
  position in the nav section: Stick to the same order as in
  [keynotes.yaml](docs/data/keynotes.yaml) or
  [talks.yaml](docs/data/talks.yaml).