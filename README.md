# s1mn.io

The [Hugo](https://gohugo.io) project for the website at https://s1mn.io.

## Getting started

```sh
brew install hugo
```

Then to get the theme:

```sh
git submodule init
git submodule update
```

## To run the site locally:

```
hugo server
```

## Publishing

Just push changes to `main`. [This Github Action](./.github/workflows/gh-pages.yml) builds the site and pushes it to the `gh-pages` branch, which is further configured [here](https://github.com/simonwhitaker/s1mn.io/settings/pages).
