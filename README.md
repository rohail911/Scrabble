# Scrabble Using C++
# Dictionary Project

## Description
This project is a C++ console application designed to efficiently process and utilize a large-scale English dictionary dataset. Built with a focus on performance and data structure optimization, the application reads from a raw text database (`dictionary.txt`) to perform lookups and vocabulary management operations.

Key features include:
* **Efficient Data Handling:** Utilizes C++ Standard Template Library (STL) data structures for rapid word retrieval.
* **File I/O Integration:** Robust parsing logic to handle external dictionary files.
* **Console Interface:** A streamlined CLI (Command Line Interface) for user interaction.

## Files
* **`projectfinal.exe`**: The compiled binary executable.
* **`dictionary.txt`**: The database file containing a comprehensive list of English words.
* **`main.cpp`**: The source code entry point.

## How to Run
1.  Ensure `dictionary.txt` is located in the same folder as the executable.
2.  Run the application via the command line:
    ```bash
    ./projectfinal
    ```

## Build Instructions
To compile the project from source, use a standard C++ compiler like `g++`:

```bash
g++ main.cpp -o projectfinal
