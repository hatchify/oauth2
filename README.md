# OAuth2 for Go

[![Build Status](https://travis-ci.org/golang/oauth2.svg?branch=master)](https://travis-ci.org/golang/oauth2)
[![GoDoc](https://godoc.org/github.com/hatchify/oauth2?status.svg)](https://godoc.org/github.com/hatchify/oauth2)

oauth2 package contains a client implementation for OAuth 2.0 spec.

## Installation

~~~~
go get github.com/hatchify/oauth2
~~~~

Or you can manually git clone the repository to
`$(go env GOPATH)/src/github.com/hatchify/oauth2`.

See godoc for further documentation and examples.

* [godoc.org/github.com/hatchify/oauth2](https://godoc.org/github.com/hatchify/oauth2)
* [godoc.org/github.com/hatchify/oauth2/google](https://godoc.org/github.com/hatchify/oauth2/google)

## Policy for new packages

We no longer accept new provider-specific packages in this repo if all
they do is add a single endpoint variable. If you just want to add a
single endpoint, add it to the
[godoc.org/github.com/hatchify/oauth2/endpoints](https://godoc.org/github.com/hatchify/oauth2/endpoints)
package.

## Report Issues / Send Patches

This repository uses Gerrit for code changes. To learn how to submit changes to
this repository, see https://golang.org/doc/contribute.html.

The main issue tracker for the oauth2 repository is located at
https://github.com/golang/oauth2/issues.
