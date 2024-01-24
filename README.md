
# File Packer Unpacker - Java

## Overview

This Java-based project facilitates file packing and unpacking activities in two distinct parts. The first part involves combining all the contents of a specified folder into a single file, referred to as a "packed file." The second part of the project focuses on unpacking, where the packed file is provided as input, and the original folder structure and files are regenerated.

## Technology: Java Programming

The entire project is implemented using Java programming language.

## Project Components

The project is structured into two main parts:

1. **Packing Activity:**
   - Accepts a user-specified folder as input.
   - Combines all the contents of the folder into a single file.
   - The resulting file is named the "packed file."

2. **Unpacking Activity:**
   - Accepts the packed file as input.
   - Extracts and reconstructs the original folder structure and files.

## How to Use

### Packing Activity:

1. **Input:**
   - Provide the path to the folder you want to pack.

2. **Execution:**
   - Run the packing activity of the project using the appropriate Java command.

   ```bash
   java -cp . PackMain /path/to/source/folder
   ```

3. **Output:**
   - A single file containing all the contents of the specified folder (packed file).

### Unpacking Activity:

1. **Input:**
   - Provide the path to the packed file.

2. **Execution:**
   - Run the unpacking activity of the project using the appropriate Java command.

   ```bash
   java -cp . UnpackMain /path/to/packed/file
   ```

3. **Output:**
   - The original folder structure and files are reconstructed.

## Requirements

- Ensure that Java is installed on your system.
- Compile the Java files using `javac` before executing.

```bash
javac PackMain.java UnpackMain.java
```

## Usage Examples

### Packing Activity:

```bash
java -cp . PackMain /path/to/source/folder
```

### Unpacking Activity:

```bash
java -cp . UnpackMain /path/to/packed/file
```

## Notes

- This Java project provides a platform-independent solution for packing and unpacking files.
- The compilation step may be required before executing the project.

## Contributors

- Nikhil Hemant Jadhav

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it.

## Support

For any questions or issues, please contact [your email address].

Thank you for using the File Packer Unpacker in Java!
