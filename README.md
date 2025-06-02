# Medical-Help-App-using-GPT-4V

This project is a **Streamlit-based AI web application** that uses **OpenAI's GPT-4 with Vision (GPT-4V)** to analyze medical images such as X-rays, MRIs, or other scans. It helps users get AI-generated insights and simplified explanations — ideal for educational, research, or personal curiosity purposes.

>  **Disclaimer**: This tool is **not a substitute for professional medical advice or diagnosis**. Always consult a healthcare professional for medical concerns.

---

##  Features

- Upload and analyze medical images
- Powered by GPT-4 Vision for deep visual understanding
- Returns findings, recommended actions, and possible conditions
- Includes an "ELI5" (Explain Like I'm 5) version of the response
- Built with Streamlit for quick deployment and testing

---

##  How to Run the Project

python -m venv venv
.\venv\Scripts\Activate.ps1 

pip install -r requirements.txt 

streamlit run app.py

And don't forget to set your API key securely as an environment variable
