# MQ Demo
The purpose is to add a producer and a consumer for MQ using localhost.

The producer should set custom headers and the consumer should be able to read them.

## Development Environment: Devcontainers

This project supports [Devcontainers](https://containers.dev/) for a fully containerized Java 21 development setup.

### How to Use Devcontainers

1. **Install [VS Code](https://code.visualstudio.com/) and the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers).**
2. **Open the project folder in VS Code.**
3. **When prompted, "Reopen in Container" or use the command palette (`Ctrl+Shift+P`) and select `Dev Containers: Reopen in Container`.**
4. VS Code will build and start the container using Java 21 and Maven. All dependencies will be installed automatically.
5. You can now build, test, and run the project inside the containerized environment.

#### Useful Commands
- To build: `mvn clean install`
- To run tests: `mvn test`
- To start development: Open a terminal in VS Code and use Maven commands as usual.

**Note:** All source code and dependencies remain isolated in the container, ensuring a consistent environment for all contributors.