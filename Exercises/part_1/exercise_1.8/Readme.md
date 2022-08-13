## Exercise 1.8: Image for script
1. Create Dockerfile to build image
- step 1: create Docker file in local
```console
$ touch Dockerfile
```
- step 2: copy content from Dockerfile in this folder to Dockerfile that is created
2. Build image from Dockerfile
```console
$ docker build . -t curler
```
3. Run container from this image and enter argument that required
```consolde
$ docker run -it curler
```