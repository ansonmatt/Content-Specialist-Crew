# 📝 Autonomous Content Specialist Crew

### An autonomous, multi-agent AI editorial team built with CrewAI and Google Gemini (Free Tier). This project orchestrates an autonomous editorial team that transforms raw developer expertise into high-impact industry content.

# 🚀 Architecture
This project orchestrates four distinct AI agents to handle the end-to-end content creation lifecycle:

**Profile Analyst:** Extracts technical strengths and authoritative voice from a user's background.

**Market Researcher:** Analyzes target topics to uncover industry trends and content gaps.

**Editorial Strategist:** Cross-references expertise against market demand to score and select the highest-impact article angle.

**Specialist Copywriter:** Drafts a polished, highly engaging long-form article based on the winning strategy.

# 💻 How to Run Locally
Clone this repository.

Install dependencies: pip install -r requirements.txt

Create a .env file based on .env.example and add your Google Gemini API key.

Run the crew: python main.py

# ☁️ How to Run on Google Colab
To run this notebook securely without editing a single line of code, add your Gemini API key to your Colab Secrets:

Click the Key icon (Secrets) on the left sidebar of Google Colab.

Add a new secret named exactly GEMINI_API_KEY.  Paste your free API key from Google AI Studio (https://aistudio.google.com/api-keys) into the Value field. 

Toggle the "Notebook access" switch to ON.

The script will automatically pull this secret out of your vault, keeping your keys 100% invisible inside the code cells.
