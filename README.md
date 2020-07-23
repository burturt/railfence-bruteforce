# railfence-bruteforce
a simple python implementation of the Rail Fence cipher that bruteforces the rail count AND offset. If you have known plaintext, consider piping the output into a grep.

`python railfence.py "ENCRYPTED TEST"`

If you know any of the plaintext (e.g. "flag") I highly recommend doing `python railfence.py "ENCRYPTED TEST" | grep "[PLAINTEXT]"`. Otherwise, there are only so many options so you should be able to just scroll through the output and find what you need

**Python 2 only - I did not make the function that does the actual decryption**

[Rail Fence cipher](https://en.wikipedia.org/wiki/Rail_fence_cipher)
is a super weak cipher.
