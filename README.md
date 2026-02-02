# Chatbot Project 🤖

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/vimalkarkarpatel12/chatbot-project/blob/main/Chatbot.ipynb)

A smart chatbot built using **Python**, **Hugging Face Transformers**, and **LLaMA 2**, with a **QA memory system** and an interactive **Gradio web interface**.

The chatbot first searches a local dataset for answers and falls back to an LLM when the answer is not found.

---

## 🚀 Features

- 🤖 LLaMA-2 powered chatbot  
- 📂 CSV-based question–answer memory  
- 🧠 Automatically learns new Q&A pairs  
- 🌐 Interactive Gradio UI  
- ⚡ Runs on Google Colab  
- 🔐 Secure Hugging Face authentication  

---

## 🛠️ Technologies Used

- Python  
- Hugging Face Transformers  
- LLaMA 2 (`NousResearch/Llama-2-7b-chat-hf`)  
- PyTorch  
- Pandas  
- Gradio  
- Google Colab  

---

## ▶️ How to Run (Recommended – Colab)

1. Click **Open in Colab**
2. Add your Hugging Face token securely
3. Run all cells
4. Open the Gradio public URL


## ▶️ Run Locally

```bash
git clone https://github.com/vimalkarkarpatel12/chatbot-project.git
cd chatbot-project
pip install -r requirements.txt
jupyter notebook Chatbot.ipynb



