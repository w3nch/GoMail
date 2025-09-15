# GoMail

GoMail is a robust and efficient command-line tool written in Go, designed to verify the validity of email addresses. Whether you're cleaning up your email list, checking user input, or validating emails for any other reason, GoMail provides a simple and powerful solution.

## Features

- **Fast and Efficient**: Built with Go for high performance and quick verification.
- **MX Record Lookup**: Verifies the existence of the domain's mail server.
- **Syntax Check**: Ensures the email address adheres to standard email format.
- **Disposable Email Detection**: Identifies disposable email addresses.
- **Command-Line Interface**: Easy to use with clear commands and options.
- **Output Options**: Supports various output formats including JSON and plain text.

## Installation

You can install GoMail using `go get`:

```sh
go get -u github.com/w3nch/GoMail.git
