# Python Rye Template

## Requirements

- [Rye >= 0.38](https://rye.astral.sh)

You may need to load rye in your .bash_profile or similar:

```sh
echo '. "$HOME/.rye/env"' >> ~/.bash_profile
```

## Installation

```sh
$ rye sync
$ ./install_hooks.sh
```

## Usage

Put local files and notebooks in local/

Run python files with `rye run python src/file.py`

Fix linting/formatting: `rye run fix`

Run tests: `rye test`
