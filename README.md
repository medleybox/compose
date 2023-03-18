# compose
Docker compose stack for medleybox in production. Includes scripts to manage instance

## Quick Setup
```bash
git clone https://github.com/medleybox/compose.git
cd compose
bin/start-stack
bin/first-setup
```

## CI Status

| Image  | ghcr.io  |  |
| :--- |  --- | ---: |
| medleybox/frontend| ![Build Status](https://github.com/medleybox/frontend/actions/workflows/.github/workflows/docker-publish.yml/badge.svg) | |
| medleybox/nginx| ![Build Status](https://github.com/medleybox/nginx/actions/workflows/.github/workflows/docker-publish.yml/badge.svg) | |
| medleybox/webapp| ![Build Status](https://github.com/medleybox/webapp/actions/workflows/.github/workflows/docker-publish.yml/badge.svg) | |
| medleybox/vault| ![Build Status](https://github.com/medleybox/vault/actions/workflows/.github/workflows/docker-publish.yml/badge.svg) | |
| medleybox/messenger| ![Build Status](https://github.com/medleybox/vault/actions/workflows/.github/workflows/docker-publish.yml/badge.svg) | |
| medleybox/websocket| ![Build Status](https://github.com/medleybox/vault/actions/workflows/.github/workflows/docker-publish.yml/badge.svg) | |