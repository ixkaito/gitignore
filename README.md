# Gitignore

Generate `.gitignore` using [this template](https://github.com/ixkaito/gitignore/blob/master/.gitignore).

## Install the command line

```
$ git config --global alias.ignore '!gi() { if [[ ! -f .gitignore ]]; then touch .gitignore && curl -fsSL https://raw.githubusercontent.com/ixkaito/gitignore/master/.gitignore >> .gitignore; fi; }; gi'
```

## Usage

```
$ git ignore
```
