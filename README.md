# WILDS Contributor Guide

<https://getwilds.org/guide/>

Contributor guide for the WILDS GitHub organization at Fred Hutch Data Science Laboratory.

## Contributing to this guide

On the command line `make` commands are provided in the `Makefile` in this repo, with the following two commands:

- `make preview`
- `make render`

You can contribute via other editors/IDEs - see https://quarto.org/

## Publishing

The book is published on each push to main using the GitHub Actions workflow in `.github/workflows/publish.yml`. There's no need to do anything other than push (or merge/etc) to the `main` branch to update the public version of this book. Note that the book will only be updated by changes on `main` - so we're free to make changes on other branches without affecting the public version. We may want to change this flow in the future - e.g., require a pull request to `main` rather than push directly to make sure there's some review.
