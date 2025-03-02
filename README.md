# Quick Exploration and Retrieval (QER) System

The **QER** file format is designed for efficient compression, reducing file sizes by approximately **70%**. This open-source system enables quick compression, decompression, and analysis of data in `.qer` files.

## Features

- **Efficient Compression**: Compress files into `.qer` format with up to 70% size reduction.
- **Decompression**: Extract and access data from `.qer` files.
- **Data Read**:  The tool will only support reading (and not modifying) .qer files.

## How to Use

### 1. Compress Files into `.qer` Format

To compress files into a `.qer` archive, use the following command:

   ```cmd
   python qercompress.bin test1.jpg test2.rar test3.zip -n namefile.qer
   ```

### 2.  Extract Files from .qer Format

To decompress and extract files from a .qer file, use:
   ```cmd
  python qertract.bin namefile.qer
   ```

### 3. Readonly .qer Files

To read the contents of a .qer file, use:

 ```cmd
  python qerreadonly.bin namefile.qer
   ```


## For windows by cmd
 ```cmd
qercompress.exe test1.jpg test2.rar test3.zip -n namefile.qer
   ```
 ```cmd
qertract.exe namefile.qer
   ```
 ```cmd
qerreadonly.exe namefile.qer
   ```

