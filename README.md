# Gitignore

Generate `.gitignore` using this template.

## Install command line

```
$ git config --global alias.ignore '!gi() { if [[ ! -f .gitignore ]]; then touch .gitignore && curl -fsSL https://raw.githubusercontent.com/ixkaito/gitignore/master/.gitignore >> .gitignore; fi; }; gi'
```

## Use command line

```
$ git ignore
```
