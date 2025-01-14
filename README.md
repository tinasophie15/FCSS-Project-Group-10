# FCSS-Project-Group-10
This repository contains the work and analyses for the group project focused on investigating media bias in the Israel-Palestine conflict. The project explores how different media outlets frame and report on the conflict by analyzing sentiment and keyword usage over time.

# Members
| Role                      | Name                  | 
| :---                      |    :----:             |
| **Sentiment Analysis**    |     Nejla Hidic       |
| **Keyword Analysis**      |     Jiamin Shen       |
| **Keyword Analysis**      |     Binbin Yang       |
| **Sentiment Analysis**    |  Christina Sophie Knes |

# Project Overview:

Research Question:
To what extent can sentiment, keyword usage, and event salience in US mainstream media's reporting on the Israel-Palestine conflict reveal patterns of bias?

Objective:
This project aims to analyze and identify possible biases in media coverage of the Israel-Palestine conflict by assessing sentiment, keyword usage, and the prominence of key events reported by six media outlets.
Media Outlets Analyzed:

    Fox News
    CNN
    Washington Post
    Washington Times
    New York Times
    New York Post

Methodology:

    Data Collection: Data is gathered from the Media Cloud platform, which provides headlines and articles from the six chosen media outlets.
    Sentiment Analysis: Sentiment scores for headlines are calculated using the VADER Sentiment Analyzer and the Transformers pipeline for sentiment classification. This helps determine whether the tone of media coverage is positive, negative, or neutral.
    Keyword Analysis: Keywords related to key players, events, and terms (such as “Israel,” “Palestine,” “war,” etc.) are analyzed to uncover any patterns in framing.
    Timeline & Key Events: A timeline of important events is considered, and sentiment changes are tracked around these events to investigate shifts in media portrayal.

Key Deliverables:

    A comprehensive analysis of sentiment trends across different media outlets.
    Identification of keywords and phrases used in the media coverage of the conflict.
    Insights into potential media bias based on sentiment shifts and keyword usage.

Tools and Libraries Used:

    Python Libraries:
        pandas for data manipulation and analysis
        matplotlib and seaborn for data visualization
        nltk and transformers for sentiment analysis
        spaCy for text processing and NLP tasks
        wordcloud for visualizing common keywords
        VADER for sentiment intensity analysis

How to Run the Project:

    Clone this repository to your local machine:

git clone https://github.com/yourusername/FCSS-Project-Group-10.git

Install the required dependencies:

pip install -r requirements.txt

Run the project code:

    python main.py

License:

This project is licensed under the MIT License - see the LICENSE file for details.
