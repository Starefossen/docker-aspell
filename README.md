# Docker Aspell

Docker image for running [Aspell](http://aspell.net) spell checking.

## Supported tags and respective `Dockerfile` links

* [`latest`, `0.60` (Dockerfile)](https://github.com/Starefossen/docker-aspell/blob/master/Dockerfile)

## What is Aspell

Aspell is a Free and Open Source spell checker. It can either be used as a
library or as an independent spell checker. Its main feature is that it does a
superior job of suggesting possible replacements for a misspelled word than just
about any other spell checker out there for the English language.

## How to use this image

This image makes it easy to spell check your files and documents by mounting
them as a voulme inside the container and run aspell on the files you like to
spell check like this:

```
$ docker run --rm -v some/dir:/some/dir starefossen/spell -c /some/dir/file.txt
```

## License

This Docker image is licensed under the [MIT License](https://github.com/Starefossen/docker-aspell/blob/master/LICENSE).

Software contained in this image is licensed under the following:

* GNU Aspell: [GNU LGPL License](http://aspell.net/man-html/GNU-Lesser-General-Public-License.html)

## Supported Docker versions

This image is officially supported on Docker version 1.6.1.

Support for older versions (down to 1.0) is provided on a best-effort basis.

## User Feedback

### Documentation

* [GNU Aspell](http://aspell.net)

### Issues

If you have any problems with or questions about this image, please contact us
through a [GitHub issue](https://github.com/Starefossen/docker-aspell/issues).

### Contributing

You are invited to contribute new features, fixes, or updates, large or small;
we are always thrilled to receive pull requests, and do our best to process them
as fast as we can.

Before you start to code, we recommend discussing your plans through a [GitHub
issue](https://github.com/Starefossen/docker-aspell/issues), especially
for more ambitious contributions. This gives other contributors a chance to
point you in the right direction, give you feedback on your design, and help
you find out if someone else is working on the same thing.
