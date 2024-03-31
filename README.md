# Virtual-TA-Chatbot
This purpose of this project was to build a Virtual TA chatbot that can assist professors in asking student's questions. Used python libraries to build an AI model that satisfy teacher's requests.



Instructions for running this bot
1. Open command prompt and change the directory path to the pathway of the folder where the chatbot is located and run the following commands. Make sure you have python 3.4 or newer installed or else it won't run.

# Change to virtual env
python -m venv myenv

# Activate the virtual environment
source rasa_env/bin/activate  # On Linux/Mac
# or
myenv\Scripts\activate     # On Windows

# Install Rasa within the virtual environment
pip install rasa

# Change Directory to desired path
cd "C:\Users\yashh\OneDrive\Desktop\CS 4485\Chatbot"


# Train Your Chatbot:
Train your chatbot using the training data by running the following command:

rasa train

# Test Your Chatbot:
Test your chatbot using the Rasa shell to interact with it in a command-line interface:

rasa shell


# To interact with Rasa

rasa interactive
