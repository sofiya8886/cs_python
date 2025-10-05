Caesar Cipher Program – Exploration Q&A

Q1: What happens if you change SYMBOLS = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ' to SYMBOLS = 'ABC'?
A: Only the letters A, B, and C will be encrypted or decrypted. All other characters remain unchanged.

Q2: What happens when you encrypt a message with key 0?
A: The message is not changed; the output is the same as the input.

Q3: What error message do you get if you delete or comment out translated = ''?
A: UnboundLocalError: local variable 'translated' referenced before assignment

Q4: What error message do you get if you delete or comment out key = int(response)?
A: UnboundLocalError: local variable 'key' referenced before assignment

Q5: What happens if you change translated = translated + SYMBOLS[num] to translated = translated + symbol?
A: The program no longer encrypts or decrypts; the output is always the same as the input.

