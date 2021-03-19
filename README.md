# Oswald
an OpenSSL Wrapper for general purpose encrypting and decrypting

## Rationale
Sometimes I like to encrypt things using OpenSSL; this is a wrapper around it
so that I don't need to Google or reread the man page every time.


## Usage
**Help Output**
```
USAGE: oswald COMMAND [OPTIONS] THING
	encrypt [OPTIONS] : Encrypts, defaults to STDIN and STDOUT
	decrypt [OPTIONS] : Decrypts, defaults to STDIN and STDOUT
	help              : prints this
 [OPTIONS] can be any valid OpenSSL command line options
```
