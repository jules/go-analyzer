# go-analyzer

A custom linter tool for enforcing CI checks on Golang repositories.

[![Go Report Card](https://goreportcard.com/badge/github.com/julesdesmit/go-analyzer?style=flat-square)](https://goreportcard.com/report/github.com/julesdesmit/go-analyzer)
[![PkgGoDev](https://pkg.go.dev/badge/github.com/julesdesmit/go-analyzer)](https://pkg.go.dev/github.com/julesdesmit/go-analyzer)
[![Actions Status](https://github.com/julesdesmit/go-analyzer/workflows/Continuous%20Integration/badge.svg)](https://github.com/julesdesmit/go-analyzer/actions)

## About

This tool should provide an easily extensible custom linter, which is easy to use.

## Usage

To use `go-analyzer` on any repo, make sure it is installed, and available in your `$PATH`:

```bash
$ go install github.com/julesdesmit/go-analyzer
```

From there, you can get a full list of commands by simply running:

```bash
$ go-analyzer
```

To run all available lints, run:

```bash
$ go-analyzer -a
```

## License

This code is licensed under the MIT license. Please see [LICENSE](LICENSE) for further info.
