docker-curl
===========

curl in a container. This supports http2 as well.

## Current Version: [7.50.1](https://github.com/SolidNerd/docker-curl/blob/master/Dockerfile)


## Quickstart
With Docker Compose is a Quickstart very easy. Run the following command:

```
docker run --rm -it solidnerd/curl:7.50.1 -s --http2 -I https://nghttp2.org
```


## Inspiration

This image is inspired by the great article from [nathan le claire](https://nathanleclaire.com/blog/2016/08/11/curl-with-http2-support---a-minimal-alpine-based-docker-image/).
