### Supported tags and respective `Dockerfile` links

* `0.22`, `latest` ([Dockerfile](https://github.com/shadyoak/hugo/blob/master/Dockerfile))
* `0.21` ([Dockerfile](https://github.com/shadyoak/hugo/blob/v0.21/Dockerfile))

### Hugo Docker Image

This is a Docker image for the [Hugo](https://github.com/spf13/hugo) static site generator.

#### Usage

To run this image:

`docker run --rm -v $(pwd):/app shadyoak/hugo [COMMAND]`

For example:

```
docker run --rm -v $(pwd):/app shadyoak/hugo help
docker run --rm -v $(pwd):/app shadyoak/hugo version
docker run --rm -v $(pwd):/app shadyoak/hugo new site bookshelf
docker run --rm -v $(pwd):/app shadyoak/hugo new post/good-to-great.md
```

See the [hugo](https://gohugo.io) documentation for more details on available commands and usage.

#### Build

To build this image:

`docker build -t shadyoak/hugo .`

#### License

[MIT License](https://github.com/shadyoak/hugo/blob/master/LICENSE)
