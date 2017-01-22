# hapi-backend
Hapi Backend Docker Container

# How to use:
`git clone https://github.com/bigbassroller/hapi-backend && cd hapi-backend`

`docker-compose build`

`docker-compose up -d`

## Build Image:
`docker build -t <username>/backend-container .`
## Run Image
`docker run -p 3000:3000 -d <username>/backend-container`
## Run Image with mounted volume
`docker run -p 3000:3000 -v  "$PWD"/:/usr/src/app --name hapi-backend -d <username>/hapi-backend`
