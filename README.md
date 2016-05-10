# Docker Multiresolution Pannellum

### About
This Docker container can create multiresolution panoramas for [Pannellum](https://github.com/mpetroff/pannellum).

### Usage

```sh
$ docker run --rm -it -v <folder>:/opt quadeare/multiresolution_pannellum:latest <image>
```

You can modify output destination and image name. The image must be in the same folder you parametered.

This exemple creates a multiresolution of "alma.jpg" in the folder were you are.

```sh
$ docker run --rm -v $(pwd):/opt -it quadeare/multiresolution_pannellum:latest my_image.jpg
```

### Build
You can edit and build the project as desired.

```sh
$ docker build -t <your_name>/multiresolution_pannellum:latest .
```

### Requirement
* [Docker](https://www.docker.com/)

### Licence
```
This work is under the MIT License (MIT)
```
