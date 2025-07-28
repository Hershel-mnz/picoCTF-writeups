# PW Crack 1 (Binary Exploitation)

### Challenge Description
A program asks for a password. Can you find the correct one?

### Thought Process
Since I didn’t know the password, I tried looking inside the program itself. Binary challenges often hide strings directly.

### Approach
1. Downloaded the file `pw_crack`.
2. Ran `strings pw_crack` in the terminal — this shows all human-readable text inside the program.
3. Found a line that looked like the password: `pico123`.
4. Ran the program and entered `pico123` as the password.

### Tools Used
- `strings` command (Linux terminal)

### Solution
The program printed:

