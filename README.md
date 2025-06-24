Ask the Constitution: RAG Chatbot Powered by Mistral AI
A Retrieval-Augmented Generation (RAG) chatbot built with Flask and Mistral AI, designed to help users ask detailed questions about the United States Constitution.

Whether you're a student, educator, researcher, or just curious about constitutional law, this tool helps surface relevant parts of the U.S. Constitution in response to your queries—instantly.

🔍 What It Does
This chatbot allows users to interactively ask questions about the U.S. Constitution. It:

Uses RAG techniques to pull relevant text chunks from the Constitution

Feeds them to Mistral AI for context-aware answers

Provides a simple, intuitive web interface via Flask

Ask questions like:

"What does the Constitution say about freedom of speech?"

"How is the President elected?"

"What are the powers of Congress?"

🚀 Getting Started
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/yourusername/us-constitution-rag.git
cd us-constitution-rag
2. Create a virtual environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Add your Mistral API key
Create a .env file in the root directory:

ini
Copy
Edit
MISTRAL_API_KEY=your_api_key_here
5. Add the U.S. Constitution text
Place the source text (e.g. us_constitution.txt) in the project root and rename it to:

Copy
Edit
essay.txt
🧪 Local Development
Run the Flask app:

bash
Copy
Edit
python app.py
Visit the chatbot at: http://localhost:5001

🌍 Deployment to Vercel
Push your repo to GitHub

Link it to Vercel

In Vercel settings, add your environment variable:

MISTRAL_API_KEY: your API key

Deploy!

🔧 Project Structure
bash
Copy
Edit
├── app.py              # Main Flask application
├── essay.txt           # Text source (U.S. Constitution)
├── templates/          # HTML templates
├── static/             # Static assets (CSS, JS)
├── requirements.txt    # Python dependencies
├── vercel.json         # Deployment configuration
└── .env                # Environment variables
📘 License and Attribution
This project is based on the educational template by Halim Madi, modified and adapted for constitutional education and RAG experimentation.

You're welcome to:

Use it for learning and teaching

Adapt it for other public documents

Extend or integrate it with other RAG workflows

🤝 Contributions Welcome
Pull requests and improvements are welcome! Got a feature idea or want to improve document handling? Fork the repo and open a PR.

