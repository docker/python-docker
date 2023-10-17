# Python Docker

A simple Python app for [Docker's Python Language Guide](https://docs.docker.com/language/python).

## My Annotations

How to run Flask Apps.

```shell
python -m flask run
```

How to create a Dockerfile for Python.

```shell
docker init
```

- What application platform does your project use? `Python`
- What version of Python do you want to use? `3.12.0`
- What port do you want your app to listen on? `5000`
- What is the command to run your app? `python -m flask run --host=0.0.0.0`

And them, there will be created: `.dockerfile`, `Dockerfile`, `compose.yaml`.

How to build an image.

```shell
docker build --tag python-docker .
```

How to view the images.

```shell
docker images
```

How to delete a image.

```shell
docker rmi <repository>:<tag>
```

## Links for More Information

- [Dockerfile reference](https://docs.docker.com/engine/reference/builder/)
- [docker init CLI reference](https://docs.docker.com/engine/reference/commandline/init/)
- [docker build CLI reference](https://docs.docker.com/engine/reference/commandline/build/)
