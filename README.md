# Import Data Using Transform Maps (Spreadsheet)

## Project Overview

This project demonstrates how employee data can be imported into ServiceNow using Import Sets and Transform Maps.

The employee information is initially maintained in a spreadsheet and imported into ServiceNow. The data is stored temporarily in an Import Set Table and then transformed into the target Employee table.

## Technologies Used

- ServiceNow
- Import Sets
- Import Set Table
- Transform Maps
- Coalesce
- ServiceNow Reports
- ServiceNow Dashboards
- Spreadsheet

## Employee Data Fields

The spreadsheet contains:

- Employee ID
- Name
- Email
- Department
- Location

## Project Workflow

1. Create the employee spreadsheet.
2. Create the required table in ServiceNow.
3. Create the Import Set Table.
4. Import spreadsheet data into ServiceNow.
5. Create the Transform Map.
6. Configure field mappings.
7. Configure Employee ID as the Coalesce field.
8. Transform and validate the imported data.
9. Generate reports.
10. Add reports to a ServiceNow dashboard.

## Key Features

### Import Set
Employee data from the spreadsheet is imported into ServiceNow using an Import Set.

### Transform Map
The Transform Map maps the imported spreadsheet fields to the corresponding target table fields.

### Coalesce
Employee ID is used as the unique identifier to prevent duplicate records and update existing employee records.

### Data Validation
The transformed records are validated to ensure that the employee information is correctly inserted into the target table.

### Reports and Dashboard
Reports are created from the employee data and added to a ServiceNow dashboard for visualization.

## Screenshots

The repository contains screenshots demonstrating:

- Spreadsheet creation
- Table creation
- Import Set data
- Data loading
- Transform Map configuration
- Field mapping
- Data validation
- Coalesce configuration
- Reports
- Dashboard

## Project Outcome

The project successfully demonstrates the complete process of importing spreadsheet-based employee data into ServiceNow, transforming the data using Transform Maps, avoiding duplicate records using Coalesce, validating the imported data, and presenting the information through reports and dashboards.

## Author

Sharmila P# import-data-and-transform-map-using-spreadsheet
naan mudhavan project development
