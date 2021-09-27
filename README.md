# dev-containers

This repository contains dockerfiles to create images to be used as dev-containers with vscode.

## pyspark-dev
- latest Python 3 version
- spark-3.1.1-bin-hadoop3.2

## example: build an image
```
cd pyspark-dev
docker build -t dxa0/pyspark-dev .
```