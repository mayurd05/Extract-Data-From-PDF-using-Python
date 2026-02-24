# PDF Data Extraction – Aahar 2025 Fair Guide

## Overview
This project extracts structured information from the PDF file  
**“Aahar 2025 Fair Guide.pdf”** using Python.

The goal is to demonstrate PDF text extraction, basic parsing using
regular expressions, and exporting the extracted data into an Excel file.

---

## Data Extraction Objective
The script attempts to extract the following fields from the PDF:

- Company Name  
- Address  
- Contact Person  
- Tel / Mobile  
- Email  

---

## Tools & Libraries Used
- Python 3.x
- pdfplumber – for extracting text from PDF files
- pandas – for data manipulation and tabular representation
- openpyxl – for writing Excel (.xlsx) files
- re (regex) – for pattern-based text extraction

---

## Project Files
- `extract_pdf_basic.py` – Python script for PDF data extraction  
- `Aahar 2025 Fair Guide.pdf` – Input PDF file  
- `Aahar_2025_Extracted_Data.xlsx` – Generated Excel output  
- `README.md` – Project documentation  

---

## How to Run the Script

### 1. Install Required Libraries
```bash
pip install pdfplumber pandas openpyxl
