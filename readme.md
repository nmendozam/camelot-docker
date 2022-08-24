This is the docker images for python's [camelot library](https://github.com/camelot-dev/camelot).

To build it:
```
docker build -t "camelot-docker" - < DockerFile
```

And to run test it:
```
docker run -it -v `pwd`:/app camelot-docker python test.py
```
