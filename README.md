# invoice-management-system-by-n8n
## A fully automated invoice processing system using n8n – a no-code/low-code workflow automation tool.
### Here's what it does:
 \n📥 Monitors a specific Google Drive folder for new invoice PDFs
 \n📄 Downloads and reads the PDF contents
 \n🧠 Uses Google Gemini AI (via LangChain) to extract key info like:
 \n🔹 Invoice Number
 \n🔹 Client Name, Email, Address, Phone
 \n🔹 Total Amount
 \n🔹 Invoice Date & Due Date
 \n📊 Logs the extracted data into a Google Sheet (our invoice database)
 \n📧 Automatically sends an email notification to the finance team with all invoice details
\nThis saves hours of manual work each week and ensures accurate, real-time data capture! 🔁✨
\nHere’s a sneak peek of the flow:
 \n🔗 Google Sheet: Invoice DB
### 💡Tech Stack:
  \nn8n (open-source automation)
  \nGoogle Workspace APIs (Drive, Sheets, Gmail)
  \nLangChain + Google Gemini for intelligent data extraction
