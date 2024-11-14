# micro-service-frontend
A practice project for app development using image recognition and natural language processing.
This repository is the frontend codebase. The backend codebase will be in another repository.

The branch policy of this repository is "GitHub Folow".
Please check [this article](https://qiita.com/onishi_820/items/d98c61e0faa67f417829) and [this document](docs/branch-policy.md) for details.

## DevContainer
This project recommends devcontainer environment. If the project contains .devcontianer/ directory, vscode can recognize it as devcontainer project automatically. VSCode would suggest any options. All folders in the project will be mounted into devcontaier.

The base image of this devcontianer is ubuntu. In addition, git CLI and node are installed.

Please follow instructions below to configure.

1. git clone and open cloned repository in vscode
2. press "Reopen in container", which can be shown automatically 
    - If you cannot see the window, you need to take following steps.
        1. Open a remote window (below left)
        2. choose the option "Reopen container"

Once you connected to devcontainer, you can observe "container runnning" by docker desktop or `docker ps` command.

## git CLI inside devcontainer
You will be required to setup git config inside container.
Please execute following commands.

  `git config --global user.email "you@example.com"`
  `git config --global user.name "Your Name"`