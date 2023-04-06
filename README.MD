### dockerfile####
Dockerfile is a declarative way of creating our own images. docker will give us some syntax to create our own images.

File name should be dockerfile .
###### How to build image from dockerfile 
...
docker build -t [docker-hub-URL]/[your-username]/[image-name]:version .
..

### How to push image to docker hub
....
docker push [your-username]/[image-name]:version
..