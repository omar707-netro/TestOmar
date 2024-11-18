FROM mcr.microsoft.com/devcontainers/base:ubuntu

# Install C++ and OpenGL dependencies
RUN apt-get update && apt-get install -y \
    build-essential \
    cmake \
    libgl1-mesa-dev \
    libglu1-mesa-dev \
    freeglut3-dev

# Set up a non-root user (vscode is the default user in Codespaces)
USER vscode
