# Sample CLI project in Python using PDM

Because debugging pyproject.toml is not fun and python imports are a mess.

## Instructions
- `pdm build`: Build distributable - can be uploaded to pypi with `twine upload dist/*` once done
- `pdm install`: Install dependencies locally into the `__pypackages__` folder, to be used by your IDE or `python -m my_project`
- `pip install .`: Install package through pip

Once installed via pip, `run-my-project` should be a recognized command in your shell of choice. You can now use this template as the basis for your CLI python application.

## Links
- [PDM Package Manager](https://pdm.fming.dev/)
- [Awesome Pyproject.toml](https://github.com/carlosperate/awesome-pyproject)
