# dev-containers

This repository contains dockerfiles to create images to be used as dev-containers with vscode.

## pyspark-dev
- latest Python 3 version
- spark-3.1.1-bin-hadoop3.2

## pyml-dev
- latest Python 3 version
- ...

## tex-dev
- latest Ubuntu
- tex ...

## example: build an image

> pyspark-dev
```
cd pyspark-dev
docker build -t dxa0/pyspark-dev .
```

> hugo-dev
```
cd hugo-dev
docker build -t dxa0/hugo-dev .
```