# Automation-Hub
A repository for building reusable workflow for github actions and other automation configurations

## Notes on Usage

The docker build and push pipeline is for different container registry. set the required sredentials for each docker registry. for docker hub use registry name as *docker.io*;username as **DOCKERHUB_USERNAME** and password as **DOCKERHUB_TOKEN**.

for github container registry use registry name as *ghcr.io*; username as **REPOSITORY_OWNER** and password as **GHCR_PAT**.

for more information check [here](https://github.com/docker/login-action)
