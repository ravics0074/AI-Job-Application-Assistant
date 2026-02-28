AI Job Application Assistant | Gen AI Capstone 2025
This project was built as part of the Google Gen AI Intensive Capstone 2025. It showcases how Generative AI can automate the job application process using Google Gemini Pro.
 
🔍 Overview
The AI Job Application Assistant helps job seekers streamline their application process by:
•	Matching resumes with job descriptions
•	Scoring job-resume compatibility
•	Suggesting customized resume bullet points
•	Auto-generating a personalized cover letter
•	Outputting all data in structured JSON format
All of this is done using Generative AI prompts and automation, reducing manual effort while improving quality and personalization.
 
✨ Key Features
•	✅ Match score calculation between job descriptions and resumes
•	✅ AI-generated resume enhancements
•	✅ Tailored cover letter creation
•	✅ JSON output for use in trackers or dashboards
•	✅ Lightweight agent-like logic for step-by-step automation
 
🧠 GenAI Techniques Used
•	Retrieval-Augmented Generation (RAG-style prompts)
•	Structured Output (JSON formatting)
•	Agent-style Task Automation
•	Few-shot Prompt Engineering
•	Grounding
•	LOng Context Handling
 
🛠 Built With
•	Google Gemini Pro (via google-generativeai SDK)
•	Python (Jupyter Notebook / Kaggle)
•	Markdown, JSON
 
🚀 Setup & Usage
1. Install dependencies
pip install google-generativeai
2. Set your Google API key
import google.generativeai as genai genai.configure(api_key="your_google_api_key_here")
3. Run the notebook
Follow the code steps to input your resume and a job description. The model will generate match insights, JSON data, and a custom cover letter.
📁 Project Structure
AI-Job-Application-Assistant/ ├── README.md
├── Capstone_Notebook.ipynb
├── assets/
│ └── thumbnail.png
└── examples/
└── sample_outputs.json

![Uploading image.png…]()
