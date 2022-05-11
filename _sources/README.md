# Source repository for DigitalTibetan

[![publish-book](https://github.com/DigitalTibetan/DigitalTibetan/actions/workflows/Publish.yml/badge.svg)](https://github.com/DigitalTibetan/DigitalTibetan/actions/workflows/Publish.yml)

This repository contains the source-files for Digital Tibetan. So to access the actual web-site, look here:

* [Digital Tibetan web site](https://digitaltibetan.github.io/DigitalTibetan/)

## How this works

This repository contains markdown files (for textual information) and jupyter notebooks (for computational examples) that are automatically converted at each push to the repository using github actions. The result are web pages, accessible at the [Digital Tibetan site](https://digitaltibetan.github.io/DigitalTibetan/).

To build the project manually:

```bash
jupyter-book build .
```

The result ends up in `_build/html` and can be opened with a web-browser. The github action publishes this into the branch `gh-pages` which is served by Github pages as `digitaltibetan.github.io/DigitalTibetan`.