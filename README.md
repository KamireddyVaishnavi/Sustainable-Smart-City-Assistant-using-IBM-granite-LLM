Sustainable Smart City Assistant using IBM Granite LLM

📘 Overview

The Sustainable Smart City Assistant is an AI-powered application designed to support smart city development and sustainability initiatives using IBM’s Granite Large Language Model (LLM). This assistant can answer urban planning questions, suggest eco-friendly solutions, analyze environmental issues, and provide intelligent insights—all through natural language interaction.

It is built using IBM Granite LLM via Hugging Face, with development done in Google Colab and Jupyter Notebook, and packaged as an executable script in app.py for easy reuse and deployment.

🔍 Features

🌱 Recommends sustainable urban solutions

🏙️ Offers insights for smart city infrastructure

🌍 Answers environmental and policy-related questions

🤖 Powered by IBM Granite LLM via Hugging Face

🖥️ Run locally via app.py or explore in Jupyter Notebook/Colab

🧠 Technologies Used

IBM Granite LLM (via Hugging Face API)

Python 3.8+

Google Colab & Jupyter Notebook (for development/testing)

Hugging Face Transformers

Command-line execution with app.py

🚀 Getting Started

✅ Prerequisites

Python 3.8 or higher

Hugging Face account & API key

Git (optional, for cloning)

Internet connection (required to access the LLM)

💻 Run the Project Locally

Clone the Repository

git clone https://github.com/your-username/smart-city-assistant.git
cd smart-city-assistant

Install Required Dependencies

pip install transformers huggingface_hub
Set Hugging Face API Token You can log in from within the script or set an environment variable:

export HUGGINGFACEHUB_API_TOKEN=your_huggingface_api_key
Run the Application

python app.py

🌐 Option: Run in Google Colab
Open the notebook in Colab using the badge below:

Open In Colab

Insert your Hugging Face API key when prompted in the notebook.

Run all cells step-by-step.

📦 Project Structure

smart-city-assistant/
│
├── app.py                         # Main executable script
├── smart_city_assistant.ipynb     # Development/demo notebook
├── README.md                      # Project documentation
└── assets/                        # Optional assets (e.g., images)

📌 How It Works

Accepts a user query related to smart city sustainability.

Sends the query to IBM Granite LLM via Hugging Face API.

Displays intelligent, actionable insights as a response.

💡 Example Use Cases

“How can smart traffic systems reduce carbon emissions?”

“What are the best practices for waste management in urban areas?”

“Suggest sustainablearchitecture models for city planning.”

🤝 Contribution
Pull requests and feedback are welcome! If you'd like to contribute:

Fork the repo

Create a new branch

Submit a PR with your improvements

📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

🧩 Acknowledgments

IBM for Granite LLM
Hugging Face for model API access
Google Colab for development and testing support
