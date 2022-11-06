# go-command-line-interface
Go module to demonstrate backing CLI program with a programmatic API

## Setting Up Cobra
1. ``$ go install github.com/spf13/cobra-cli@latest``
1. ``$ ~/go/bin/cobra-cli init``
1. ``$ ~/go/bin/cobra-cli add create``

## Install Programmatic API Command
1. ``$ go get -u github.com/swensonpn-playground/go-programmatic-api-create``
1. Add import to cmd/create.go ``create "github.com/swensonpn-playground/go-programmatic-api-create"``
1. Call create.CreateScript("script name")

## References
* [github.com/spf13/cobra-cli](https://github.com/spf13/cobra-cli)