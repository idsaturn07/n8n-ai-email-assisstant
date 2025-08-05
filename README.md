# 🤖 AI-Powered Email Assistant – n8n Workflow

This is an intelligent automation workflow built using **n8n**. It combines **OpenAI**, **memory management**, **Google Sheets**, and **Gmail** to provide smart chat responses and context-aware email handling.

---

## 🧠 Workflow Overview

This AI workflow automates responses based on chat messages. It integrates OpenAI for response generation, a memory tool for context, accesses a contact database, and can send emails automatically through Gmail.

---

## 🔧 Nodes Used

| Node                    | Type              | Description                                               |
|-------------------------|-------------------|-----------------------------------------------------------|
| When chat message received | Trigger         | Initiates the workflow upon receiving a chat message      |
| AI Agent                | Core Node         | Processes input using OpenAI, memory, and tools           |
| OpenAI Chat Model       | Integration       | Generates intelligent responses via GPT                   |
| Simple Memory           | Memory Tool       | Stores context for personalized conversation              |
| Contact Database        | Google Sheets     | Reads contact information                                 |
| Send Email              | Gmail API         | Sends follow-up or info-rich emails                       |
| Output                  | Output Node       | Shows final AI-generated output                           |

---

## 📁 File Structure

```plaintext
n8n-ai-email-assistant/
├── assets/
│   └── ScreenshotOfWorkflow.png     # Screenshot of the workflow
│   └── Workflow.json    # Exported n8n workflow
├── README.md                           # Markdown documentation
