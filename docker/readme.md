Luxon provides a Docker container and some wrapping scripts to make it easier to run the tests.

  1. The Dockerfile is really just here as an FYI. You shouldn't need to interact with it
  1. `npm` is a bash script that runs `npm run [arg]` inside the Docker container.

If you do want to build the Docker image yourself, just do:

```
docker build -t luxon docker
```
