
# File Encryption Tool

This is a simple C++ script for Windows that encrypts files using the AES encryption algorithm from the OpenSSL library.

## Requirements

- Windows operating system
- OpenSSL library installed and properly linked in your project

## Usage

1. Compile the C++ code with the appropriate OpenSSL libraries linked.
2. Run the compiled executable.
3. Provide the path to the input file you want to encrypt.
4. The encrypted output file will be generated in the same directory as the input file with "_encrypted" appended to its name.

## Example

```bash
$ ./file_encryption_tool
Enter the path to the input file: input.txt
File encrypted successfully. Encrypted file saved as: encrypted_input.txt
```

## Security Considerations

- Always handle encryption keys securely.
- Use strong and unique keys for each encryption operation.
- Ensure proper file permissions are set to protect encrypted files.

