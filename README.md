# KAI Copier Project Template for Python Projects of External Partners

Apache License 2.0: Copyright 2025 Infineon Technologies AG

- This is a [copier](https://copier.readthedocs.io/en/stable/) project template
- This template defines project metadata in [pyproject.toml](https://packaging.python.org/en/latest/guides/writing-pyproject-toml/)
- [pre-commit](https://pre-commit.com/) runs static code analysis to ensure clean formatting and type consistency

## Usage

CAUTION: Copier creates an answer file in the project dir (`.copier-answers.yml`), never change this file manually! Only with `copier update`.

First install `copier` via `pip install copier` / `pipx install copier` / `uv tool install copier`. For copier usage refer to [copier docs](https://copier.readthedocs.io/en/stable/) or `copier --help`.

### Init a New Project with this Template

- Provide a directory where you want to instantiate the template by creating one or cloning a git repo
- Switch CWD to this directory
  - `cd myNewProject`
- Run copier copy cmd
  - `$ copier copy -C -T https://github.com/Infineon/kai-external-python-project-template.git ./`
- Search for `TODO` in the project files and resolve them

### Update a Project to Newest Template Version

1. `cd project_dir`
1. `copier update --skip-answered`
