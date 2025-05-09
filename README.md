AI LLM Conversation Bot
A project where two AI models (GPT & Claude) have a conversation with each other, generating responses based on their interactions.

📌 Features
✔️ Uses GPT (OpenAI) and Claude (Anthropic) to generate conversations
✔️ Simulates an AI-to-AI discussion
✔️ Implements structured message handling
✔️ Easy-to-run Python script

🚀 How It Works
GPT generates a response based on past messages.
Claude responds to the last message from GPT.
The process continues, creating an automated AI conversation.
📂 Project Structure

📁 AI-Conversation-Bot/
│── 📜 main.py              # The core script for the conversation
│── 📜 requirements.txt     # Required dependencies
│── 📜 README.md            # Documentation
│── 📜 config.py (Optional) # API keys or settings
🔧 Installation & Setup

1️⃣ Clone the Repository
git clone https://github.com/paschal-godwin/AI-LLM-conversation.git
cd AI conversation projects

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Project
python main.py
⚙️ Configuration (API Keys)
Make sure you have API keys set up for OpenAI (GPT) and Anthropic (Claude).

Store them in environment variables or a config.py file (avoid hardcoding API keys).
Example:

OPENAI_API_KEY = "your_openai_key_here"
CLAUDE_API_KEY = "your_claude_key_here"

Example Output

GPT: "Hello Claude! How do you feel about AI ethics?"
Claude: "Great question! AI ethics is about ensuring fairness and transparency..."
GPT: "Agreed! We must balance innovation with responsibility."
Claude: "Exactly! What challenges do you think we'll face?"
...
🛠️ Future Improvements
🔹 Add a user interface (Gradio or Streamlit)
🔹 Support for more AI models (Llama, Mistral, etc.)



🤝 Contributing
Want to improve this project? Feel free to fork it, open issues, or submit pull requests!

⭐ Like This Project?
Give it a ⭐ on GitHub if you find it useful!
