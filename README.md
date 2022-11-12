* Build Docker using Dockerfile
- docker build -t pritamworld/nodejs-image-demo-csad-1 .

- docker run -d -p 4000:3000 pritamworld/nodejs-image-demo-csad-1

* OR

- docker run --name nodejs-image-demo -p 4000:3000 -d pritamworld/nodejs-image-demo-csad-1

* Push Image to Docker Hub
- docker login
- docker push pritamworld/nodejs-image-demo-csad-1

* References

- https://www.digitalocean.com/community/tutorials/how-to-build-a-node-js-application-with-docker
- https://event-driven.io/en/how_to_buid_and_push_docker_image_with_github_actions/