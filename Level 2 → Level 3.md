## Bandit Level 2 → Level 3
### Level Goal
The password for the next level is stored in a file called spaces in this filename located in the home directory

## Learnings: Handling Filenames with Spaces in Linux

## Key Points:
1. **Issue**: `cat spaces in this filename` fails because spaces split the filename into arguments.
2. **Solutions**:
   - Use escape characters (`\`) before spaces:
     ```bash
     cat spaces\ in\ this\ filename
     ```
   - Or wrap the filename in quotes:
     ```bash
     cat "spaces in this filename"
     cat 'spaces in this filename'
     ```

## Takeaway:
Always escape spaces or use quotes to handle filenames with spaces.
