Python 3.6 Docker image
=======================

This image is based on Alpine Linux image, which is only a 5MB image, and contains
[Python 3.6](https://www.python.org/).

Download size of this image is only:

[![](https://images.microbadger.com/badges/image/etheleon/docker-alpine-python3.svg)](https://microbadger.com/images/etheleon/docker-alpine-python3 "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/version/etheleon/docker-alpine-python3.svg)](https://microbadger.com/images/etheleon/docker-alpine-python3 "Get your own version badge on microbadger.com")

Usage Example
-------------

This image is based on frolvlad/alpine-python3

```bash
$ docker run --rm etheleon/docker-alpine-python3 python3 -c 'print("Hello World")'
```

Once you have run this command you will get printed 'Hello World' from Python!

NOTE: `pip`/`pip3` is also available in this image.
