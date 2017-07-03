# Scala, SBT, Docker Client Dockerfile

This repository contains **Dockerfile** of the following software components:

* [Scala](https://www.scala-lang.org/)
* [SBT](http://www.scala-sbt.org/)
* [Docker Client](https://docs.docker.com/engine/docker-overview/)


## Base Docker Image ##

* [openjdk:8](https://hub.docker.com/_/openjdk/)


## Installation ##

```
docker build --tag=joesan/scala-sbt-with-docker-client .
```


## Usage ##

```
docker run -it --rm --name rust joesan/scala-sbt-with-docker-client
```

## License ##

This code is open source software licensed under the [Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html").
