# PDF Bill Splitter

PDF Bill Splitter is a C#.NET console application designed to simplify the task of splitting a PDF document containing multiple bills into individual PDF files, and it gives you the flexibility to split them based on account numbers or by using a keyword system for intelligent splitting. This project utilizes the iTextSharp Library to automate the splitting process.

## Features

- **Smart PDF Splitting**: PDF Bill Splitter can intelligently split PDFs based on predefined keywords. These keywords are defined in JSON files, allowing you to customize the splitting criteria. An example of a template for intelligent splitting is provided in the `jsonTypes` folder.

- **Page-by-Page Splitting**: If you prefer a more straightforward approach, you can opt for page-by-page splitting. This mode is perfect for scenarios where bills are not structured by account numbers or keywords.

- **User-Friendly UI**: PDF Bill Splitter comes with a simple and intuitive user interface. Just open the executable file, and the UI will guide you through the process.

## How to Use

1. Download the program as a zip folder & extract it

2. Run the executable file (`.exe`) to open the PDF Bill Splitter.

3. Choose your preferred mode (Cheney PDF Splitting or Default Splitting).

4. Follow the on-screen instructions to select the PDF document you want to split and configure the splitting options.

5. Begin the process. The application will create individual PDF files based on your selected criteria.

## Keyword Templates

To enable intelligent splitting based on keywords, you can define templates in JSON files. Here's an example of a JSON template named "Cheney" located in the `jsonTypes` folder:

```json
{
  "Synonyms": [
    "Total Due",
    "Amount Payable",
    "Balance Due",
    "Outstanding Balance",
    "Payment Due",
    "Amount Due",
    "Payable Amount",
    "Total Amount Payable",
    "Due Amount",
    "Due Balance",
    "Amount Owed",
    "Unpaid Balance",
    "Payment Required",
    "Invoice Total",
    "Invoice Amount",
    "Bill Total",
    "Bill Amount",
    "Account Balance",
    "invoice",
    "due date"
  ]
}
```

You can create and customize your own JSON templates in the `jsonTypes` folder to meet your specific needs.

## Requirements

- [.NET Framework](https://dotnet.microsoft.com/download/dotnet-framework) must be installed on your computer.

## Installation

You can download the latest version of PDF Bill Splitter from the https://github.com/BasedOctavian/PDF-Bill-Splitter. There are no additional installation steps required.
