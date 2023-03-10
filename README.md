
# AI Chat with Speech

This Python script combines the AI language model of Cohere and the AI speech API of Elevenlabs to generate speech from text input. The script uses the API of both technologies, so before running the script, you need to install the latest version of Python and pip. You also need to install the `requests` and `cohere` libraries.



## Getting API Keys

#### Get all items


To access the Cohere and Elevenlabs APIs, you need to obtain API keys from both services:

1. To get your Cohere API key, go to https://dashboard.cohere.ai/api-keys and sign up for an account if you haven't already done so. Once you're logged in, you can find your API key on the API Keys page.

2. To get your Elevenlabs API key, go to https://beta.elevenlabs.io/speech-synthesis and sign up for an account if you haven't already done so. Once you're logged in, you can find your API key on the Speech Synthesis page.

#### Install dependencies

```bash
pip install cohere
pip install requests
```

## Adding API Keys to the Program

To use the Cohere and Elevenlabs APIs in the program, you need to add your API keys to the main.py file. Open the file and look for the following lines:

```python
API_KEY_COHERE = 'YOUR_COHERE_API_KEY'
API_KEY_ELEVEN = 'YOUR_ELEVENLABS_API_KEY'
```

Replace `YOUR_COHERE_API_KEY` and `YOUR_ELEVENLABS_API_KEY` with your actual API keys, respectively.
## Running the Script

To run the script, navigate to the project directory in a terminal or command prompt and type:

```python
python main.py
```

The script will prompt you to enter a text input. Once you've entered your text, the script will generate speech using the Cohere and Elevenlabs APIs and play the speech for you.
## Demo


https://user-images.githubusercontent.com/82773456/224442090-420ec9c5-1fe3-48f7-a74c-88b670bb2828.mp4



