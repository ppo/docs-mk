# DocsMk

Template and CLI tool to manage a standalone [MkDocs](https://www.mkdocs.org/) documentation.


## Install

**Prerequisites:** Python 3, Git, Bash.

In your project folder, clone this project (or fork it first)…

```
git clone git@github.com:ppo/docsmk.git .
./docsmk/docsmk install
```

#### This will

- Create a Python3 virtualenv (`python3 -m venv ./docsmk/.venv`).
- Install the required pip packages (see `requirements.txt`).
- Create the documentation directory (`./docs`); unless it already exists.

#### Remark

If you plan to keep it versioned, don't forget to either:

1) Delete the .git directory of this project:

```
rm -fr ./docsmk/.git
```

2) Change it to your repository:

```
cd docsmk
git remote set-url origin git@example.com:<YOU>/<YOUR_REPO>.git
```


## Usage

```
Usage: docsmk [COMMAND=serve]

  serve      Run the local server to preview the documentation.
  build      Build the documentation.
  clean      Remove the build directory.
  install    Create a virtualenv and install pip packages.
  upgrade    Upgrade the pip packages.
  uninstall  Remove the virtualenv.
  help       Show this usage.
```


## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).  
See the [LICENSE](./LICENSE) file for details.
