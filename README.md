# Releaser Docker Set-up

[![Codefresh build status]( https://g.codefresh.io/api/badges/pipeline/guangie88/guangie88%2Freleaser%2Freleaser?branch=master&key=eyJhbGciOiJIUzI1NiJ9.NWM4MjcyMzg3Y2NkOTUzZTcxM2RiMjRl.cTJ8XB8rM4mRl2LmZBHaIVZ92MxdGgb7Mmib1jt8o4E&type=cf-1)]( https://g.codefresh.io/pipelines/releaser/builds?repoOwner=guangie88&repoName=releaser&serviceName=guangie88%2Freleaser&filter=trigger:build~Build;branch:master;pipeline:5c853bc390bbd7d4e1ae2549~releaser)

Dockerfile set-up to contain tools for helping to release binaries.

The image is based on Alpine and the following packages are installed from
`apk`:

- ca-certificates
- curl
- zip

Additionally, some helpful external tools are installed:

- UPX
  - For compressing binary / libraries
- GHR
  - For helping to easily upload GitHub releases
