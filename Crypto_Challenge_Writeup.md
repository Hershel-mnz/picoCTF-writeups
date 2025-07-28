# Easy Peasy (Cryptography)

### Challenge Description
A message was encrypted with a repeating XOR key. Can you decrypt it?

### Thought Process
Repeating XOR can be broken by XORing the ciphertext with the key. The hint suggested that the key length was small.

### Approach
1. Downloaded the provided encrypted file.
2. Used `CyberChef` to analyze the ciphertext.
3. Found the repeating key by frequency analysis.
4. Decrypted the message.

### Tools Used
- CyberChef (https://gchq.github.io/CyberChef/)

### Solution
Decrypted text revealed the flag:
picoCTF{CRYPTO_IS_FUN}

