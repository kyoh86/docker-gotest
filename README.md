# gotest

A docker image to test golang projects.

In the container, you can use following tools.

* [gometalinter](https://github.com/alecthomas/gometalinter)
* [reviewdog](https://github.com/haya14busa/reviewdog)
* [goverage](https://github.com/haya14busa/goverage)

```
gometalinter --config /etc/gometalinter/config.json ./...  # It has the good feeling config.
```

```
cat lints.txt | reviewdog -f=golint -ci=circle-ci
```

```
goverage -coverprofile=coverage.out ./...
```

## Example

### Circle CI

(TODO)

### Wercker

(TODO)
