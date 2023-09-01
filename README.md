# Hugo Demo Site with GIT submodules

This is a documentation demo site based on [Hugo](https://gohugo.io/) and [Hextra Theme](https://github.com/imfing/hextra-starter-template). The content is loaded from external GIT repos through GIT submodules.

## Local deployment

Pre-requisites: [Hugo](https://gohugo.io/getting-started/installing/), [Go](https://golang.org/doc/install) and [Git](https://git-scm.com)

```shell
# Start the server
hugo mod tidy
hugo server --logLevel debug --disableFastRender -p 1313
```

### Update theme

```shell
hugo mod get -u
hugo mod tidy
```

## Deployment

### Docker

