# Source repository for DigitalTibetan

[![publish-book](https://github.com/DigitalTibetan/DigitalTibetan/actions/workflows/Publish.yml/badge.svg)](https://github.com/DigitalTibetan/DigitalTibetan/actions/workflows/Publish.yml)
[![pages-build-deployment](https://github.com/DigitalTibetan/DigitalTibetan/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/DigitalTibetan/DigitalTibetan/actions/workflows/pages/pages-build-deployment)

This repository contains the source-files for Digital Tibetan. So to access the actual web-site, look here:

* [Digital Tibetan web site](https://digitaltibetan.github.io/DigitalTibetan/)

## How this works

This repository contains markdown files (for textual information) and jupyter notebooks (for computational examples) that are automatically converted at each push to the repository using github actions. The result are web pages, accessible at the [Digital Tibetan site](https://digitaltibetan.github.io/DigitalTibetan/).

To build the project manually:

```bash
jupyter-book build .
```

The result ends up in `_build/html` and can be opened with a web-browser. The github action publishes this into the branch `gh-pages` which is served by Github pages as `digitaltibetan.github.io/DigitalTibetan`.

### Installation:

```bash
# Clone repository of markdown files
git clone https://github.com/DigitalTibetan/DigitalTibetan
# Create a virtual env for Python
python -m venv DigitalTibetan
cd DigitalTibetan
# Activate environment
source bin/activate
# Install python dependencies
pip install -r requirements.txt
# Re-activate environment with newly install binaries
source bin/activate
```

then build the book with:

```bash
jupyter-book build .
```

### Build notes for macOS with brew:

If encountering build errors containing `ValueError: No template sub-directory with name 'script' found in the following paths:` then execute the following before building:

```bash
export JUPYTER_PATH=/opt/homebrew/share/jupyter:$JUPYTER_PATH
```

is currently required to make the jupyter-book build work until [this](https://github.com/jupyter/nbconvert/issues/1773) is fixed.