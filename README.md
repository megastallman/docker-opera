# megastallman/docker-opera

[Opera beta](http://www.opera.com/computer/beta) (latest version) in a Docker container.


## Installation

download and compile the source yourself from Github:

```bash
$ git clone https://github.com/megastallman/docker-opera.git
$ cd docker-opera
$ docker build -t zeitgeist/docker-opera .
```

## Usage

```bash
$ docker run --rm -v /tmp/.X11-unix:/tmp/.X11-unix -v /var/run:/var/run -v /tmp:/tmp -e DISPLAY=unix$DISPLAY  megastallman/docker-opera
```

## Hint

This project can be used as a backbone to containerize any other proprietary shitware.
