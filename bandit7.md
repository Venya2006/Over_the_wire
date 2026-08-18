# Bandit Level 1 -> Level 2

## Level Goal
The password for the next level is stored somewhere on the server and has all of the following properties:

- owned by user bandit7
- owned by group bandit6
- 33 bytes in size

## Key concepts learnt
1. Using the `find` command lets you search using multiple filters like file size, ownership, and permissions
2. Bytes is mentioned as c.
3. File permissions are critical for security purposes (read, write, execute).
4. When searching through directories you don’t have permission to access, redirecting error messages with `2>/dev/null` helps hide permission denied warnings and keeps the output tidy.
