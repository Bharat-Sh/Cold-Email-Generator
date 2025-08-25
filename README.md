🚀 Cold Email Generator for Services Companies
An AI-powered Cold Email Generator that helps services companies reach out to potential clients by analyzing job postings and generating personalized cold emails.
Extracts job listings from company career pages (given a URL).
Uses Groq’s Llama-3.1 (via LangChain) to generate professional, context-specific emails.
Retrieves relevant portfolio links from a vector database (ChromaDB) to include in emails.
Provides a Streamlit-based interface for easy use by business development executives.

📖 Example Scenario
👉 Nike is hiring a Principal Software Engineer, investing significant resources in recruiting, onboarding, and training.
👉 A software development services company can offer a dedicated engineer instead.
👉 Mohan uses this tool to generate a personalized cold email to Nike, saving time and creating a professional first impression.

Set-up
To get started we first need to get an API_KEY from here: **https://console.groq.com/keys**. Inside **app/.env** update the value of **GROQ_API_KEY** with the **API_KEY** you created.
To get started, first install the dependencies using:
**pip install -r requirements.txt**
Run the streamlit app:
**streamlit run app/main.py**
