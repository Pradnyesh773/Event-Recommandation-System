# **Event Recommender System with AI Chatbot**  

## 📌 **Project Description**  
This project integrates an **Event Recommender System** with an **AI Chatbot** to provide a seamless event discovery and interactive assistance experience.  

- 🎯 **Event Recommender System** – Suggests events based on user preferences and similarities.  
- 🤖 **AI Chatbot (Ollama AI)** – Assists users in event queries using natural language processing.  

---

## 🚀 **Features**  

✔️ **Personalized Event Recommendations** – Uses machine learning algorithms for accurate suggestions.  
✔️ **AI Chatbot with Ollama AI** – Chatbot answers queries and provides event recommendations.  
✔️ **Location & Category-Based Suggestions** – Users can filter events based on preferences.  
✔️ **Interactive UI** – Built with **Flask** (for event system) and **Streamlit** (for chatbot).  
✔️ **Event Images & Ratings** – Displays event details, including images, ratings, and attendee count.  
✔️ **Real-time Chat Responses** – The chatbot streams responses dynamically.  

---

## 🛠️ **Installation & Setup**  

### 📌 **1. Clone the Repository**  
```bash
git clone https://github.com/yourusername/Event-recommender-system-with-chatbot.git
```

### 📌 **2. Run the AI Chatbot (Streamlit + Ollama AI)**  
1. Open a **terminal** and navigate to the chatbot directory:  
   ```bash
   cd "C:\Users\pradn\OneDrive\Desktop\Event\Event-recommender-system-master\streamlit_chatbot-main"
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Start the chatbot:  
   ```bash
   streamlit run chatbot.py
   ```

### 📌 **3. Run the Event Recommender System (Flask + Machine Learning)**  
1. Open a **new terminal** and navigate to the event recommender system directory:  
   ```bash
   cd "C:\Users\pradn\OneDrive\Desktop\Event\Event-recommender-system-master\Event-recommender-system-master"
   ```
2. Install dependencies (if not already installed):  
   ```bash
   pip install -r requirements.txt
   ```
3. Start the event recommender system:  
   ```bash
   python app.py
   ```

---

## 🔧 **Technologies Used**  

### **Event Recommender System (Flask + Machine Learning)**  
🔹 **Python** – Core programming language  
🔹 **Flask** – Backend framework for the recommender system  
🔹 **NumPy & Pandas** – Data processing and manipulation  
🔹 **Machine Learning (Scikit-Learn, TensorFlow, etc.)** – Event recommendation engine  
🔹 **Pickle** – For loading and using pre-trained models  
🔹 **HTML/CSS (Jinja2)** – Web templates for displaying events  

### **Chatbot (Streamlit + Ollama AI)**  
🔹 **Python** – Core programming language  
🔹 **Streamlit** – UI framework for chatbot interaction  
🔹 **Ollama AI** – NLP model for chatbot responses  
🔹 **Chat Streaming** – Real-time dynamic message streaming  
🔹 **Session State** – Maintains message history for contextual conversations  

---

## 🎯 **Usage**  

1. **Chatbot Interaction:**  
   - Open the chatbot UI in your browser.  
   - Ask event-related queries, and the chatbot will provide relevant responses.  

2. **Event Recommender System:**  
   - Browse or search for events by name, category, or tags.  
   - Get top personalized event recommendations.  

3. **Integrated Experience:**  
   - Use the chatbot to ask for event suggestions and get instant results.  
   - The event recommender system and chatbot work together for a better user experience.  

---

## 🔮 **Future Enhancements**  
🚀 Improve chatbot intelligence with GPT-based models  
🚀 Add user authentication for personalized recommendations  
🚀 Enhance UI with React or Vue.js  
🚀 Implement collaborative filtering for better recommendations  
🚀 Deploy the system on a cloud platform  

---

## 👥 **Contributors**  
👤 **Pradnyesh Anil Patil** – Final Year CS Student with Honors in Cybersecurity  
📧 *Email:* your.email@example.com  
🔗 *LinkedIn:* [linkedin.com/in/pradnyeshpatil](https://linkedin.com)  

---

## 📜 **License**  
This project is licensed under the **MIT License**.  
