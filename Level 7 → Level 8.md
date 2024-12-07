## Bandit Level 7 → Level 8
### Level Goal
The password for the next level is stored in the file data.txt next to the word millionth



### Steps:
1. **List directory contents**:
   ```bash
   ls
   ```
   Output: `data.txt`

2. **Search for the keyword "millionth"**:
   ```bash
   cat data.txt | grep millionth
   ```
   Output:
   ```
   millionth       dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc

