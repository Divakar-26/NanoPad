# NanoPad
NanoPad is a terminal-based text editor inspired by nano. Written in C with under 1300 lines of code, it features syntax highlighting and search functionality, making it a lightweight yet powerful tool for terminal users. Built using the guide from KILO - Build Your Own Text Editor by Antirez, with full credit for inspiration.

Link of the article - https://viewsourcecode.org/snaptoken/kilo/

### Table Of Contents
- [Installation](#installation)
- [USAGE](#usase)
- [IMAGES/VIDEOS](#IMAGES)
- [CREDITS](#credits)

## Images


## Installation

### Prerequisites
- Ensure you have GCC (GNU c compiler)
- Make sure you have make installed(optional)
- Ensure you have git installed

### METHOD 1
#### STEPS TO INSTALL
1. Clone the repository:
    ```bash
        git clone https://github.com/Divakar-26/NanoPad
2. Navigate to Directory 
    ```bash
        cd NanoPad
3. Make install.sh Executable
    ```bash
        chmod +x install.sh
4. Run install.sh
    ```bash
        ./install.sh
5. You are done!!
    ```bash
        nanopad

### METHOD 2 - using GCC
#### STEPS TO INSTALL

1. Clone the repository OR just download nanopad.c:
    ```bash
        git clone https://github.com/Divakar-26/NanoPad
2. Navigate to Directory
    ```bash
        cd NanoPad
3. Compile Using GCC
    ```bash
        gcc nanopad.c -o nanopad
4. Run
    ```bash
        ./nanopad

### METHOD 3 - using MAKE
#### STEPS TO INSTALL
1. Clone the repository OR just download nanopad.c:
    ```bash
        git clone https://github.com/Divakar-26/NanoPad
2. Navigate to Directory
    ```bash
        cd NanoPad
3. Install Make(skip it if you have already)
    ```bash
        sudo apt install make
4. Compile using make
    ```bash
        make
5. RUN
    ```bash
        ./nanopad
    

## USASE
- Opening a file(use ./nanopad if nanopad is not working)
    ```bash
        nanopad FILE_NAME_WITH_EXTENSION

- Search
    1. CTRL+F to search
    2. Use Arrow keys to go to next result or previous
    3. Use ESC to exit search

- Saving a File
    CTRL+S to save

- Quiting NanoPad
    1. CTRL+Q to quit
    2. Press CTRL+Q 3 times if your file is not saved!


## CREDITS

- [DIVAKAR](https://github.com/Divakar-26)
- [ANTIREZ'S KILO](https://viewsourcecode.org/snaptoken/kilo/) 
