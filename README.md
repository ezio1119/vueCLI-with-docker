# VueCLI-with-docker
## Usage
You can create vue project with docker.

First create an empty vue project folder.

```bash
git clone https://github.com/ezio1119/vueCLI-with-docker.git
```
```bash
cd vueCLI-with-docker
```
PROJECT_PATH is **absolute** path of your created vue project.

You can specify docker image tag of node.js with NODE_TAG.
```bash
make PROJECT_PATH=<your project path>
```