# AI-Mini-Projects
This is my some Ai mini projects

## 📑Prerequisites
#### to run these projects ,you will need
##### ▫️python 3.8+
##### ▫️Dependencies:
          pip install openai python-dotenv streamlit PyPDF2
##### ▫️An OpenAI key:
###### 1.sign up at OpenAI
###### 2.create a .env file in your project folder with:
          OPENAI_API_KEY=your-api-key-here
##### ▫️A code editor(ex:VS code,pycharm)
##### ▫️Basic familiarity with python and APIs

## 🔧Setup Guid
#####  1.clone or create a project folder:
          mkdir ai-mini-projects
          cd ai-mini-projects
##### 2.Set up a virtual environment:
         python -m venv venv
         venv\Scripts\activate
##### 3.Install dependencies:
         pip install openai python-dotenv streamlit PyPDF2
##### 4.Create a .env file with your OpenAI API key
##### 5.Run each project by copying the code  into a .py file and running:
          python your_file.py


### 1️⃣ AI Text Summarizer
📌what it does:Summarizes long text(articles,essays,PDFs)into concise bullet points

##### 🎯Features
######   ▫️Supports text and PDF input
######   ▫️Customizable summary length
######   ▫️Error handling for API failures

##### 💡Improvements
######  ▫️Add multiple summary styles(e.g "Execute Summary" , "Simplified for kids")
######  ▫️Integrate with Streamlit for a web-based UI where users can upload PDFs or paste text
######  ▫️Support multiple languages for summaries using language-specific prompts.
######  ▫️Add keyword extraction using libries like *spacy* or *nltk*.
          
