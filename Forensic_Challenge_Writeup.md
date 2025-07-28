# Matryoshka doll (Forensics)

### Challenge Description
A file contains several nested files. Can you find the flag?

### Thought Process
The challenge name hints at "matryoshka dolls," which are nested layers. Likely a zip within a zip.

### Approach
1. Downloaded the file `dolls.jpg`.
2. Used `binwalk` to extract hidden files.
3. Found multiple compressed archives inside.
4. Repeatedly unzipped until I reached `flag.txt`.

### Tools Used
- `binwalk`
- `unzip`
- Linux terminal

### Solution
The final file revealed:
picoCTF{f1l3_1n_4_f1l3}

