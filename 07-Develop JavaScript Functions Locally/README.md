## Learning Objective

When you're developing Azure Functions in any language, it's common to come across version conflicts.
Version conflicts can occur at the runtime level, such as having more than one version of Node.js installed.
Conflicts can also occur when two or more different dependency versions are required by other dependencies.

Any time that you, as a software engineer, come across versioning conflicts, it's a good idea to keep containers in mind.
Using [Docker Desktop](https://www.docker.com/products/docker-desktop), you can easily spin up development containers that are isolated from other software installed on your dev system.
You can also attach the cross-platform Microsoft [Visual Studio Code](https://code.visualstudio.com) (VSCode) editor directly to a container, thanks to the [Remote Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension.

These tools together give you a native-like development environment, without having to worry about version conflicts as often.
Another benefit to using this toolchain is that you can easily test your software against many different runtime versions.