# Lucius
AI assistant for case law analysis (rechtspraak.nl)

Link to video of Lucius: https://clipchamp.com/watch/ei7PPMCW3DY 

# Legal Case Law Assistant

This is a Python script that helps with legal case law research (rechtspraak.nl). 

Users can add the ECLIs relevant for their research in the code. The API of rechtspraak.nl is used to retrieve the content of the ECLIs. 

Three novelties of Lucius are the following:
1. The user can search for multiple keywords in the same paragraph of the content (rather than across the entire text file), thereby making the search more specific. 
2. The search results can immediately be analyzed with a chatbot (the GPT-4 model of OpenAI is used)
3. The results of the chatbot contain footnotes in both in and under the text. These footnotes are based on the earlier search results of the keywords. Users can therefore immediately check the response of the chatbot, thereby increasing accuracy/validation. 

## Setup

1. Make sure you have Python installed.
2. Install the required packages: `requests`, `xml.etree.ElementTree`, `openai`.
3. Set up your OpenAI API key as an environment variable.

## How to Run

1. Navigate to the project directory.
2. Run `python your_script_name.py`.
3. Follow the on-screen instructions.

## Contributing

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are welcome.
