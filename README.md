# HTML/JSON Parser and DOCX Table Generator

This project was created to solve a real-world problem: **documenting IT security certifications in a structured format**. The goal was to automate the process of extracting and formatting information about IT security certifications into a Word document, saving countless hours of manual effort.

---

## Why This Script Was Created

I had an assignment to create a comprehensive table for **every IT security certification**. Given the massive number of certifications (I found a repo with **481 certifications**), manually creating this table was not practical. To tackle this challenge, I wrote a script that:

1. **Extracts certification information** from an HTML file or JSON data.
2. **Generates a `.docx` file** with a formatted table for **every IT security certification**.

This automation made it possible to document hundreds of certifications efficiently and accurately.

---

## How It Works

The script uses:
- **HTML parsing** with `BeautifulSoup` to extract certification names, descriptions, and URLs from an HTML file.
- **JSON parsing** to handle structured certification data with dynamic headers.
- **Word document generation** using `python-docx` to create tables with the extracted data.

---

## Features

1. **Automated Extraction**: Extracts data directly from an HTML file or JSON structure, eliminating manual copy-pasting.
2. **Dynamic Table Generation**: Creates a `.docx` table with dynamically generated headers based on the data structure.
3. **Comprehensive Documentation**: Produces a complete table with every IT security certification, including descriptions and URLs.

---

## Requirements

Install the required Python libraries:
```bash
pip install beautifulsoup4 python-docx
