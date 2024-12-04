## Bandit Level 3 → Level 4
## Level Goal
The password for the next level is stored in a hidden file in the inhere directory.

### learning Notes: Accessing Hidden Files in Linux

## Key Points:
1. **Hidden File**: Files beginning with `.` are hidden and require specific handling.
   - Example: `...Hiding-From-You`.

2. **Commands Used**:
   - `ls`: Lists visible files.
   - `ls -al`: Displays all files, including hidden ones.
   - `cat ...Hiding-From-You`: Accesses the content of the hidden file.

3. **Example**:
   ```bash
   bandit3@bandit:~/inhere$ ls -al
   -rw-r----- 1 bandit4 bandit3   33 Sep 19 07:08 ...Hiding-From-You

   bandit3@bandit:~/inhere$ cat ...Hiding-From-You
   2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
