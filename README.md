🎓 AI Scholarship Finder Chatbot

📌 Overview

This project is an AI-powered Scholarship Finder Chatbot built using Python and Streamlit. It helps students discover scholarships, eligibility criteria, and application guidance using scraped and structured online data. The chatbot collects information from educational and scholarship websites and provides relevant answers based on user queries.

🚀 Features

🌐 Web scraping of scholarship opportunities from trusted sources  

🎓 Scholarship recommendations based on user queries  
💬 Interactive chatbot interface using Streamlit  
⚡ Fast keyword-based matching system  
📚 Organized dataset for easy information retrieval  
🎯 Helps students find local and international scholarships  

🧠 How It Works

1. Data Collection
Scrapes scholarship-related websites  
Extracts key details like eligibility, country, and field  
Stores cleaned information in training_data.txt  

2. Processing
Cleans and splits data into searchable sentences  
Matches user queries with relevant keywords  
Finds most relevant scholarship information  

3. Output
Displays scholarship suggestions in chatbot format  
Provides guidance on eligibility and application process  

📁 Project Structure

AI-Scholarship-Finder-Chatbot/
│
├── app.py                 # Streamlit chatbot interface  
├── web_scraper.py        # Scrapes scholarship data  
├── training_data.txt     # Dataset (scholarship information)  
├── requirements.txt      # Dependencies  
└── README.md             # Project documentation  

⚙️ Installation & Setup

1. Clone the repository
git clone https://github.com/your-username/AI-Scholarship-Finder-Chatbot.git  
cd AI-Scholarship-Finder-Chatbot  

2. Create virtual environment (optional)
python -m venv venv  
venv\Scripts\activate   # Windows  
source venv/bin/activate  # Mac/Linux  

3. Install dependencies
pip install streamlit requests beautifulsoup4  

4. Run Web Scraper
python web_scraper.py  

5. Run Chatbot
streamlit run app.py  

📦 Requirements
streamlit  
requests  
beautifulsoup4  
re (built-in Python library)  

🎯 Example Usage

User: I need scholarships for computer science  
Bot: Here are available scholarships for Computer Science students...

User: Scholarships in USA for Pakistani students  
Bot: These scholarships are available for Pakistani students in USA...

⚠️ Limitations

Does not use deep learning or advanced AI models  
Depends on scraped data quality  
Works on keyword-based matching only  

🔮 Future Improvements

🤖 Add NLP/AI model (Transformers or LLM integration)  
🌍 Expand scholarship database globally  
🔍 Improve smart search & filtering  
💬 Add ChatGPT-like conversational ability  
🚀 Deploy on Streamlit Cloud / Hugging Face  

👩‍💻 Author

AI Student Project  
Built for learning purposes:
Python Programming  
Web Scraping  
Streamlit Development  
Basic AI Chatbot Design  
