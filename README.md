# ROT-13 Decoder/Encoder
 * Initially written for fun for a CTF
 * Can take a string and encode/decode using ROT13

From [Wikipedia:](https://en.wikipedia.org/wiki/ROT13)
> Applying ROT13 to a piece of text merely requires examining its alphabetic characters and replacing each one by the letter 13 places
> further along in the alphabet, wrapping back to the beginning if necessary. A becomes N, B becomes O, and so on up to M, which
> becomes Z, then the sequence continues at the beginning of the alphabet: N becomes A, O becomes B, and so on to Z, which becomes M.
> Only those letters which occur in the English alphabet are affected; numbers, symbols, whitespace, and all other characters are left
> unchanged. Because there are 26 letters in the English alphabet and 26 = 2 × 13, the ROT13 function is its own inverse:

### To-Do
 - [x] Write simple script for encoding and decoding ROT13 strings
 - [x] Write to accept string as an argument and return the desired string
 - [ ] Debug