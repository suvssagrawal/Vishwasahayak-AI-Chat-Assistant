#  Vishwasahayak – AI Chat Assistant

Vishwasahayak is a **futuristic AI desktop assistant** built with **Tkinter (using ttkbootstrap for modern UI)** and powered by the **Groq API**.  
It supports **chatting with AI**, **attaching PDF/Word/Excel files as context**, and even **exporting responses to Word or Excel files**.

---

## Features

- Powered by Groq API for lightning-fast AI responses.  
- File Upload Support: Attach PDF, Word (`.docx`), or Excel (`.xlsx`, `.xls`) files to provide context for AI answers.  
- Smart Context Handling**: Extracts and summarizes content, while automatically truncating long files.  
- Export Responses: Save AI responses as Word (`.docx`) or Excel (`.xlsx`) files directly.  
- Modern UI with splash screen, file context badges, styled chat bubbles, and typewriter effect.  

---

##  Installation

1. Clone this repository or download the script:
   ```bash
   git clone https://github.com/suvssagrawal/vishwasahayak.git
   cd vishwasahayak
  ## 🔑 API Key Setup

This project requires a **Groq API key**.

1. Get your free API key from [Groq](https://groq.com/).
2. Set it as an environment variable on your system:

   **Linux/macOS (bash/zsh):**
   ```bash
   export GROQ_API_KEY="your_api_key_here"
