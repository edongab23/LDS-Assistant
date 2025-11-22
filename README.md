# LDS Assistant

> ⚠️ **FOR PERSONAL USE ONLY**
> 
> This tool is designed for personal spiritual study and preparation. Please verify all content with official Church sources before use in Church settings.

An AI-powered tool for creating LDS talks, lessons, and doctrinal explanations for personal study and preparation.

## ⚠️ Important Disclaimer
- This is a **personal study tool** only
- **Not an official Church resource**
- Always verify doctrine with scriptures, prophets, and Church leaders
- AI-generated content may contain errors
- Use for personal inspiration and study preparation only

## 🚀 Technical Details
- **Built with**: Python 3
- **AI Backend**: Ollama (local and cloud models)
- **Sources**: Official Church website (churchofjesuschrist.org)
- **Output Formats**: TXT and DOCX

## Features
- Generate talks for personal study and preparation
- Create interactive lesson plans for personal learning
- Expound on gospel topics with doctrinal depth for personal understanding
- Search official Church website for sources
- Support for both local and cloud AI models via Ollama

## Prerequisites
- Python 3.x
- Ollama installed and running

## Installation
1. Clone this repository
2. Install required packages:
   ```bash
   pip install -r requirements.txt

## Usage
1. Ensure Ollama is running with your preferred models
2. Run: `python3 lds-bot.py`
3. Follow the interactive prompts to create content

## Ollama Models
**You can use any Ollama models you prefer!** The tool is designed to work with any model that supports chat completion.

### Models I Personally Use
Here are the models I've tested and included in the configuration:

#### Local Models
- Llama3.2:1b
- qwen3:1.7b  
- gpt-oss:20b
- qwen3-coder:30b

#### Cloud Models
- cogito-2.1:671b-cloud
- gpt-oss:120b-cloud
- minimax-m2:cloud
- gemini-3-pro-preview:Latest
- kimi-k2:1t-cloud
- deepseek-v3.1:671b-cloud

### Adding Your Own Models
You can easily modify the `OFFLINE_MODELS` and `ONLINE_MODELS` lists in the code to add your preferred Ollama models.

## License
For personal use only. Not for official Church use.
