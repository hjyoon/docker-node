# Build
`docker build --tag docker-node:dev .`

# Server Start
`docker run --name docker-node-test -p 3000:3000 docker-node:dev`

# Check Web Page
[127.0.0.1:3000](http://127.0.0.1:3000/)