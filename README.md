# WhatsApp Chat Analyzer

## Project Overview
WhatsApp Chat Analyzer is a Streamlit-based web application that provides insights and statistical analysis of WhatsApp chat data. The tool processes exported chat files (without media) and presents various analytics, such as message frequency, most active users, commonly used words, and emoji usage.

## Features
- Total message, word, media, and link count
- Monthly and daily activity timeline
- Weekly and monthly activity maps
- Busiest users in the chat
- Word cloud visualization
- Most common words used
- Emoji analysis with frequency distribution
- Heatmap of message activity

## Tools and Technologies Used
- **Python**: Core programming language for processing and analysis.
- **Streamlit**: Web framework for building the interactive UI.
- **Pandas**: Data processing and manipulation.
- **Matplotlib & Seaborn**: Data visualization.
- **WordCloud**: Generation of word clouds.
- **Emoji**: Emoji processing and analysis.
- **URLExtract**: Extraction of URLs from messages.

## Setup and Installation
### Requirements
The dependencies required for this project are listed in `requirements.txt`. To install them, run:
```sh
pip install -r requirements.txt
```

### Running the Application
To start the Streamlit application, execute:
```sh
streamlit run app.py
```

## Usage Instructions
1. Export a WhatsApp chat (without media) from the WhatsApp app.
2. Upload the exported `.txt` file to the web interface.
3. Select the desired user for analysis (or analyze the entire chat).
4. Explore various insights and visualizations provided by the tool.

## File Structure
- `app.py` - Main application file for Streamlit.
- `preprocessor.py` - Functions for cleaning and structuring the chat data.
- `helper.py` - Functions for generating insights and visualizations.
- `requirements.txt` - List of required dependencies.
- `setup.sh` - Configuration file for deployment.
- `stop_hinglish.txt` - Stopword list for text processing.

## Author
Developed by **Salma Elmasry**.

