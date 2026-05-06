# 🧠 Veritas – AI Study Assistant + Fact-Checker

An intelligent n8n workflow that helps students generate **reliable study material** from lecture notes or topics — with built-in **AI fact-checking** before content generation.



## 🚀 Features

- 📥 Input via form (topic or lecture notes)
- 🔍 AI-powered fact-checking using web search
- 📊 Confidence scoring + claim verification
- ⚠️ Flags misleading or false information
- 🧠 Generates:
  - Flashcards
  - Quiz (MCQs)
  - Structured Summary
- 📧 Sends results as a beautifully formatted email
- 📄 Logs results to Google Sheets



## 🧩 Workflow Overview

1. User submits topic/notes via form
2. AI agent extracts and fact-checks key claims
3. System evaluates:
   - TRUE / FALSE / MISLEADING / UNVERIFIED
4. Based on user choice, generates:
   - Flashcards
   - Quiz
   - Summary
   - Or all combined
5. Final output is:
   - Sent via email
   - Saved to Google Sheets



## 🛠️ Tech Stack

- n8n (workflow automation)
- Groq (LLM inference)
- SerpAPI (web search for fact-checking)
- Google Sheets API
- Gmail API



## 📸 Example Use Case

> Input: “Neural Networks lecture notes”

Output:
- Verified summary
- Flashcards for key concepts
- Quiz questions
- Fact-check report with confidence score


## ⚙️ Setup Instructions

1. Import the workflow JSON into n8n
2. Configure credentials:
   - Groq API
   - SerpAPI
   - Google Sheets
   - Gmail
3. Activate the workflow
4. Use the form webhook to submit data


## 👨‍💻 Author

Mohammad
