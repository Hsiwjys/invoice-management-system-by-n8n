# invoice-management-system-by-n8n
## A fully automated invoice processing system using n8n – a no-code/low-code workflow automation tool.
### Here's what it does:
 📥 Monitors a specific Google Drive folder for new invoice PDFs
 📄 Downloads and reads the PDF contents
 🧠 Uses Google Gemini AI (via LangChain) to extract key info like:
 🔹 Invoice Number
 🔹 Client Name, Email, Address, Phone
 🔹 Total Amount
 🔹 Invoice Date & Due Date
 📊 Logs the extracted data into a Google Sheet (our invoice database)
 📧 Automatically sends an email notification to the finance team with all invoice details
This saves hours of manual work each week and ensures accurate, real-time data capture! 🔁✨
Here’s a sneak peek of the flow:
 🔗 Google Sheet: Invoice DB
### 💡Tech Stack:
  n8n (open-source automation)
  Google Workspace APIs (Drive, Sheets, Gmail)
  LangChain + Google Gemini for intelligent data extraction
