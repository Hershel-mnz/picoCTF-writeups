# Insp3ct0r (Web Exploitation)

### Challenge Description
A website has a flag hidden somewhere. Can you find it?

### Thought Process
The hint suggested checking the source code. Web challenges often hide data in HTML, CSS, or JS files.

### Approach
1. Opened the given URL.
2. Inspected the page source (`Ctrl + U`) and found a comment pointing to `/style.css`.
3. Opened `/style.css`, found a hint pointing to `/script.js`.
4. Opened `/script.js` and found the flag.

### Tools Used
- Browser Developer Tools

### Solution
The flag was hidden inside `script.js`:

