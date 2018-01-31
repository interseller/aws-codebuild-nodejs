# aws-codebuild-nodejs

This repository contains a Dockerfile which builds Docker images for AWS CodeBuild. The intention of this repository is to keep an image for CodeBuild that stays consistent and up-to-date with Elastic Beanstalk and with the current versions of Node.js.

You can use these Docker images by specifying a custom image in CodeBuild such as `interseller/aws-codebuild-nodejs:8.9.3`

The Dockerfile is a clone of [AWS CodeBuild Docker Images](https://github.com/aws/aws-codebuild-docker-images) but does not lock Ubuntu packages.

This repository automatically builds to [Docker Cloud](https://cloud.docker.com/swarm/interseller/repository/docker/interseller/aws-codebuild-nodejs/general).
