# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.140.1/containers/typescript-node/.devcontainer/base.Dockerfile

# [Choice] Node.js version: 14, 12, 10
ARG VARIANT="14-buster"
FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:${VARIANT}


RUN apt-get update -y
RUN apt-get install -y python3-pip python-dev build-essential

USER node

RUN echo 'source /workspaces/heights-gatsby/.bashrc' >> ~/.bashrc