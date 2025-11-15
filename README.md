# UiPath – Invoice Processing Automation Workflow

This repository contains a **UiPath workflow** designed for **Invoice Processing Automation**. It utilizes various activities such as **Document Understanding**, **Excel Integration**, and **PDF Activities** to process and extract data from invoices automatically.

---

## Project Overview
- **Built using**: **UiPath Studio (Modern Design Experience)**
- **Workflow**: Automates invoice processing by extracting key data points from invoices, such as amounts, dates, vendor names, and more.
- **Technologies Used**:
  - **Document Understanding**: For processing structured and unstructured data.
  - **Excel Activities**: To handle and manipulate data.
  - **PDF Activities**: To extract data from invoice PDFs.
  - **Mail Activities**: For email-based workflows (if needed).
  - **UI Automation**: To interact with web or desktop applications (if required).

---

## Project Files
- `Main.xaml` → The main automation workflow  
- `project.json` → UiPath project configuration file  
- Dependencies → Listed in `project.json`

---

## Workflow Logic

### Document Understanding
- **Invoice Data Extraction**: Utilizes the **UiPath.DocumentUnderstanding.Activities** package to extract data from scanned or image-based invoices.  
- Processed data is stored and utilized for further automation steps.

### Excel Automation
- **Data Handling**: Reads, writes, and manipulates invoice data from Excel sheets. Perfect for processing multiple invoices at once.

### PDF Automation
- Extracts text, images, and other elements from PDF invoices using **UiPath.PDF.Activities**.

### Email Integration
- Automates email-based invoice processing with **UiPath.Mail.Activities**.

---

## Example Output
The workflow extracts the following details from invoices:

- **Invoice Number**: INV-001234
- **Vendor Name**: ABC Corp.
- **Amount**: $1,200.00
- **Invoice Date**: 2025-11-15
- **Due Date**: 2025-12-15

---

## Screenshots


---

## Running the Workflow
1. **Install UiPath Studio** and ensure all the required dependencies are installed.
2. Open **Main.xaml** in UiPath Studio.
3. If necessary, update any **API keys**, **file paths**, or **email configurations**.
4. Run the workflow to automate invoice processing.
```

