The notebook in this repo contains definitions relating to unique decodability and functions which check a code 
(presented as a set of code-words) for unique decodability using the Sardinas-Patterson Algorithm.

In a nutshell, the algorithm checks to see if any code word in the original code can be used as a suffix on a
sequence of words to create ambiguity in decoding. If so, the code is not uniquely decodable.

For example consider the set C of code-words:

C = {02, 12, 120, 20, 21}

Consider the string

1202120

This can be decoded in two ways:

120.21.20

12.02.120

Thus, C is not uniquely decodable.
