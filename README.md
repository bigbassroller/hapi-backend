# hapi-backend
Hapi Backend Docker Container

# How to use:
## Build Image:
`docker build -t <username>/backend-container .`
## Run Image
`docker run -p 3000:3000 -d <username>/backend-container`
## Run Image with mounted volume
`docker run -p 3000:3000 -v  "$PWD"/:/usr/src/app --name backend -d <username>/backend-container`
