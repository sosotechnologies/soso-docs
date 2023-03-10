# Installation
> How to install MkDocs locally.


## Requirements

- [Python 3](https://www.python.org/)
- [Make](https://www.gnu.org/software/make/) - standard on macOS and Linux but can be installed on Windows too.


## Install system dependencies

install with docker

## Set up a new repo

Follow the Tutorial page to set up a project from scratch.

O

Then clone your repo.

## Install project dependencies
> Install MkDocs locally

For more info, see the [Installation](https://www.mkdocs.org/#installation) page on the MkDocs site.

### Install in a virtual environment

Create a virtual environment at the project root - this is used to isolate project packages from the global packages.

```sh
$ python3 -m venv venv
```

Activate the environment.

```sh
$ source venv/bin/activate
```

Install `mkdocs` - this is covered in the project requirements file.

```sh
$ cd docs
$ make install
```

Note - `mkdocs` 1.2 causes a break on force pushes, so this is excluded in the requirements. See issue [#2447](https://github.com/mkdocs/mkdocs/issues/2447).

### Install globally

If you prefer to install MkDocs once and reuse it across projects, then you can install it globally instead.

MkDocs is available using package managers like `apt-get`, `homebrew` and `yum`.

Or you can install like this:

```sh
$ python3 -m pip install mkdocs
```

If you get prompted for `sudo` use, then cancel and run again with `-U` flag for user-level install.
