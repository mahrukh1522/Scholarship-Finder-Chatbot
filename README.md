# 🎓 AI Scholarship Finder Chatbot  <!-- Project Title -->

📌 Overview  <!-- Short description of project -->

This project is an AI-based Scholarship Finder Chatbot built using Python and Streamlit.  
It helps students discover scholarships, eligibility criteria, and application guidance using scraped and structured online data.

The chatbot collects information from scholarship and educational websites and provides relevant answers based on user queries.


🚀 Features  <!-- Main functionalities -->

🌐 Web scraping of scholarship opportunities from trusted sources  
🎓 Scholarship recommendations based on user queries  
💬 Interactive Streamlit web interface  
⚡ Fast keyword-based response system  
📚 Organized dataset for easy information retrieval  
🎯 Helps students find local and international scholarships  


🧠 Technologies Used  <!-- Tools & libraries -->

Python 🐍  
Streamlit  
BeautifulSoup (bs4)  
Requests  
Regular Expressions (re)  


📁 Project Structure  <!-- Folder structure -->

AI-Scholarship-Finder-Chatbot/

│

├── app.py              # Streamlit chatbot UI  

├── web_scraper.py      # Web scraping script  

├── training_data.txt   # Collected scholarship dataset  

├── README.md           # Project documentation  


⚙️ How It Works  <!-- Working explanation -->


📥 Data Collection  <!-- Step 1 -->

Scrapes scholarship-related websites  
Extracts key details like eligibility, country, and field  
Stores cleaned data in training_data.txt  


⚙️ Processing  <!-- Step 2 -->

Splits text into sentences  
Matches user input with dataset keywords  
Finds most relevant scholarship information  


💬 Output  <!-- Step 3 -->

Displays scholarship suggestions in chatbot format  
Provides guidance on eligibility and application process  


🚀 How to Run  <!-- Execution steps -->


Step 1: Install dependencies

pip install streamlit requests beautifulsoup4  


Step 2: Run scraper

python web_scraper.py  


Step 3: Run chatbot

streamlit run app.py  


⚠️ Limitations  <!-- Weak points -->

- Does not use deep learning or advanced AI models  
- Depends on scraped data quality  
- Works on keyword-based matching only  


🔮 Future Improvements  <!-- Upgrades -->

- Add NLP/AI model (Transformers or LLM integration)  
- Expand global scholarship database  
- Improve smart search & filtering  
- Add ChatGPT-style conversational ability  
- Deploy on Streamlit Cloud / Hugging Face  


👩‍💻 Author  <!-- Developer info -->

Student Project – AI Scholarship Finder Chatbot  
Built for learning purposes:

- Python Programming  
- Web Scraping  
- Streamlit Development  
- Basic AI Chatbot Design  
