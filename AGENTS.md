# AGENTS

This file captures repository-specific facts for automated agents.

## Repository facts (README)
- This repository contains the source of open-vsx.org, the public instance of Eclipse Open VSX.
- Most of the code is maintained in https://github.com/eclipse/openvsx.
- This repository contains adaptations specific to the public instance.
- The main artifact is the Docker image at ghcr.io/eclipsefdn/open-vsx-website.

## Development commands (README)
Enable Yarn, install dependencies, build assets, and start a dev server:
```bash
cd website
corepack enable
corepack prepare yarn@stable --activate
yarn --cwd website
yarn --cwd website compile
yarn --cwd website build
yarn --cwd website build:dev
yarn --cwd website start:dev
```

Recommended watch commands:
```bash
yarn --cwd website watch:tsc
yarn --cwd website watch:dev
```

## Tests
insufficient configuration data
