Creddost Loan Advisor AI Chatbot 🦉💰

A professional, single-file AI chatbot designed to act as a Senior Financial Consultant for the Indian market. Built with vanilla JavaScript and Tailwind CSS, it leverages the Google Gemini API to provide strategic, context-aware advice on loans, CIBIL scores, and financial planning.

🚀 Features

Comprehensive Loan Knowledge: Expert advice on Home, Personal, Auto, Gold, Education, and Business/MSME loans.

Strategic Consulting: Goes beyond simple FAQs to offer strategy (e.g., "How to improve eligibility," "Floating vs. Fixed rates," "Part-payment benefits").

Indian Market Context: Tailored logic for Indian financial regulations (RBI guidelines, Section 80C/24b tax benefits, Repo Rates).

Professional Persona: Maintains a "Senior Consultant" tone—empathic, authoritative, and helpful.

Zero-Config UI: Beautiful, responsive interface built with Tailwind CSS (via CDN)—no build steps required.

Robust Error Handling: Includes exponential backoff for API reliability during high traffic.

🛠️ Tech Stack

Frontend: HTML5, Tailwind CSS (CDN)

Logic: Vanilla JavaScript (ES6+)

AI Backend: Google Gemini API (gemini-2.5-flash-preview)

📂 File Structure

/
├── loan_advisor_chatbot.html    # The complete application (UI + Logic)
├── WhatsApp Image...jpg         # Your logo file (ensure this matches the HTML source)
└── README.md                    # This documentation


⚡ Quick Start Guide

1. Get an API Key

You need a Google Gemini API key to power the chatbot.

Visit Google AI Studio.

Create a new project and generate an API key.

2. Configure the Code

Download or clone this repository.

Open loan_advisor_chatbot.html in any code editor (VS Code, Notepad++, etc.).

Find the script section at the bottom (around line 125).

3. Setup the Logo

Ensure your logo image file is named exactly WhatsApp Image 2025-10-18 at 23.37.11_210f634b.jpg and is placed in the same folder as the HTML file.

Alternatively, update the src attribute in the HTML <header> to point to your own logo file.

4. Run It

Simply double-click loan_advisor_chatbot.html to open it in your web browser. No server or installation is required!

🧠 How to Customize the "Brain"

The chatbot's personality and knowledge come from the systemPrompt variable in the JavaScript code.

To add new loan types or change the behavior:

Search for const systemPrompt = in the file.

Edit the text inside the backticks (     ).

Tip: You can add specific details like your company's actual interest rates or contact details here.

Example Modification:

const systemPrompt = `...
**7. SPECIAL OFFER:**
* **Creddost Festive Home Loan:** Flat 8.35% for CIBIL > 800. Valid till Dec 31st.
...`;


🤝 Integration

To use this on platforms like Framer, Webflow, or Hercules:

Copy the entire content of loan_advisor_chatbot.html.

Add an "Embed Code" or "Custom Code" block to your site.

Paste the code.

Note: Ensure your API key is restricted to your website's domain in the Google Cloud Console to prevent unauthorized use.

📄 License

This project is open-source and available for personal or commercial use


