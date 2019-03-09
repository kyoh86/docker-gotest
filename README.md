# gotest

[![Docker Build Status](https://img.shields.io/docker/build/kyoh86/gotest.svg)](https://hub.docker.com/r/kyoh86/gotest/)

A docker image to test golang projects.

In the container, you can use following tools.

* [golangci-lint](https://github.com/golangci/golangci-lint)
* [reviewdog](https://github.com/haya14busa/reviewdog)
* [goverage](https://github.com/haya14busa/goverage)

```
golangci-lint run
```

```
goverage -coverprofile=coverage.out ./...
```

## Example

### Circle CI

(TODO)

### Wercker

(TODO)
