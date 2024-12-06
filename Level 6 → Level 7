## Bandit Level 6 → Level 7
## Level Goal
The password for the next level is stored somewhere on the server and has all of the following properties

- owned by user bandit7
- owned by group bandit6
- 33 bytes in size



### Problem Requirements:
1. **File owner:** `bandit7`.
2. **Group owner:** `bandit6`.
3. **File size:** 33 bytes.
4. **Search location:** Entire server (`/`).
5. **Suppress errors:** Avoid clutter caused by permission-denied messages.

### Command Explanation:

```bash
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
```

1. **`find /`:**  
   Starts the search from the root directory (`/`), covering all files and directories on the system.

2. **`-user bandit7`:**  
   Limits the search to files owned by the user `bandit7`.

3. **`-group bandit6`:**  
   Filters further to only include files owned by the group `bandit6`.

4. **`-size 33c`:**  
   Ensures the file is exactly 33 bytes in size.  
   - `c` specifies the size in bytes.

5. **`2>/dev/null`:**  
   Redirects standard error (e.g., "Permission denied") to `/dev/null` (a "black hole" for unwanted output). This keeps the output clean and focused on the result.

---


### Example Output:
```bash
/var/lib/dpkg/info/pass.txt
```

Display the file contents:
```bash
cat /var/lib/dpkg/info/pass.txt
```

