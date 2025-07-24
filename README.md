$ cat README.md
# csr-cipher

A simple brute-force Caesar cipher decryption tool written in Bash.

This script takes a string and applies all 25 Caesar cipher shifts to it, converting the string to lowercase first. It's useful for solving basic substitution ciphers, beginner CTF challenges, or for learning purposes.

## Features

- Brute-forces all Caesar cipher shifts (1 through 25).
- Converts input to lowercase for consistency.
- Uses only built-in Bash and `tr`.
- Portable: works on any Unix-like system (Linux, macOS, Termux, etc.).

## Installation

Clone the repository:

    git clone https://github.com/Gh0st-0f-Th/csr-cipher.git
    cd csr-cipher

Make the script executable:

    chmod +x csrcipher install

Run the auto-installation tool:

    bash install

## Usage

    csrcipher "your encrypted string"

Example:

    csrcipher "WKH HDJOH KDV ODQGHG"

Output:

    xli iegmi lev perhih
    ymj jfhmj mfw qfsijf
    ...

(You'll see all possible Caesar shifts of the original input.)

## Notes

- Only lowercase letters are used during rotation; the script forces input to lowercase.
- Spaces and non-alphabetic characters are preserved as-is.

## License

MIT License — see LICENSE file for details.

## Author

Gh0st-0f-Th
