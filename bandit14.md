# Bandit Level 13 → Level 14

## Level Goal
The password for the next level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. Look at the commands that logged you into previous bandit levels, and find out how to use the key for this level.
If you need help with this level: a hint file can be found in the home directory.
Make sure to read the error messages as they are informative.

## Key concepts learnt
1. Instead of a password we can connect to the server using an SSH private key.
> GitHub uses SSH keys or Personal Access Tokens (PATs) instead of account passwords for authenticating Git operations like cloning, pushing, and pulling.
2. Private keys should be kept secure.
3. File Permissions `(chmod)` - proper permissions prevents unauthorised users from accessing sensitive files.
4. `scp` (Secure Copy Protocol) command - used to securely transfer files over an encrypted SSH connection.
5. Logging into remote servers with `ssh -i <key>`.

