# 💼 LinkedIn Post Generator AI

A **Streamlit-based AI tool** that generates creative LinkedIn posts automatically using **Llama 3.3**, **LangChain**, and **Groq LLM**.  

This project helps you quickly create posts in different tones, categories, hashtags, and emoji styles — perfect for professional or personal branding on LinkedIn.

---

## ✨ Features

- Generate **short, long, or LinkedIn-style posts**.  
- Choose post **category**: Marketing, Tech, Career, AI, or Custom.  
- Choose **tone**: Professional, Motivational, Friendly, Bold, Funny.  
- Generates **hashtags** automatically.  
- **Emoji captions** included.  
- **Streamlit UI** for easy interaction.  

---

## 🚀 How to Run Locally

1️⃣ Clone the repository
```bash
git clone https://github.com/Zeenatattar/LinkedIn-Post-Generator.git
cd LinkedIn-Post-Generator

2️⃣ Install required packages
pip install streamlit langchain-groq python-dotenv

3️⃣ Add your Groq API key
Create a .env file in the root folder:

GROQ_API_KEY=your_groq_api_key_here
Important: Do NOT upload your .env file to GitHub.

4️⃣ Run the Streamlit app
streamlit run main.py

📂 Folder Structure
LinkedIn_Post_Generator/
│
├── main.py           # Streamlit UI
├── post_generator.py # AI logic
├── llm_helper.py     # LLM setup
├── .env              # Your API key (not uploaded)
├── requirements.txt  # Python dependencies
└── README.md         # Project documentation

🎨 Future Improvements
Multi-language LinkedIn posts
Add post scheduling feature
Save generated posts as PDF or Word document
Add tone slider for custom creativity

💻 Technologies Used
Python 3.11+
Streamlit (UI)
LangChain (AI orchestration)
Groq LLM (Language model)
dotenv (Environment variables)
