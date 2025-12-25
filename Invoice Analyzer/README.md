Invoice Analyzer

Description
Analyzed invoice image or manual input into sheets and generate monthly piechart after.

Requeirements
n8n version: 1.123.5-exp.0 (Cloud)
Credentials: GDrive OAuth2 or Google Sheets and Gemini AI
External Assets: need Google Sheet file with header ("Invoice ID", "Purchase Date", "Store Name", "Amount", "Type", "Category", "Subcategory", "Items", "Note")

How to Use
1. Import 'Invoice Analyzer.json'
2. Connect API Key/configuration
3. Build your web, set to 'Post', check on respond webhook nodes, make it receive chart data according to it, send action: submit (for submitted image or manual input) and action: analyze (for cart data)