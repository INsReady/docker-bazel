# Supported tags and respective `Dockerfile` links

-	[`latest` (*Dockerfile*)](https://github.com/INsReady/docker-bazel/blob/master/dev/Dockerfile)

This image is updated via pull requests to [the `INsReady/docker-bazel` GitHub repo](https://github.com/INsReady/docker-bazel).


# What is Bazel?

Bazel is Google's build tool, now publicly available in Beta. Bazel has built-in support for building both client and server software, including client applications for both Android and iOS platforms. It also provides an extensible framework that you can use to develop your own build rules.

> [Bazel Documentation](https://bazel.build/docs/install.html)

# How to use this image

The basic pattern for starting a `bazel` instance is:

```console
$ docker run --rm -v "$PWD":/usr/src/app -d insready/bazel SOME-BAZEL-COMMAND
```

# License

View [license information](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) for the software contained in this image.

# Supported Docker versions

This image is officially supported on Docker version 1.13.0.

Please see [the Docker installation documentation](https://docs.docker.com/installation/) for details on how to upgrade your Docker daemon.

# User Feedback

## Documentation

Documentation for this image is stored in the [`README.md`](https://github.com/INsReady/docker-bazel/blob/master/README.md) of the [`insready/docker-bazel` GitHub repo](https://github.com/INsReady/docker-bazel). Be sure to familiarize yourself with the [repository's `README.md` file](https://github.com/docker-library/docs/blob/master/README.md) before attempting a pull request.

## Issues

If you have any problems with or questions about this image, please contact us through a [GitHub issue](https://github.com/INsReady/docker-bazel/issues).

You can also reach many of the official image maintainers via the `#docker-library` IRC channel on [Freenode](https://freenode.net).

## Contributing

You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull requests, and do our best to process them as fast as we can.

Before you start to code, we recommend discussing your plans through a [GitHub issue](https://github.com/INsReady/docker-bazel/issues), especially for more ambitious contributions. This gives other contributors a chance to point you in the right direction, give you feedback on your design, and help you find out if someone else is working on the same thing.
