# docker-interlok-template

Just a simple template for building a docker image using MAVEN. It is intended for overlaying customisations over the latest `adaptris/interlok` (https://hub.docker.com/r/adaptris/interlok/) image. This uses the spotify docker plugin (https://github.com/spotify/docker-maven-plugin).

## Getting Started

* Modify pom.xml to include the optional components you require
* Add your custom config to src/config/ as required
* Modify src/Dockerfile as required.
* `mvn package docker:build` will eventually build you an image.