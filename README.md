[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/colszowka-cucumber_table_formatter.svg)](https://hub.docker.com/r/rubygem/colszowka-cucumber_table_formatter/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/colszowka-cucumber_table_formatter.svg)](https://hub.docker.com/r/rubygem/colszowka-cucumber_table_formatter/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/colszowka-cucumber_table_formatter.svg)](https://hub.docker.com/r/rubygem/colszowka-cucumber_table_formatter/)
[![Gem Downloads](https://img.shields.io/gem/dt/colszowka-cucumber_table_formatter.svg)](https://rubygems.org/gems/colszowka-cucumber_table_formatter/)
# colszowka-cucumber_table_formatter

Auto-Generated Docker image for colszowka-cucumber_table_formatter to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/colszowka-cucumber_table_formatter`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/colszowka-cucumber_table_formatter`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/colszowka-cucumber_table_formatter`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/colszowka-cucumber_table_formatter/)
