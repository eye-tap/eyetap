<div id="title" align="center">
    <img src="./assets/favicon-logo.jpg" width="300">
    <h1>Eye-TAP</h1>
</div>

A platform to connect gaze points to bounding boxes of texts.
Deployed version can be found [here](https://eyetap.ivia.ch/)

# Installation
The `docker-compose.yml` provided in the main folder in this repo is configured to pull in the latest docker containers provided by this project.

Run `docker compose up` in the root folder of this repository

## Monorepo
To run the backend for development, run `docker compose up` in the `/dev` folder
This repo uses submodules to pull in the frontend and backend.
So, when cloning, use
```git clone --recursive https://github.com/eye-tap/eyetap```

or, if you forget, you can clone the submodules using
```git submodule --recursive --remote --init```

and you can pull changes to them using either the provided `update-repo.sh` script or
```git submodule --remote --recursive```
