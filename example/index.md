# Welcome

For full documentation visit:

  - [MkDocs](https://www.mkdocs.org)
  - [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)

## Commands

- `docker-compose up build` - Build the EPFL scheme for Material.
- `docker-compose up serve` - Start the live-reloading docs server.

## Example

```yaml
theme:
  name: material
  palette:
    scheme: epfl
  logo: https://web2018.epfl.ch/5.2.0/icons/epfl-logo.svg
  favicon: https://web2018.epfl.ch/5.2.0/icons/favicon-32.png
  
extra_css:
  - css/epfl-scheme.min.css
```
