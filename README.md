# flask-test

A simple Flask+Docker app which you can use to check your install is working.

## Clone files

git clone https://github.com/exactful/flask-test.git

cd flask-test

## Build image

docker image build -t flask-test .

## Create container using image

docker run -d -p 80:5000 flask-test

Runs container in detached mode (-d) and binds (-p) the host's port 80 to the container's port 5000

## Access page on default port 80

http://localhost

## View running containers

docker ps

## Stop container

docker stop {container id}
