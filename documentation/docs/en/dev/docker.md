# Docker
We are running the application within containers. Using Docker (or podman).
Information about using Docker is widly spread on the internet. We only have some basic information mentioned here.
Mainly to help the creating of images on the local machine. Mostly for testing purposes.

## Used commands

### WEB
cd <main-folder>/hero-web
docker build --rm -t phummelen/hero-web:latest -f deployment/web-dev.dockerfile .

docker run --rm -it -p 9000:9000 phummelen/hero-web:latest

### DOCS
cd <main-folder>/littertagger-documentation
docker build --rm -t phummelen/hero-docs:latest -f deploy/build/dockerfile .
