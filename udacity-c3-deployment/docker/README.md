# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.



## Tasks

### Environment Variables:
You'll need to have the following environment variables setup:
$POSTGRESS_USERNAME
$POSTGRESS_PASSWORD 
$POSTGRESS_DB 
$POSTGRESS_HOST 
$AWS_REGION 
$AWS_PROFILE 
$AWS_BUCKET
$JWT_SECRET

### Setup Docker Environment
You'll need to install docker https://docs.docker.com/install/. Open a new terminal within the project directory and run:

1. Build the images: `docker-compose -f docker-compose-build.yaml build --parallel`
2. Push the images: `docker-compose -f docker-compose-build.yaml push`
3. Run the container: `docker-compose up`

