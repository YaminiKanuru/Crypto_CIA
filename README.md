# Crypto_CIA

**1. Caesar Cipher** 
A simple letter‐shift cipher (with user-specified shift).

**2. Atbash Cipher**
A substitution cipher that “mirrors” the alphabet.

**3. August Cipher** 
In this example we interpret “August” as a specialized Caesar cipher using a fixed shift of 8 (recalling that August is the 8th month).

**4. Affine Cipher**  
Uses the formula *E(x) = (ax + b) mod 26* (with modular inversion for decryption).

**5. Vigenère Cipher**  
A polyalphabetic cipher using a string key to vary the shift on each letter.

**6. Gronsfeld Cipher**  
Very similar to Vigenère but with a numerical key (each digit represents a shift).

**7. Beaufort Cipher**  
A reciprocal cipher where encryption and decryption are performed by the same routine.  
The formula used here is **C = (K – P + 26) mod 26**.

**8. Autoclave / Running Key Cipher**  
A variant of the Vigenère cipher that uses a long key (often from a text). Here we assume the key is provided (and if shorter, it is repeated).

**9. Ngram Operations**  
A simple utility that counts the frequency of every n‑gram (substring of length n) in a text.

**10. Hill Cipher (2x2 Matrix Example)**  
A matrix‐based cipher where plaintext is split into digrams and multiplied by a key matrix modulo 26.

**11. Rail Fence Cipher**  
A transposition cipher that “zigzags” the message along a set number of rails.

**12. Route Cipher**  
A simple transposition cipher that writes the message into a grid and reads it column‐wise. (Spaces are removed and padding with ‘X’ is applied.)

**13. Myszkowski Cipher**  
A columnar transposition cipher variant in which columns with identical key letters remain in their original order.  
In this example the plaintext is written into a grid (padding with ‘X’ as needed) and then the columns are read in the order determined by a stable sort of the key letters.
