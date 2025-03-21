# Email Attachment Automation

## Important Notice
**WARNING:** Any sample files or data included in this repository are **FICTIONAL** and created for demonstration purposes only. All real client data and credentials have been removed to preserve privacy.

## About the Project
This project automates the process of retrieving and processing email attachments. The automation logs into an email account, downloads attachments to a designated folder, then processes files containing barcodes by extracting the barcode data and recording it in a spreadsheet along with the filename, due date, and amount.

### Features
- Automatic login to email account
- Download of email attachments to a specified folder
- Barcode recognition and data extraction from PDF files
- Automated recording of barcode data in a spreadsheet, including:
  - Barcode number
  - Filename
  - Due date
  - Amount
- Simple GUI interface for configuration

## Requirements
- Python 3.6 or higher
- Libraries:
  - PySimpleGUI
  - email libraries
  - barcode recognition libraries
  - spreadsheet manipulation libraries

## File Structure
- `app.py` - Main automation script with GUI interface
- `Pasta Anexos/` - Folder for downloaded attachments
- `Pasta Planilhas/` - Folder for output spreadsheets

## How to Use
1. Run the script:
```bash
python app.py
```
2. In the GUI window:

Enter your email address
Enter your password
Select the folder for attachments
Select the folder for the output spreadsheet


Click "Save" to start the process
