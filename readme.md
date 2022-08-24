This is the docker image for python's [camelot library](https://github.com/camelot-dev/camelot).

To build it:
```
docker build -t "nmendozam/camelot" - < DockerFile
```

And to run test it:
```
docker run -it -v `pwd`:/app nmendozam/camelot python test.py
```
