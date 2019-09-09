# simple-container
this is a very simple container example

The Dockerfile is the source. This container image is also built and hosted by [DockerHub](https://hub.docker.com/r/richarda82/simple-container)

This command will pull and run a silly program ( :rainbow: :cat: ) on the container.

```
docker run --rm -it richarda82/simple-container nyancat
```

If you clone the source code, you can run

```
docker build --tag=simple-container .
```
to build it yourself.

Of course, this simply demonstrates a basic container workflow - a Dockerfile that can be shared, modified, and used as well as a container image that can be passed around and used as-is.