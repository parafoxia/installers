# Installers

This is a repository for various install scripts.
These scripts will only work on Debian-based systems.

***

## LaTeX

This script installs latest version of TeX Live and all packages.
If you have a `.profile` file, place it in this directory before installing.

### Usage

```bash
sudo bash install-latex
```

***

## Poetry

This script installs the latest version of Poetry for Python.

### Usage

```bash
bash install-poetry [python-version]
```

Here, `python-version` is the version of Python you wish to use when installing.
By default, "3" is used (calling `python3`).

***

## Python

This script downloads, builds, and installs Python from source.
It can install multiple Python versions at once.

### Usage

```bash
bash install-python <version1> [version2 ...]
```

***

## Redis

This script downloads, builds, and installs the latest version of Redis from source.

### Usage

```bash
bash install-redis [-t]
```

The `-t` flag denotes whether `make test` is run or not. By default, it is not run.

***

## License

These scripts have been put into the public domain by [The Unlicense](https://github.com/parafoxia/installers/blob/main/LICENSE).
Use them at your own risk.
