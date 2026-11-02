# ShapeBit Website

This repository contains the ShapeBit OS landing page, Jekyll layout, and
GitHub Pages deployment.

Documentation content is maintained in
[`docs/` of the OS repository](https://github.com/shapebit-software/os/tree/main/docs)
and published under [shapebit.software/docs/](https://shapebit.software/docs/).
Published page paths are normalized to lowercase, for example
`/docs/architecture/`. The site landing page is maintained in this repository.

## Local development

Install [mise](https://mise.jdx.dev/), then run:

```bash
mise install
mise run serve
```

This serves the site at `http://localhost:4000/`, with the documentation from a
checkout of the OS repository at `../os`. Set `OS_DOCS` to use another path.
