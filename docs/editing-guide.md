## How to edit this site

### Documentation links
- [Setup](https://squidfunk.github.io/mkdocs-material/setup/changing-the-colors/)
- [Reference](https://squidfunk.github.io/mkdocs-material/reference/)

### Commands
- `mkdocs new [dir-name]` - Create a new project.
- `mkdocs serve` - Start the live-reloading docs server.
- `mkdocs build` - Build the documentation site.
- `mkdocs -h` - Print help message and exit.

### Project layout
    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files (including CNAME).

### Admonitions
``` title="Markdown"
!!! note "Custom Title"
    This is an example note. The custom title is optional!
```
Renders as:
!!! note "Custom Title"
    This is an example note. The custom title is optional!

#### Other supported types
General syntax is:
```
!!! [qualifier] "Whatever title"
    Whatever text goes here.
```

The full list of qualifiers is: `note`, `abstract`, `info`, `tip`, `success`, `question`, `warning`, `failure`, `danger`, `bug`, `example`, and `quote`.

Some of the most likely to use here:
!!! info "Info"
    Example text goes here.
!!! warning "Warning"
    Example text goes here.
!!! danger "Danger"
    Example text goes here.