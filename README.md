# 🤖 Agentic Market Research Report Generator

This project simulates an **AI Agent Workflow** to generate structured market research reports in Markdown format.

### 🧠 How It Works

This system simulates 3 agents working together:

- **Agent 1: Content Fetcher**  
  Simulates gathering market data on a user-specified topic.

- **Agent 2: Summarizer**  
  Uses HuggingFace Transformers (BART model) to generate an executive summary.

- **Agent 3: Report Compiler**  
  Compiles both the summary and detailed content into a Markdown `.md` file.

---

### 📌 Features

- Automated report generation for any topic  
- Executive summary using BART (`facebook/bart-large-cnn`)  
- Structured Markdown output for easy export  
- Modular agent-based simulation  
- Ready to be extended with real APIs or tools like LangChain agents, web scraping, etc.

---
Results
![image](https://github.com/user-attachments/assets/b8262542-08f7-43c7-aab6-b7c558fced33)
![image](https://github.com/user-attachments/assets/fe12011c-c98f-42a4-903d-5b29fb38f62f)


TechStack
---
| Library                   | Purpose                              |
| ------------------------- | ------------------------------------ |
| `langchain`               | Agent framework (planned/optional)   |
| `transformers`            | Pretrained summarization model       |
| `sentence-transformers`   | Semantic tools (optional/expandable) |
| `pymupdf`                 | PDF handling (optional for export)   |
| `markdown`                | Markdown rendering (optional)        |
| `facebook/bart-large-cnn` | HuggingFace model for summarization  |


📬 Author
Developed by Syeda Zuberiya
