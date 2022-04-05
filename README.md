# Sample cli project for PDM

Because debugging pyproject.toml is not fun and python imports are a mess.

## Instructions
- `pdm build`: Build distributable - can be uploaded to pypi with `twine upload dist/*` once done
- `pdm install`: Install dependencies locally into `__pypackages__` folder
- `pip install .`: Install package through pip
