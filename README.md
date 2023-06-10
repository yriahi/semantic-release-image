# semantic-release-image

![Release Docker Image](https://github.com/yriahi/semantic-release-image/workflows/Release%20Docker%20Image/badge.svg)

`docker pull yriahi/semantic-release-image`

Docker image with semantic-release and plugins installed so you can just put
the `releaserc` (or your configuration of choice) file into your repo.

The following packages are installed globally:

- `semantic-release`
- `@semantic-release/gitlab`
- `@semantic-release/git`
- `@semantic-release/changelog`
- `@semantic-release/exec`

You find the exact versions of the packages in the package.json file.
