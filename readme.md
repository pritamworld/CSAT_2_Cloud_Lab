[![Docker Build and Publish to Docker Hub](https://github.com/pritamworld/CSAT_2_Cloud_Lab/actions/workflows/docker-build.yml/badge.svg)](https://github.com/pritamworld/CSAT_2_Cloud_Lab/actions/workflows/docker-build.yml)

Hello World

LCIT


docker build -t pritamworld/nodejs-image-demo-csat-2 .

docker run --name nodejs-image-demo -p 4000:3000 -d pritamworld/nodejs-image-demo-csat-2
