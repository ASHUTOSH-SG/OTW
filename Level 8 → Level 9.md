## Bandit Level 8 → Level 9

## Goal:
The password for the next level is stored in `data.txt` and is the only line that occurs once.

## Steps:
1. **List files:**
   ```bash
   ls
   ```

2. **Sort and find the unique line:**
   ```bash
   cat data.txt | sort | uniq -u
   ```

3. **Password:**
   ```
   4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
   ```

## Explanation:
- `cat data.txt`: Displays file contents.
- `sort`: Sorts the file lines.
- `uniq -u`: Prints only lines that occur once.

## Key Notes:
- The `-u` option in `uniq` is used to show only lines that occur exactly once.
```
