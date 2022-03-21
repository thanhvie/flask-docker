# flask-docker
````
docker run -d -p 5000:5000 huynhthviet/dockerhub:flaskapp-docker
````

# github actions
Github actions show an example workflow for building and pushing docker image to a docker image repository.
Everytime the code submitted in master/main branch, a process of building and pushing docker image will be trigger.
The docker image of every build will be assigned a different image tag.

## The image repository for this project is here

[huynhthviet/dockerhub:flaskapp-docker](https://github.com/marketplace/actions/build-and-push-docker-images)