# Unique
---

# Unique Integer Processor

The Unique Integer Processor is a Node.js script designed to process text files containing integer values, extract unique integers within a specified range, and write them to an output file.

## Features

- Processes text files containing integer values.
- Extracts unique integers within the range of -1023 to 1023.
- Sorts the extracted unique integers in ascending order.
- Outputs the sorted unique integers to a separate file.

## Usage

1. **Installation**: Ensure you have Node.js installed on your system.

2. **Setup**:
   - Clone or download the script files to your local machine.
   - Ensure you have a directory named `input_files` containing the text files with integer values you want to process.

3. **Running the Script**:
   - Open a terminal or command prompt.
   - Navigate to the directory where the script files are located.
   - Run the script using the following command:
     ```
     node processor.js
     ```

4. **Output**:
   - The processed files will be saved in the `output_files` directory with the original file name appended with `_results.txt`.

## File Structure

- **processor.js**: The main Node.js script responsible for processing the input files.
- **input_files**: Directory containing input text files with integer values.
- **output_files**: Directory where the processed files with unique integers will be saved.

## Requirements

- Node.js

## Note

- Ensure that the input files are formatted properly with one integer per line.
- Only files with a `.txt` extension in the `input_files` directory will be processed.

## Author

Joe Freeman NINDORERA
