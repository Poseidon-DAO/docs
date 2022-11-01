# Poseidon DAO Public docs

This docs is built using [mdbook](https://rust-lang.github.io/mdBook/) and based on the whitepaper.

## Development

To run local development install mdbook and then simply run the following command in order to dinamycally change the markdown files and see the output in your browser:

> mdbook watch --open

## Build

Building the docs as a static website is as easy as running:

> mdbook build

The output is saved in a `book` folder that can be served statically as a website from multiple providers.
