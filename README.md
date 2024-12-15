# Conda build example
Simple repo to show an conda build process with a pyproject.toml

## How to use:
- Clone repo
- Build example: `conda build --output-folder build/ recipe/`
- Install package via `zip.bz2` on other systems/other envs:
`conda install conda-build-example-0.1.0-py_0.tar.bz2 `
- Use package `hello` (in bash)
