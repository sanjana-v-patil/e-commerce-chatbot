# E-Commerce Data Chatbot (Gradio + Gemini / OpenRouter)

This project is a **Gradio-based AI app** that enables users to **chat with their e-commerce dataset** in natural language.  
It integrates **LLMs (Gemini via Google AI Studio / OpenRouter)** with **LangChain** to interpret queries, analyze multiple relational tables (customers, products, orders, etc.), and respond intelligently with insights.

---

##  How to Run

#1 Clone the repository
```bash
git clone https://github.com/<your-username>/ecommerce-data-chatbot.git
cd ecommerce-data-chatbot


2️ Install Dependencies
pip install -r requirements.txt  

3️ Add Your API Key(s) :Create a .env file in the root folder and add your Gemini or OpenRouter key (⚠️ Do not commit it to GitHub):
GOOGLE_API_KEY="your_gemini_api_key_here"
# or
OPENROUTER_API_KEY="your_openrouter_key_here"

4️ Run the App
Once running, open the Gradio interface link (usually http://127.0.0.1:7860/) and start chatting with your data!
 python app.py
