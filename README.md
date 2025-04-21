![image](https://github.com/user-attachments/assets/469b1c60-67ed-4e6a-8708-dd1ca6a2114e)# WhatsApp Chat Analyzer

A web application built with Streamlit that provides comprehensive analysis and visualization of WhatsApp chat data.

## Overview

WhatsApp Chat Analyzer is a tool that helps you analyze your WhatsApp conversations. Upload your chat export file and get insights through interactive visualizations including message trends, user activity patterns, sentiment analysis, word clouds, and emoji usage statistics.

## Features

- **Basic Statistics**: Total messages, word count, media shared, and links shared
- **Timeline Analysis**: Monthly and daily message patterns
- **Activity Mapping**: Most active days and months
- **User Activity**: Analysis of most active participants (for group chats)
- **Word Analysis**: Word clouds and most common words used
- **Emoji Analysis**: Most frequently used emojis with distribution charts
- **Sentiment Analysis**: Positive, negative, or neutral sentiment classification of messages

## Technologies Used

- **Streamlit**: For the web application interface
- **Pandas**: For data manipulation and analysis
- **Matplotlib & Seaborn**: For data visualization
- **TextBlob**: For sentiment analysis
- **URLExtract**: For extracting URLs from messages
- **WordCloud**: For generating word clouds
- **Emoji**: For emoji detection and analysis

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/whatsapp-chat-analyzer.git
   cd whatsapp-chat-analyzer
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Create a file named `stop_hinglish.txt` with common stop words to be filtered out in word analysis.

## Usage

1. Export your WhatsApp chat:
   - Open WhatsApp
   - Go to the chat you want to analyze
   - Tap on the three dots (menu) > More > Export chat
   - Choose "Without Media"
   - Save or share the exported file

2. Run the application:
   ```
   streamlit run app.py
   ```

3. Upload the exported chat file in the sidebar
   
4. Select a user to analyze or choose "Overall" for complete chat analysis
   
5. Click on "Show Analysis" to view the results

## Project Structure

- `app.py`: Main Streamlit application
- `preprocessor.py`: Functions for data cleaning and preparation
- `helper.py`: Helper functions for analysis
- `stop_hinglish.txt`: List of stop words to ignore in text analysis
- `requirements.txt`: Dependencies list
- `setup.sh`: Configuration file for deployment

## Deployment

The application is configured for deployment on platforms like Heroku using the included `setup.sh` file.

## Screenshots
![image](https://github.com/user-attachments/assets/2a823557-4d1e-44ab-93e5-8a1e884a8721)
![image](https://github.com/user-attachments/assets/e00a833e-f745-4e8e-bc4b-11b8b5004c3a)
![image](https://github.com/user-attachments/assets/61784ca3-dd52-4962-9d20-060d785e49b4)
![image](https://github.com/user-attachments/assets/602d1256-82da-47ab-9d26-412e494d4f61)
![image](https://github.com/user-attachments/assets/67c2d068-ceb5-490f-89e1-c1dff6ca2c64)

## Future Improvements

- Support for different date formats in chat exports
- Network analysis of chat interactions
- Topic modeling to identify conversation themes
- Enhanced sentiment analysis
- Support for more languages

## License

[Choose an appropriate license]

## Contact

[Your contact information]

---

*Note: This application is for personal use only and does not store any of your chat data.*

