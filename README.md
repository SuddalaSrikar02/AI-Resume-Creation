🧠 AI Resume / Website Generator using Streamlit & Gemini

This project is a Streamlit-based AI application that generates a complete frontend website (HTML, CSS, JavaScript) based on user input. It uses Google Gemini (Generative AI) via LangChain to automatically create clean, professional frontend code and allows users to download the generated website as a ZIP file.

🚀 Features

🖊️ User-friendly Streamlit UI

🤖 Powered by Google Gemini AI

🌐 Automatically generates:

HTML

CSS

JavaScript

📦 Packages all files into a ZIP download

⚡ Fast and lightweight generation

🔐 Secure API key handling using .env

🛠️ Tech Stack

Python

Streamlit

LangChain

Google Generative AI (Gemini)

dotenv

HTML / CSS / JavaScript

📂 Project Structure
├── resume.py          # Main Streamlit application
├── index.html         # Generated HTML file
├── style.css          # Generated CSS file
├── script.js          # Generated JavaScript file
├── website.zip        # Downloadable ZIP file
├── .env               # Environment variables (API Key)

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/ai-website-generator.git
cd ai-website-generator

2️⃣ Install Dependencies
pip install streamlit langchain langchain-google-genai python-dotenv

3️⃣ Set Up Environment Variables

Create a .env file and add your Google Gemini API key:

gemini=YOUR_GOOGLE_API_KEY

▶️ Run the Application
streamlit run resume.py

🧪 How It Works

Enter a description of the website you want (e.g., portfolio, resume site).

Click Generate.

AI creates:

index.html

style.css

script.js

Files are zipped automatically.

Download your website with one click 🎉

📌 Example Use Cases

Resume websites

Portfolio websites

Landing pages

Business websites

Practice frontend projects

🔮 Future Enhancements

Multiple website templates

Live preview inside Streamlit

Dark/Light mode

Resume-specific layout generation

Deployment support (Netlify/Vercel)
