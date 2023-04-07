# charons-projects

Just a simple project to setup a basic html site using a docker container. Inside this repo you'll find the Dockerfile used to build the container image and the html files that are passed to it. You can test my image yourself by running the following:

docker run --rm --name charon-site -d -p 80:80 charonware/ct-docker-proj

To test, either use a browser to navigate to localhost:80 or use a terminal to curl localhost:80