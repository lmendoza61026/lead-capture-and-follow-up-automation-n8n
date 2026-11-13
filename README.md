# Lead Capture and Automated Follow-Up System

## Overview

A sample n8n automation that captures new leads, validates their details, records them in Google Sheets, and notifies a business so it can follow up promptly.

## Business Problem

Businesses can lose potential customers when inquiries are recorded manually or follow-ups are delayed.

## Solution

This workflow automates lead collection, data validation, spreadsheet logging, and business notifications.

## Workflow

1. Receive a new lead through a form or webhook.
2. Validate required information.
3. Save the lead to Google Sheets.
4. Send a business notification.
5. AI Agent draft a follow up email for every leads.

## Tools and Technologies

- n8n
- Google Sheets
- Webhook or form trigger
- Email or notification integration
- AI model integration

## Results and Testing

Tested with fictional sample leads.

Document the actual test results here, including successful executions, missing-field handling, and any limitations. Do not claim time savings or business results that have not been measured.

## Screenshots

- Workflow overview: `screenshots/workflow-overview.png`
- Successful execution: `screenshots/successful-execution.png`

## Limitations

- Requires properly configured integrations and credentials.
- The workflow is a demonstration, not a production deployment.
- AI-generated content, if enabled, should be reviewed before being sent to customers.

## Security

No real customer data, passwords, or API secrets are included in this repository.

## Author

L. Mendoza

AI Automation Specialist | n8n Workflow Builder


