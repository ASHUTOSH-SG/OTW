## Bandit Level 4 → Level 5
## Level Goal
The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.

## Notes: Handling Files with Special Characters in Linux

## Key Points:
1. **Special Characters**: Files starting with a `-` can confuse commands as they are interpreted as options.
   - Example: `-file07`.

2. **Commands Used**:
   - `file ./*`: Checks file types in the current directory.
   - `cat ./-file07`: Correctly references the file using `./` to indicate it's in the current directory.

3. **Example**:
   ```bash
   bandit4@bandit:~/inhere$ file ./*
   ./-file07: ASCII text

   bandit4@bandit:~/inhere$ cat ./-file07
   4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
