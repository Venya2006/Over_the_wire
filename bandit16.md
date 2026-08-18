# Bandit Level 15 → Level 16

## Level Goal
The password for the next level can be retrieved by submitting the password of the current level to port 30001 on localhost using SSL/TLS encryption.

Helpful note: Getting “DONE”, “RENEGOTIATING” or “KEYUPDATE”? Read the “CONNECTED COMMANDS” section in the manpage.

## Key concepts learnt
1. `SSL/TLS` (Secure Sockets Layer and Transport Layer Security) are security protocols that create an encrypted link between a web browser and a server.They protect sensitive data.
2. openssl command to establish a secure connection with an SSL server.
3. The `s_client` module establishes a transparent connection to a remote server speaking SSL/TLS. It's intended for testing purposes only
