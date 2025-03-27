# PDF Combiner

A simple command-line tool to combine PDF files in a folder.

## Installation

```bash
pip install pdf-combiner
```

## Usage

Combine PDFs in the current directory:
```bash
pdf-combiner .
```

Combine PDFs in a specific folder with a custom output name:
```bash
pdf-combiner /path/to/pdfs -o merged.pdf
```

### Options

- `folder`: Path to the folder containing PDF files (required)
- `-o, --output`: Name of the output PDF file (optional, default: combined.pdf)

## Features

- Combines all PDF files in a specified folder
- Sorts PDFs alphabetically before combining
- Simple command-line interface

## Requirements

- Python 3.7+
- PyPDF2

## License

MIT License