# 🧬 DNA Profiling - Forensic Analysis Tool

[![Language: Python](https://img.shields.io/badge/Language-Python-3776AB.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📋 Overview
This forensic analysis tool identifies individuals based on their DNA sequences using **Short Tandem Repeats (STRs)**. It processes large CSV databases of known individuals and compares them against raw DNA sequences to find matches. This project demonstrates proficiency in Python's data handling, file I/O, and algorithmic optimization.

## 🚀 Features
- **Automated STR Counting**: Implements an efficient algorithm to find the longest consecutive run of STRs in a DNA string.
- **CSV Data Integration**: Parses and manages structured data using Python's `csv` module.
- **Scalable Matching**: Capable of handling databases with varying numbers of individuals and STR types.
- **Error Handling**: Validates command-line arguments and file paths.

## 🛠️ Technical Skills Demonstrated
- **Python Scripting**: Advanced use of lists, dictionaries, and file handling.
- **Data Analysis**: Comparing complex patterns across different data formats (CSV vs. TXT).
- **Algorithm Design**: Optimized string searching and pattern matching.
- **CLI Development**: Creating a user-friendly command-line interface.

## 💻 Getting Started

### Prerequisites
- Python 3.x

### Installation & Execution
1. Clone the repository:
   ```bash
   git clone https://github.com/njfw50/cs50-dna.git
   cd cs50-dna
   ```
2. Run the analysis:
   ```bash
   python dna.py data.csv sequence.txt
   ```

## 📖 How it Works
The program reads a sequence of DNA and for each STR, it computes the maximum number of times the STR repeats consecutively. It then compares these counts against a database of individuals to find a perfect match.

---
*Developed as part of Harvard's CS50x.*
