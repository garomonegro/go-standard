# go-standard

[![Build Status](https://travis-ci.org/codecov/go-Standard.svg?branch=master)](https://travis-ci.org/codecov/go-Standard) [![codecov](https://codecov.io/gh/codecov/go-Standard/branch/master/graph/badge.svg)](https://codecov.io/gh/codecov/go-Standard)

### Last Updated: 04/19/20 18:43:51

## What is this?

This is a **Go** application, with basic unit tests, for which coverage is uploaded to Codecov on a daily basis. It can also serve as an example for how to integrate Codecov into your Go project. If the build is passing for this project, then Codecov's Go report processing is functional and correct on codecov.io.

## Configuration

This project is written in `Go`. Unit test are written using the go `testing` framework and coverage reports are generated using the `go` CLI.

## Usage

### The Docker Way

Run unit tests inside a Docker container
```bash
docker-compose up
```

### The Local Way

Run tests
```
go test -race -coverprofile=coverage.txt -covermode=atomic
```

## Reporting Issues

If you've discovered an issue with this repository or with Go processing in general, it is recommended to email support@codecov.io rather than post an issue here. This repository will not be checked regularly for open issues.

## Contributing

Contributions are welcome! If you'd like to contribute to this repository, feel free to open a pull request or flag an issue. If you would like to contribute a new lanaguage standard, [you can get more information here](https://github.com/codecov/standards-scripts/blob/master/README.md#contributing). 
