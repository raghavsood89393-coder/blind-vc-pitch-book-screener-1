
# Blind VC Pitch Book Screener

## Project Overview
The Blind VC Pitch Book Screener is an automated n8n workflow designed to reduce founder charisma, university pedigree, and presentation-design bias during venture capital screening.

It extracts financial metrics from startup pitch books, removes selected identity-related information and hype language, calculates a financial score, and generates standardized reports.

## Problem Statement
Traditional venture capital screening can be influenced by founder reputation, educational background, charisma, and presentation quality rather than actual business performance.

## Workflow Process
1. Founder uploads a PDF or TXT pitch book.
2. n8n extracts the financial metrics.
3. The workflow checks whether required information is available.
4. Selected identity details and hype language are redacted.
5. The startup receives a score based on financial performance.
6. HTML and CSV reports are generated.

## Technologies Used
- n8n
- JavaScript
- PDF/TXT text extraction
- Regex-based data extraction
- HTML
- CSV

## Project Files
- `blind_vc_pitchbook_screener.json` – Importable n8n workflow.
- `Blind_VC_Pitch_Book_Screener_Themed.pptx` – Project presentation.

## How to Import
1. Open your n8n instance.
2. Go to Workflows.
3. Select Import from File.
4. Upload the JSON workflow.
5. Save and test the workflow with a sample pitch book.

## Expected Outputs
- Standardized blind HTML scoresheet.
- Structured CSV report.

## Important Note
The workflow uses rule-based financial scoring and selected text redaction. It does not perform complete image, logo, or graphic removal from uploaded pitch books.
