# ✍️ AI Document Drafter (Notebook Version)

This project is a simple AI-powered document editor built inside a Google Colab Notebook.
It allows you to **write**, **edit**, and **save** documents using natural language.

The agent uses:
- **LLaMA 3.1** model from **Groq**
- **LangChain** for conversation and tool management
- **LangGraph** for workflow control

---

## 🚀 Features

| Feature | Description |
|--------|-------------|
| Write | Generate new text into the document |
| Update | Replace the document content with a new version |
| Save | Save the document as a `.txt` file |
| Interactive | Works directly inside Google Colab |

---

## ✅ Usage

In your notebook, after running all cells, use:

```python
chat("Write an introduction about Artificial Intelligence.")
