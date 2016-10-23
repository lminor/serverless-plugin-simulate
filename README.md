# Serverless docker
This is a proof of concept to see if we can replicate Amazon API Gateway using docker images to run lambda 

## Prerequisite
- docker - https://docs.docker.com/engine/installation/

## Getting started
- `npm install` - Installs all dependencies
- `npm start` - Starts server listing at http://localhost:4000
- `npm test` - tests custom authorizer (Authorization:TOKEN 12345)

## Acknowledgements
This would not be possible without [lambci](http://lambci.org/)
- [docker-lambda](https://github.com/lambci/docker-lambda) - Docker images and test runners that replicate the live AWS Lambda environment

[@johncmckim](https://github.com/johncmckim) for suggesting the idea
