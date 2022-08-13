## Exercise 1.5: Sizes of images
1. Pull both images to local for checking them size
```console
$ docker pull devopsdockeruh/simple-web-service:ubuntu
$ docker pull devopsdockeruh/simple-web-service:alpine
```
2. Run container for both images in background
```console
$ docker run -d devopsdockeruh/simple-web-service:ubuntu sh
$ docker run -d devopsdockeruh/simple-web-service:alpine sh
```

3. Go to inside each container with two terminal
- Check container id or name of two container that is running
```console
$ docker ps -a
```
- In the first terminal
```console
$ docker exec -it <container_id> sh
$ tail -f ./text.log
```
- In the second terminal
```console
$ docker exec -it <container_id> sh
$ tail -f ./text.log
```
4. View result in both terminal and submit them
