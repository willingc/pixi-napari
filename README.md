# pixi-napari

This repo sets up a pixi environment that supports cpu and gpu execution options.

This production set up will enable the user to run the napari.

## Installation

Install the [pixi tool](https://pixi.sh/latest/installation/).

## Usage

### CPU default option

The following command will install python, napari and its dependencies, and launch napari:

```sh
pixi run napari
```

### GPU option

```sh
pixi run --environment gpu napari
```
