# AI Agent for Restaurant (n8n)

An n8n workflow that receives chat messages and routes them to:
- Google Gemini Chat Model (intent detection)
- Simple Memory (Google Sheets)
- Inventory, FAQ, Orders (Google Sheets)

## Features
- Automates customer chat handling
- Checks inventory and returns answers from FAQ
- Appends orders automatically to a Google Sheet
- Built with n8n, Google Gemini, Google Sheets

## How to use
1. Import the n8n workflow JSON (attach your exported n8n workflow file).
2. Configure credentials:
   - Google OAuth (for Gemini & Sheets)
   - n8n credentials for GitHub / LinkedIn if using automation
3. Update the Google Sheet IDs in the Get Inventory / Get FAQ / Get Order nodes.

## Screenshot
![n8n workflow](workflow.png
)



## Author
Sankalp Satpute
