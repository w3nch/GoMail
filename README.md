GoRify

GoRify is a robust and efficient command-line tool written in Go, designed to verify the validity of email addresses. Whether you're cleaning up your email list, checking user input, or validating emails for any other reason, GoRify provides a simple and powerful solution.
Features

    Fast and Efficient: Built with Go for high performance and quick verification.
    MX Record Lookup: Verifies the existence of the domain's mail server.
    Syntax Check: Ensures the email address adheres to standard email format.
    Disposable Email Detection: Identifies disposable email addresses.
    Command-Line Interface: Easy to use with clear commands and options.
    Output Options: Supports various output formats including JSON and plain text.

Installation

You can install GoRify using go get:

sh

go get -u github.com/yourusername/gorify

Usage

sh

gorify [options] <email>

Options:

    -f, --file: Verify multiple emails from a file.
    -o, --output: Specify the output format (json, text).
    -v, --verbose: Enable verbose output.
    -h, --help: Show the help message.

Examples

Verify a single email address:

sh

gorify example@example.com

Verify multiple email addresses from a file:

sh

gorify -f emails.txt

Get the output in JSON format:

sh

gorify -o json example@example.com

Contributing

We welcome contributions! Please see our contributing guidelines for more details.
License

GoRify is released under the MIT License. See LICENSE for more information.
Acknowledgements

Special thanks to all the contributors and the Go community for their continuous support and contributions.
