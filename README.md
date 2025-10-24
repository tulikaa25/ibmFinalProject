# 🧠 Blog Generator using LLaMA 2 + Streamlit

This project is a **Streamlit web application** that automatically generates blog posts using the **LLaMA 2 large language model** through the **LangChain** framework.

---

## 🚀 What It Does

The app allows users to:
- Enter a **topic** for the blog post  
- Specify the **desired word count**  
- Choose a **writing style or audience** (e.g., Researchers, Data Scientists, or Common People)

Once the user clicks **Generate**, the app:
1. Passes the inputs into a **prompt template**  
2. Uses **LangChain** to format the prompt  
3. Sends it to a locally running **LLaMA 2 model** (via `CTransformers`) to generate coherent and context-aware text  
4. Displays the generated blog post directly in the Streamlit interface  

---

## 🧩 Tech Stack

- **Python** 
- **Streamlit** – for the interactive web UI  
- **LangChain** – for prompt management and LLM orchestration  
- **CTransformers** – for loading and running the LLaMA 2 model locally  

---

## 💡 Key Features

- Interactive and user-friendly web interface  
- Local **LLaMA 2** model integration (no external API needed)  
- Dynamic prompt-based blog generation  
- Adjustable output style and word length  

---

## 📘 Use Cases

- Quickly generate blog drafts for different audiences  
- Learn how to integrate **open-source LLMs** into web apps  
- Experiment with **prompt engineering** using LangChain  

---

