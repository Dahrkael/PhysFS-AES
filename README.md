# PhysFS library with AES encryption support (password protected zips)
Library Version 2.0.2
Added support for 128, 192 or 256 AES encryption

in zip.c  file, lines 1561 and 1562 you can specify the password to decrypt AES encrypted zip files.
since it was just a test, the password is set at compile time.