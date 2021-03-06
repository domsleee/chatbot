# Chatbot

Uses a conversation dialog engine [ChatterBot](https://github.com/gunthercox/ChatterBot) and JSON message data from [Facebook information](https://www.facebook.com/settings?tab=your_facebook_information) to create a messenger bot that talks like you.

## Setup

1. Install requirements using `pip install -r requirements.txt`
2. Download facebook data from [Facebook information](https://www.facebook.com/settings?tab=your_facebook_information) as JSON. Extract the zip and note the path of the `messages` folder
3. Install [mongodb](https://docs.mongodb.com/manual/installation/) (e.g. `brew install mongodb`), and run the daemon `mongod`.
4. Run using `./chatbot.py <messages_folder>`. E.g. `./chatbot.py ~/Downloads/messages`
