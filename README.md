# 🧠 Blog Generator using Groq LLaMA 3 + Streamlit

This project is a **Streamlit web application** that automatically generates blog posts using **Groq’s LLaMA 3 API** through the **LangChain** framework.Groq hardware is optimized for transformer models, so responses are generated quickly compared to local CPU/GPU inference.

---

## 🚀 What It Does

The app allows users to:
- Enter a **topic** for the blog post  
- Specify the **desired word count**  
- Choose a **writing style or audience** (e.g., Researchers, Data Scientists, or Common People)

Once the user clicks **Generate**, the app:
1. Passes the inputs into a **prompt template**  
2. Uses **LangChain** to format the prompt  
3. Sends it to **LLaMA 3 model** (via `Groq`) to generate coherent and context-aware text  
4. Displays the generated blog post directly in the Streamlit interface  

---

## 🧩 Tech Stack

- **Python** 
- **Streamlit** – for the interactive web UI  
- **LangChain** – for prompt management and LLM orchestration  
- **LangChain-Groq** – Groq API integration for LLaMA 3  

---

## 💡 Key Features

- Interactive and user-friendly web interface
- Cloud-based LLM removes the need for local GPU resources 
- Dynamic prompt-based blog generation  
- Adjustable output style and word length  

---

## 📘 Use Cases

- Quickly generate blog drafts for different audiences  
- Learn how to integrate **open-source LLMs** into web apps  
- Experiment with **prompt engineering** using LangChain  


---

