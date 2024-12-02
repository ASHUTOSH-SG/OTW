## Bandit Level 1 → Level 2
## Level Goal
The password for the next level is stored in a file called — located in the home directory

## learnings

1. **`ls -a`**  
   - Lists all files, including hidden ones.  
   - Output: `-`, `.`, `..`, and shell config files.

2. **`cat < -`**  
   - Reads input from the file named `-` using redirection.  
   - Output: `263JGJPfgU6LtdEvgfWU1XP5yac29mFx`.

3. **`cat ./-`**  
   - Explicitly refers to the file `-` using `./`.  
   - Output: Same as above.

### **Key Points**
- **Special filenames:** Use `./` to handle files like `-` that resemble options.  
- **Redirection (`<`):** Reads file input for commands.  
- **Hidden files:** Use `ls -a` to view files starting with `.`.  
- Both `cat < -` and `cat ./-` display the same content but differ in handling.

- **`cat < -`**: Uses input redirection; `-` is treated as a file to read input from.  
- **`cat ./-`**: Explicitly specifies `-` as the filename in the current directory using `./`.  

Both show the same content, but the first relies on redirection, while the second directly accesses the file.