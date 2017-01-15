# whois.go

whois-go is a simple Go module for domain whois.

## Overview

whois.go: A golang module for domain whois query.

cli/main.go: A golang cli command for domain whois query.

cli/build.sh: Build the cli command and test it.

*Work for most domain extensions and most of the time.*

## Installation

    go get github.com/easyconn/whois-go

## Importing

    import (
        "github.com/easyconn/whois-go"
    )

## Documentation

    func Whois(domain string, servers ...string) (result string, err error)

## Example

    result, err := whois.Whois("example.com")
    if err == nil {
        fmt.Println(result)
    }


## Whois info parser in Go

Please refer to [whois-parser-go](https://github.com/easyconn/whois-parser-go)

- [http://www.likexian.com/](http://www.likexian.com/)
