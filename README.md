# MinIO (CICD/GitHub Actions)

This repository contains the Dockerfile and the necessary files to build a MinIO container image. 
The image is built using the [official MinIO Docker image](https://hub.docker.com/r/minio/minio) as the base image.

The main purpose of this image is to be used in a CI/CD pipeline, specifically in a GitHub Actions workflow.
As GitHub Actions does not allow custom commands to be passed to the MinIO container (service).
Therefor a new image is needed that can be used in the workflow.
