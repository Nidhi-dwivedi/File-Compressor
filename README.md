# FileCompressor

A C++ project for file compression and decompression using Huffman coding. This project includes encoding and decoding functionality to efficiently compress and decompress files.

---

## Features

- **File Encoding**: Compresses input files using Huffman coding.
- **File Decoding**: Decompresses encoded files to their original state.
- **Huffman Coding Implementation**: Utilizes an efficient algorithm for lossless data compression.

---

## File Structure

- `encode.cpp`: Handles file compression (encoding).
- `decode.cpp`: Handles file decompression (decoding).
- `huffman.cpp`: Implementation of the Huffman coding algorithm.
- `huffman.hpp`: Header file for Huffman coding utilities.

---

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Nidhi-dwivedi/File-Compressor.git
   cd FileCompressor
   ```

2. Compile the Code: Use a C++ compiler like g++ to compile the source files. 
    Example:
   ```bash
    g++ -o encode encode.cpp huffman.cpp
    g++ -o decode decode.cpp huffman.cpp
   ```
   
3. Run the Program:
   To encode a file:
   ```bash
    ./encode input.txt output.huff
   ```
   To decode a file:
   ```bash
   ./decode output.huff decoded.txt
   ```
## Requirements
-A C++ compiler (e.g., g++)
-Basic knowledge of the command line

## Future Improvements
-Support for multiple file formats.
-Add a GUI for ease of use.
-Improve compression efficiency.

