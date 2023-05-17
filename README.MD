### Dockerfiles

Dockerfile is a declarative way of creating our own images. Docker will give us some syntax to create our own images.

File name should Dockerfile. docker command should run where your Dockerfile exists.

### How to build image from Dockerfile

```
docker build -t [docker-hub-URL]/[your-username]/[image-name]:version .
```

### How to push image to Dockerhub

```
docker push [docker-hub-URL]/[your-username]/[image-name]:version
```

### How to filter Docekr images by LABEL

docker images --filter "label=<key>=<value>"

Replace <key> with the label key you want to filter by and <value> with the corresponding value. Here's an example:

This command will list only the Docker images that have a label with the key version and value 1.0.
```
docker images --filter "label=version=1.0"
```