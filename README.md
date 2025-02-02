AI News Bot with CrewAI Integration

This project automates news retrieval, web scraping, AI-generated news writing, and file saving using CrewAI.

Setup Instructions

Step 1. Install Dependencies

Ensure you have Python installed (version 3.10 recommended). Install dependencies using:

pip install -r requirements.txt

Step 2. Set Up Configuration Files

Create and configure the following files:

config/agents.yaml - Defines agents for retrieving news, scraping websites, writing news, and saving files.

config/tasks.yaml - Specifies tasks assigned to each agent.

Step 3. Create a .env File

Create a .env file in the root directory and add the required API keys and credentials:

SERPER_API_KEY="your_serper_api_key"
GROQ_API_KEY="your_groq_api_key"

Step 4. Run the Bot

Execute the script to start the AI news automation:

python main.py

Troubleshooting

Ensure all required dependencies are installed.

Check the .env file for missing API keys.

Verify configuration files (agents.yaml, tasks.yaml) are correctly set up.

Look for any API rate limits from external services.

This AI-powered bot fetches news topics, scrapes websites, generates news content, and stores the output efficiently using CrewAI.