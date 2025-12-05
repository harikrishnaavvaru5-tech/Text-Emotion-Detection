# Text Emotion Detection

A Python-based machine learning project to detect emotions from text. This project uses NLP techniques to classify text into emotions like **happy, sad, angry, surprise, fear, and neutral**.

## Table of Contents

- [Features](#features)
- [Dataset](#dataset)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- Predict emotions from user input text.
- Supports multiple emotion categories.
- Interactive interface using **Streamlit**.
- Can be integrated into chatbots, sentiment analysis dashboards, or social media analysis tools.

## Dataset

The project uses a labeled dataset of text samples and their corresponding emotions.  
Example CSV format:

| Text                       | Emotion |
| -------------------------- | ------- |
| I am so happy today!       | happy   |
| I feel very sad right now. | sad     |
| This is terrifying!        | fear    |

You can replace `emotion_dataset.csv` with any other dataset following this format.

## Tech Stack

- Python 3.x
- Scikit-learn
- Pandas
- NLTK
- Streamlit (for the web interface)
- Joblib (for saving and loading the trained model)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/Text-Emotion-Detection.git
cd Text-Emotion-Detection
```
