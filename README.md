# Missing Keyword Analyzer

A tool that analyzes content to identify missing keywords from the homework and provides it's summary using Google's Gemini AI.

## Features

- Takes two input files for comparison analysis
- Identifies missing keywords in homework/assignments
- Lists missing keywords with detailed analysis
- Provides AI-generated summary of missing keywords and their categories/groups
- Powered by Google Gemini AI for intelligent analysis

## Prerequisites

- Python 3.7+
- Google Gemini API key

## Setup

1. Clone the repository:
```bash
git clone https://github.com/Arya-Lingayat/Missing-keyword-analyzer.git
cd Missing-keyword-analyzer
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. **Add your Gemini API key:**
   - Get your API key from [Google AI Studio](https://aistudio.google.com/app/apikey)
   - Add it to your environment variables or configuration file
   - Update the API key in the code where specified

## Usage

```bash
python main.py
```

Follow the prompts to analyze your content and get keyword suggestions.

## Configuration

Make sure to configure your Gemini API key before running the application. The tool requires a valid API key to function properly.

## Contributing

Feel free to open issues and submit pull requests to improve the tool.

 
