# Source to Image (S2I)

Here you can find files needed to build a builder and a runtime image.

To build the builder image:

```
$ docker build -t almighty-builder -f Dockerfile.builder .
```

To build the runtime image:

```
$ docker build -t almighty-runtime -f Dockerfile.runtime .
```

