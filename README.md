- docker build -t pritamworld/nodejs-image-demo-csad-1 .

- docker run -d -p 4000:3000 pritamworld/nodejs-image-demo-csad-1

* OR

- docker run --name nodejs-image-demo -p 4000:3000 -d pritamworld/nodejs-image-demo-csad-1

* References

- https://www.digitalocean.com/community/tutorials/how-to-build-a-node-js-application-with-docker