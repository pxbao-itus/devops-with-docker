## Exercise 1.7: Two line Dockerfile
1. Create file denote web server 
- In this case, i used node http server to demo
- step 1: create file and write content for this file (you can refer file index.js in this folder or custom it to have result that printed in console look like tutorial)
```console
$ touch index.js
$ vi index.js
```
- step 2: create Dockerfile and write content for this file (you can refer file Dockerfile in this folder)
```console
$ touch Dockerfile
$ vi Dockerfile
```
- step 3: build a new image by Dockerfile that is created
```console
$ docker build . -t web-server
```
- step 4: run container from this image
```console
$ docker run web-server
```