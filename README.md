# GPT File Manager 📄🤖
Description
This Python script automatically renames PDF files based on the content of the first few words in each document. It uses the OpenAI ChatGPT API to infer the title of a scientific article, making file organization easier and more meaningful—especially for researchers, students, and professionals working with large collections of academic PDFs.

# Purpose
📄 Extract the beginning of a PDF’s first page.

🧠 Use GPT-3.5-Turbo to infer the paper’s title based on the first 400 characters.

📝 Rename each PDF with the generated title, removing punctuation and special characters.

# Features
🔁 Batch renaming of all PDFs in a specified folder.

🧠 AI-powered title generation via OpenAI’s ChatGPT.

📚 Cleaner and more informative file names.

🧹 Automatic cleanup of special characters.

⚠️ Suppresses warnings from incompatible or malformed PDF files.

# Requirements
Python 3.x

# Libraries:

openai

PyPDF2

re

os
