# Smart Invoice Processing System

## Project Overview

The Smart Invoice Processing System is an automated invoice processing solution built using Microsoft Azure services. The solution validates uploaded invoices, extracts invoice information using Azure AI Document Intelligence, generates JSON outputs, stores processed data in Azure SQL Database, and provides reporting through Power BI.

## Technologies Used

- Azure Logic Apps
- Azure Blob Storage
- Azure AI Document Intelligence
- Azure SQL Database
- Azure SQL Server
- Power BI
- Azure Monitor

## Workflow

1. Upload invoice to Input Invoices container.
2. Logic App trigger detects the file.
3. File format validation is performed.
4. Non-PDF files are moved to Rejected Invoices.
5. PDF files are moved to Processed Invoices.
6. Azure AI Document Intelligence extracts invoice data.
7. JSON output is generated.
8. JSON file is stored in Output Invoices.
9. Invoice data is inserted into Azure SQL Database.
10. Power BI generates reports and dashboards.

## Key Features

- Automated Invoice Processing
- AI-Based Data Extraction
- JSON Output Generation
- Azure SQL Database Integration
- Power BI Reporting
- Monitoring and Run History Tracking

## Documentation

Detailed project documentation is available in the project repository.
