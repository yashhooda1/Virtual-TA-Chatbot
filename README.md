# Virtual-TA-Chatbot
This purpose of this project was to build a Virtual TA chatbot that can assist professors in asking student's questions. Used python libraries to build an AI model that satisfy teacher's requests.



Instructions for running this bot
1. Open command prompt and change the directory path to the pathway of the folder where the chatbot is located and run the following commands. Make sure you have python 3.4 or newer installed or else it won't run.

python3 -m venv rasa_env

# Activate the virtual environment
source rasa_env/bin/activate  # On Linux/Mac
# or
rasa_env\Scripts\activate      # On Windows

# Install Rasa within the virtual environment
pip install rasa


3. Train Your Chatbot:
Train your chatbot using the training data by running the following command:

rasa train

5. Test Your Chatbot:
Test your chatbot using the Rasa shell to interact with it in a command-line interface:

rasa shell
