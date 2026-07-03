# Sprint 2.1 – Dataset Loading and File Handling

## AI/ML Engineer Training Program

**Engineer:** Apuri Saikumar

---

# Project Overview

This project demonstrates a reusable Dataset Loading Utility developed as part of Sprint 2.1 of the AI/ML Engineer Training Program.

The objective is to understand how datasets are loaded, validated, managed, and written using Python while following software engineering best practices.

The implementation is completed using Jupyter Notebook with detailed Markdown explanations, modular functions, logging, and exception handling.

---

# Objectives

- Load datasets from multiple file formats
- Save datasets into multiple output formats
- Implement reusable helper functions
- Configure centralized logging
- Handle exceptions gracefully
- Follow clean coding standards
- Document the implementation

---

# Supported File Formats

## Input

- CSV
- Excel (.xlsx)
- JSON
- TXT

## Output

- CSV
- Excel
- JSON
- TXT
- Pickle

---

# Project Structure

```text
sprint2_dataset_loading/

│
├── datasets/
│
├── logs/
│
├── notebooks/
│     Sprint2_Dataset_Loading_and_File_Handling.ipynb
│
├── outputs/
│
├── README.md
│
└── requirements.txt
```

---

# Modules Implemented

## Module 1

CSV Loader

Features

- Read CSV files
- Custom delimiter
- UTF-8 encoding
- Chunk processing
- File validation
- Exception handling

---

## Module 2

Excel Loader

Features

- Read Excel files
- Read worksheets
- Read multiple sheets
- Invalid worksheet handling

---

## Module 3

JSON Loader

Features

- Read JSON
- Nested JSON
- Invalid JSON handling

---

## Module 4

TXT Loader

Features

- Read complete file
- Read line by line
- Encoding support

---

## Module 5

Dataset Writer

Supports

- CSV
- JSON
- Excel
- TXT
- Pickle

---

## Module 6

File Path Management

- Path validation
- Directory creation
- Output filename generation
- Relative paths
- Absolute paths

---

## Module 7

Logging

Application logging includes

- INFO
- WARNING
- ERROR
- Exception details

Logs are stored in

logs/application.log

---

## Module 8

Exception Handling

Implemented

- try
- except
- finally
- raise
- Custom exceptions

---

# Technologies Used

- Python 3.12
- Pandas
- OpenPyXL
- JSON
- Logging
- Pickle
- Pathlib
- Jupyter Notebook

---

# Installation

```bash
git clone https://github.com/apurisaikumar/sprint2_Assessment.git

cd sprint2_dataset_loading

python -m venv venv

source venv/Scripts/activate

pip install -r requirements.txt
```

---

# Running the Project

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Sprint2_Dataset_Loading_and_File_Handling.ipynb
```

Run all cells from top to bottom.

---

# Logging

Application logs are generated under

```
logs/application.log
```

---

# Outputs

Generated datasets are stored in

```
outputs/
```

---

# Coding Standards

The project follows

- PEP-8
- Modular programming
- Reusable functions
- Type hints
- Docstrings
- Meaningful variable names
- Exception handling

---

# Assumptions

- Dataset files are available inside the datasets folder.
- UTF-8 encoding is used.
- Output directories are created automatically.

---

# Future Enhancements

- Cloud storage integration
- Database support
- XML loader
- API-based dataset loading
- Docker support
- CI/CD pipeline
- Unit testing

---

# Key Learnings

Through this sprint the following concepts were strengthened:

- Dataset loading
- Dataset writing
- File handling
- Logging
- Exception handling
- Reusable functions
- Python best practices
- Software engineering principles