# Steganographer

#### Java text steganography library

A java library which creates a string with a secret message hidden within, kept secret with the use of 0 length unicode characters converted with binary strings.

| Function | Params | Return type | Use |
| --- | --- | --- | --- |
| steganographize | String publicMessage, String privateMessage | String messageWithPrivateMessage | Store a secret message within a public message |
| reveal | String publicMessage | String privateMessage | Retrieve the secret message from a public message |
