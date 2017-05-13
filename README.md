See https://nodejs.org/en/docs/guides/nodejs-docker-webapp/ for more details

# Build the image
`docker build -t <your username>/node-web-app .`

See available images:

`docker images`

# Run the image

`docker run -p 49160:8080 -d <your username>/node-web-app`

`docker ps`

Test it:

`curl -i localhost:49160`