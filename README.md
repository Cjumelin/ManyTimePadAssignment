# Process

- First, we convert the message data into bytes.
- Next, we XOR the bytes together to eliminate the key.
- Then, we guess the key to produce a meaningful output.
- Once we reach a sensible starting point, we continue adding more characters, comparing the results, converting all the bytes to string format, and printing the output.
- When part of the key is correct, it appears as plaintext, indicating we are on the right track.
- This iterative process of guessing and building up the key string is how we fully recover the key.