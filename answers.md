# CMPS 2200 Recitation 7
## Answers

**Name:**___________Owen Ni______________


Place all written answers from `recitation-07.md` here for easier grading.



- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt    |           1340          |          826      |       0.616
alice29.txt    |     1039367                |      676374          |   0.651
asyoulik.txt    |       876253              |       606448         |  0.692
grammar.lsp    |           26047          |     17356           | 0.666
fields.c    |          78050           |      56206          |  0.720

Yes, typically huffman coding's cost is 0.65-0.7 of the fixed-length coding.


- **e.**
The expected cost of huffman encoding is frequency * number of character * log2 length, which is the same as the fixed length cost. It is consistent.

