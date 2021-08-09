# library images on steroids for hashicorp/bitwarden
## Wrapped images
- [docker-images](https://github.com/corpusops/docker-images) compatibles images (original images wrapped with tools)
- [![.github/workflows/cicd.yml](https://github.com/corpusops/docker-bitwarden/workflows/.github/workflows/cicd.yml/badge.svg?branch=main)](https://github.com/corpusops/docker-bitwarden/actions?query=workflow%3A.github%2Fworkflows%2Fcicd.yml+branch%3Amain)

| original   | wrapped  |
|------------|-----------|
| [bitwardenrs/server](https://hub.docker.com/_/bitwardenrs/server)                         | [corpusops/bitwardenrs-server](https://hub.docker.com/r/corpusops/bitwarden-server)                   |
| [bitwardenrs/server-postgresql](https://hub.docker.com/_/bitwardenrs/server-postgresql)   | [corpusops/bitwardenrs-server](https://hub.docker.com/r/corpusops/bitwarden-server) (postgresql tags) |
| [bitwardenrs/server-mysql](https://hub.docker.com/_/bitwardenrs/server-mysql)             | [corpusops/bitwardenrs-server](https://hub.docker.com/r/corpusops/bitwarden-server) (mysql tags)      |
| [bitwardenrs/web-vault](https://hub.docker.com/_/bitwardenrs/web-vault)                   | [corpusops/bitwardenrs-server](https://hub.docker.com/r/corpusops/bitwarden-server) (web-vault tags)  |
