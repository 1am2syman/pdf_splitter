<<<<<<< HEAD
# PDF Splitter

A command-line tool to split PDF files into multiple files based on page ranges.

## Features

- Split PDF files by specifying page ranges
- Maintains original file name as prefix for split files
- Creates output files in the same directory as input file
- Simple command-line interface
- Detailed help documentation

## Installation

### Using pip (Recommended)

```bash
pip install git+https://github.com/1am2syman/pdf_splitter.git
```

### Using git

1. Clone the repository:
```bash
git clone https://github.com/1am2syman/pdf_splitter.git
cd pdf_splitter
```

2. Install the package:
```bash
pip install .
```

### Using winget (Windows Package Manager)

Note: This package needs to be submitted to the Windows Package Manager repository first. Once approved, it can be installed using:

```powershell
winget install 1am2syman.pdf-splitter
```

## Usage

After installation, you can use the tool in two ways:

1. Using the installed command-line tool:
```bash
pdf-splitter input.pdf "1-10,11-20,21-30"
```

2. Running the Python script directly:
```bash
python -m pdf_splitter input.pdf "1-10,11-20,21-30"
```

### Examples

1. Split a PDF into three parts:
```bash
pdf-splitter document.pdf "1-10,11-20,21-30"
```
This will create:
- document_1-10.pdf
- document_11-20.pdf
- document_21-30.pdf

2. View help:
```bash
pdf-splitter --help
```

## Notes

- Page numbers start from 1
- Ranges should be in ascending order
- Use quotes around the ranges argument
- Output files will be named as 'originalname_start-end.pdf'
- Files are created in the same directory as the input file

## Requirements

- Python 3.6 or higher
- PyPDF2 3.0.0 or higher

## License

This project is licensed under the MIT License - see the LICENSE file for details.
=======
# pdf_splitter
>>>>>>> 3ad7289783ee91ffd9b1a63840e4cdaf91730f13
