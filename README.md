# Using Keras via Docker

Based on https://github.com/tensorflow/tensorflow/tree/master/tensorflow/tools/docker

## Build

Nothing unusual here: `docker build -t TAG [-f Dockerfile.gpu]`

## Usage

Once built (you have to do this yourself for now), run the commands in `run-cpu` or `run-gpu` (with your modifications, if needed). Both are configured so that you can pass an absolute path to a directory for jupyter notebooks: `run-cpu PATH`