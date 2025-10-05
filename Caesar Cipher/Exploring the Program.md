Caesar Cipher Program – Exploration Q&A
1. What happens if you change SYMBOLS = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ' to SYMBOLS = 'ABC'?
Only the letters A, B, and C will be encrypted or decrypted. All other characters remain unchanged.
2. What happens when you encrypt a message with key 0?
The message is not changed; output is the same as input.
3. What error message do you get if you delete or comment out translated = ''?
You get:
UnboundLocalError: local variable 'translated' referenced before assignment
4. What error message do you get if you delete or comment out key = int(response)?
You get:
UnboundLocalError: local variable 'key' referenced before assignment
5. What happens if you change translated = translated + SYMBOLS[num] to translated = translated + symbol?
The program no longer encrypts or decrypts; the output is always the same as the input.