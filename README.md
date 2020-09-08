This repository is a boilerplate / scaffold to build a Docker image using CircleCI.

You may use this however you'd like.

# Usage

1. Fork or duplicate this repository to your own repo.
2. Add the project to CircleCI.
3. In CircleCI, set up the `DOCKER_USER` and `DOCKER_PASS` environment variables with the Docker credentials that can push.
4. Modify the Makefile, specifically the `DESTINATION_DOCKER_IMAGE`, to point to your destination Docker image.
5. Modify the Dockerfile. Where possible, for building Docker images for use with Tugboat, use one of the [official Tugboat images](https://docs.tugboat.qa/reference/tugboat-images/) to start.
6. Commit and push these changes.
