# File-Zipper
This project is based on Huffman Coding, a lossless, bottom-up compression algorithm.

This project is based on Huffman Coding, a lossless, bottom-up compression algorithm. It can compress and decompress any text files.

Implementation in Project
This project supports two functions:
1) Encode: Compresses input file passed.
2) Decode: Decompresses Huffman coded file passed back to its original file.

How to run this project?
To run this project you need to create an executable file.
1) For compressing:

$: g++ encode.cpp huffman.cpp -o root
$: ./root inputFile.txt compressFile.huf

Compressed successfully

2) For Decompressing:

$: g++ decode.cpp huffman.cpp -o root
$: ./root compressFile.huf outputFile.huf

Decompressed successfully
