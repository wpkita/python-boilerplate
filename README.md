## Python Boilerplate
NOTE: This project uses python-boilerplate: A quick way to get started with a simple Python project (probably CLI-based)

### Prequisites

* direnv
* pyenv

### Setup

* `cp .direnvrc ~`
* Add the following to your .zshrc:
    ```
    eval "$(direnv hook zsh)"
    ```
* `pyenv install **whatever-version-is-in.envrc**`
* `direnv allow`
