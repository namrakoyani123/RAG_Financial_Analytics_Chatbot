# 💰 RAG Financial Analytics Chatbot

An intelligent **Personal Finance Assistant** powered by **Retrieval-Augmented Generation (RAG)**.
This chatbot helps users analyze financial data, track assets, read finance news, and interact with documents using AI.

---

## 🚀 Features

* 💬 **AI Chat Assistant**
  Powered by OpenAI with Groq fallback for fast and reliable responses

* 📄 **PDF Upload & Q&A (RAG)**
  Upload financial documents and ask questions using contextual retrieval

* 📰 **Real-Time Finance News**
  Integrated with NewsAPI and Tavily for latest updates

* 📈 **Asset Tracking**
  Track stocks, forex, and cryptocurrency data

* 🛠️ **Smart Budgeting Tools**
  Get recommendations using the **50/30/20 rule**

* ⚡ **Fallback System**
  Ensures uninterrupted service using multiple APIs

---

## 🧠 Tech Stack

* **Frontend:** Streamlit
* **Backend:** Python
* **LLMs:** OpenAI, Groq
* **RAG Pipeline:** LangChain / Vector Store
* **APIs:** NewsAPI, Tavily, Alpha Vantage

---

## 📂 Project Structure

```
RAG_Financial_Analytics_Chatbot/
│── app.py
│── requirements.txt
│── Procfile
│── utils/
│── data/
│── README.md
```

---

## ⚙️ Environment Variables

Create a `.env` file or set variables in your deployment platform:

```
OPENAI_API_KEY=your_openai_key
GROQ_API_KEY=your_groq_key
TAVILY_API_KEY=your_tavily_key
NEWS_API_KEY=your_newsapi_key
AV_API_KEY=your_alpha_vantage_key
```

---

## 💻 Local Setup

```bash
# Clone the repository
git clone https://github.com/namrakoyani123/RAG_Financial_Analytics_Chatbot.git

# Navigate into the folder
cd RAG_Financial_Analytics_Chatbot

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

---

## 🌐 Deployment (Render)

1. Push your project to GitHub
2. Go to Render → New Web Service
3. Connect your repository
4. Set:

```
Build Command:
pip install -r requirements.txt

Start Command:
streamlit run app.py --server.port=$PORT --server.address=0.0.0.0 --server.headless=true
```

5. Add environment variables
6. Deploy 🚀

---

## 🛠️ Future Improvements

* 📊 Advanced financial analytics dashboard
* 🤖 Voice-based interaction
* 📱 Mobile app version
* 📉 AI-powered investment suggestions

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Namra_Koyani**
B.Tech Student | Developer | AI Enthusiast

---

⭐ If you like this project, don’t forget to star the repository!
