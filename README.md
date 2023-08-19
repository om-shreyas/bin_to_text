# Text To Binary and Binary To Text Programs

## Introduction

This repository contains two Python programs, namely "Text To Binary" and "Binary To Text." These programs allow you to convert text to binary representation and vice versa.

## Author

**Author:** Shreyas Om

## Programs

### Text To Binary Program

- **Function:** `texttobin(file_name)`

    - This function takes a filename as input, reads the text data from the file, and converts it into a binary representation.
    - It then writes the binary data back to the same file, overwriting the existing content.

- Usage Example:

    ```python
    texttobin("input.txt")
    ```

### Binary To Text Program

- **Function:** `bintotext(file_name)`

    - This function takes a filename as input, reads binary data from the file (assumed to be space-separated), and converts it into text.
    - It then writes the text data back to the same file, overwriting the existing content.

- Usage Example:

    ```python
    bintotext("output.txt")
    ```

## How to Use

1. Clone or download this repository to your local machine.

2. Ensure you have Python installed.

3. Create a text file with the content you want to convert (for Text To Binary) or a binary data file (for Binary To Text).

4. Modify the `file_name` parameter in the function calls with the name of your file.

5. Run the Python script with the desired function to perform the conversion.

6. Check the output file for the converted data.

## Example

Suppose you have a file named "input.txt" with the text "Hello, World!".

You can use the "Text To Binary Program" as follows:

```python
texttobin("input.txt")

This will overwrite "input.txt" with the binary representation of the text.

To convert it back to text, use the "Binary To Text Program":

python

bintotext("input.txt")

This will restore "input.txt" to its original text content.