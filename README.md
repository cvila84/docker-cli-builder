# docker-cli-builder
[![Build status](https://ci.appveyor.com/api/projects/status/5mn0j7adf8xtoawn/branch/master?svg=true)](https://ci.appveyor.com/project/StefanScherer/docker-cli-builder/branch/master)

Build Docker CLI for Windows from upstream repo https://github.com/docker/cli and publish the `docker.exe` to GitHub releases https://github.com/StefanScherer/docker-cli-builder/releases.

## How to build ?

You need a Windows 10 pro or entreprise with version 1903, with windows container activated to perform this build
```docker build -t cvila84/docker-cli-builder .```

## How to get the built files ?

```docker create cvila84/docker-cli-builder
docker cp <id>:C:\<build_path> .```
