# Description

This is a simple python script that uses the OpenAI API to generate a text based on a prompt.
This is done to replicate a stutter issue that I have while using elevenlabs voice generator in stream mode.

# Installation

To create a virtual environment (optional):
```
python3 -m venv venv
```

Or using virtualenv (Don't run this if you already ran the previous command):
```
virtualenv venv
```

To install openai:
```
pip install --upgrade openai
```

To install elevenlabs:
```
pip install elevenlabs
```

To install python-dotenv:
```
pip install python-dotenv
```

# Usage

To use this script, you need to create a `.env` file on the root directory of the project with your __OpenAI API key__ and __Elevenlabs API key__.

```
OPENAI_API_KEY=your_api_key
ELEVENLABS_API_KEY=your_api_key
```

Then you can run the script with the following command:

```bash
python3 stutter.py
```
