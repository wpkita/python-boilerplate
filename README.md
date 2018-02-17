# python-boilerplate
A quick way to get started with a simple Python project (probably CLI-based)

## Steps
* `git clone https://github.com/pyenv/pyenv.git ~/.pyenv`
* Add the following to your .zshrc:
    ```
    export PATH=~/.pyenv/bin:$PATH
    eval "$(pyenv init -)"
    eval "$(direnv hook bash)"
    ```
* `pyenv update`
* `pyenv install **whatever-version-is-in.envrc**`
