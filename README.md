# Built-With-AI---GDG-Cloud-Lahore-Lab-Submission
This is for workshop on gemini pro 



In Python Projects:
Environment Variables: Store your API key in an environment variable. This can be done by creating a .env file in your project root and adding your API key like so:
GEMINI_API_KEY=your_api_key_here
Access the Environment Variable in Python: Use a package like python-dotenv to load and use environment variables in your Python code. Here's a quick guide:
Install python-dotenv using pip:
pip install python-dotenv
Load your environment variables at the start of your script:
from dotenv import load_dotenv
import os

load_dotenv()  # This loads the environment variables from a .env file

GEMINI_API_KEY = os.getenv("GEMINI_API_KEY")
Use GEMINI_API_KEY in your code to authenticate with Google Gemini without exposing the key itself.
