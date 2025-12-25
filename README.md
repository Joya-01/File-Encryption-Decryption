# File Encryption & Decryption Tool 

A high-performance file security tool built in C++ that allows users to encrypt and decrypt files efficiently. This project demonstrates secure file handling and data manipulation concepts.

## Project Overview
This tool is designed to protect sensitive data by converting files into an unreadable format (encryption) and restoring them to their original state (decryption) using a specific key or algorithm. It is lightweight, fast, and runs directly from the terminal.

## Technologies Used
- **C++**: The core programming language used for logic and file stream handling.
- **Makefile**: Automated build script to compile the project easily.
- **File Handling**: Uses C++ `fstream` library to read and write binary/text files.

## How to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Joya-01/File-Encryption-Decryption.git

2. **Navigate to the project directory:**
   ```bash
   cd File-Encryption-Decryption

3. **Compile the Code:**
   ```bash
   make
   (Or manually compile using g++ if needed:)
   ```bash
   g++ encrypty/main.cpp -o encryptor

4. **Run the Application:**
   ```bash
   ./encryptor

## Project Structure

  encrypty/: Folder containing the C++ source code files.

  Makefile: Script to automate the compilation process.
