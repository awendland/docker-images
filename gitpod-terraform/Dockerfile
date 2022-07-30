# Find the new timestamped tags here: https://hub.docker.com/r/gitpod/workspace-full/tags
FROM gitpod/workspace-full:latest

# Install the terraform versions that I use across a variety of projects
RUN brew install tfenv \
    && tfenv install 0.11.15 \
    && tfenv install 0.12.31 \
    && tfenv install 0.15.5 \
    && tfenv install 1.2.6 \
    && tfenv use 1.2.6