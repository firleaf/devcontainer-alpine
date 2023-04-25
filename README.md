# devcontainer-alpine
Generic barebones Development Container setup for Docker, Docker compose and Alpine.

## Requirements
- Docker
- Docker Compose
- something to make use of Development Containers (e.g. VSCode Dev Containers extension)

## Usage
1. Create a repository using this template. ("Use this template" -> "Create a new repository")
2. Add any packages you need into `.devcontainer/extra-packages`.
3. Declare any additional services you need in `.devcontainer/compose.yaml`.
4. Done. Start your devcontainer and enjoy.
