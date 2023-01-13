# Installation

To use the password generator, you need to have Node.js and npm (Node Package Manager) installed on your system.

- Clone the repository or download the source code
- Run npm install to install the required dependencies.

# Usage

The generator can be run using the following command:

`
node index.js generate
`

By default, the generated password will be of length 8 and will include letters, numbers, and symbols.

# Options

- `-l, --length <password_length>` : The length of the generated password. If not specified, the default length is 8.
- `nn` : The generated password will not include numbers.
- `ns` : The generated password will not include symbols.
- `-s` : The generated password will be saved to a file named "password.txt" in the current directory.

# Examples

- To generate a password of length 12:

`node index.js generate -l 12`

- To generate a password without numbers:

`node index.js generate nn`

- To generate a password of length 16 without symbols:

`node index.js generate -l 16 ns`

- To generate a password and save it to a file

`node index.js generate -s`

# Note

It's recommended that you use the `-s` option to save the password to a file and keep it in a safe place.

This is a basic example of how you can use commander library to build a CLI for your application. You can further customize the options and commands to suit your needs.







