# ShapeBit Website

This repository contains the ShapeBit OS landing page, Jekyll layout, and
GitHub Pages deployment.

Documentation content is maintained in the
[ShapeBit Docs Wiki](https://github.com/shapebit-software/website/wiki) and
published under [shapebit.software/docs/](https://shapebit.software/docs/).
Published page paths are normalized to lowercase, for example
`/docs/architecture/`. The site landing page is maintained in this repository.

## Local development

Install [mise](https://mise.jdx.dev/), then run:

```bash
mise install
mise run serve
```

This clones the Wiki into the ignored `wiki/` directory and serves the site at
`http://localhost:4000/`.
