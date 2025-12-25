Invoice Analyzer (n8n + Gemini + Lovable)

An automated tool that processes invoice images and manual data using AI, prevents duplicates, add invoice ID, and provides analytics for a web frontend into monthly piechart.

Features
- AI Extraction: Uses Gemini AI to analyze images and return structured JSON.
- Smart Logic: Code node checks for duplicates and auto-assigns Invoice IDs.
- Web-Ready: Designed to connect to Lovable via Webhooks.
- Analytics: Outputs category data specifically for pie chart rendering.

Requierements
1. n8n version: 1.123.5-exp.0 (Cloud)
2. Credentials: GDrive OAuth2 or Google Sheets and Gemini AI
3. External Assets: create Google Sheet file with this header:
   `invoice id`, `purchase date`, `store name`, `amount`, `category`, `subcategory`, `items`, `note`

Setup
1. Import: `invoice_analyzer.json` into n8n.
2. Webhook: Go to Lovable app build the web app, copy the Production Webhook URL, set to 'Post', change Sheet ID to yours, check on respond webhook nodes, make it receive chart data according to it, send action: submit (for submitted image or manual input) and action: analyze (for cart data)
3. JSON Schema: Ensure the Gemini node is set to "JSON" format to ensure the web app can parse the results, or just put Code node after AI Agent node.


Author
Created and Developed by Cana Wedel

Github: @canawedel9
A creative and development oriented automating process using AI and n8n


License
- This project is licensed under **CC BY-NC 4.0**. 
- You are free to use it for personal projects, but **commercial redistribution or selling this workflow is prohibited.**