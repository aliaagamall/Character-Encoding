# Character Encoding Detection and Conversion

This repository contains a notebook demonstrating how to detect and convert character encodings of files using Python. The notebook provides functions to identify file encodings and convert them to UTF-8 format.

## Overview

This project uses the `chardet` library to detect the encoding of text files and provides functions to read files with the detected encoding and save them in UTF-8 format.

## Files

The following files are included in this project:

- **file_guide.csv**: A CSV file containing metadata or guides.
- **olaf_Windows-1251.txt**: A text file encoded in Windows-1251.
- **shisei_UTF-8.txt**: A text file encoded in UTF-8.
- **die_ISO-8859-1.txt**: A text file encoded in ISO-8859-1.
- **harpers_ASCII.txt**: A text file encoded in ASCII.
- **yan_BIG-5.txt**: A text file encoded in Big5.
- **portugal_ISO-8859-1.txt**: A text file encoded in ISO-8859-1.

## Dataset

The data used in this project is sourced from Kaggle. You can access the dataset [here](https://www.kaggle.com/datasets/rtatman/character-encoding-examples/data).

## Dependencies

This notebook requires the following Python libraries:

- `numpy`
- `pandas`
- `chardet`

### Install them using pip:

```bash
pip install numpy pandas chardet
```
## Functions

- detect_encoding(file_path): Detects the encoding of a file.
- read_file_with_encoding(file_path, encoding=None): Reads a file with the specified or detected encoding.
- save_file_as_utf8(file_path, text): Saves the text content of a file as UTF-8 encoded.
- process_file(file_path): Reads a file with its detected encoding and saves it as UTF-8.

## Usage
- Install Dependencies:

```bash
pip install numpy pandas chardet
```
- Open the notebook in Jupyter or Kaggle.
- Execute all cells to process and convert the files.

## Example Output
The notebook processes the files and saves them with UTF-8 encoding. Example output includes:

- utf8_file_guide.csv
- utf8_olaf_Windows-1251.txt
- utf8_shisei_UTF-8.txt
- utf8_die_ISO-8859-1.txt
- utf8_harpers_ASCII.txt
- utf8_yan_BIG-5.txt
- utf8_portugal_ISO-8859-1.txt
  
## Contributing
Feel free to contribute by opening issues or submitting pull requests.

## License
This project is licensed under the MIT License.

## Contact
For any questions or feedback, contact [alliaagamall@gmail.com],
[Kaggle Profile](https://www.kaggle.com/aliaagamal)
