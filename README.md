# Hotel Recommendation System with NLTK

## Introduction
This project focuses on developing a hotel recommendation system using Natural Language Toolkit (NLTK). The system utilizes content-based filtering to recommend hotels based on user input such as location and purpose of tour. It incorporates NLTK for text preprocessing and similarity calculations.
## Project Details

**Wander Way Bachelors' Final Year Project**
- Developed a travel app with a hotel recommendation system module for our final year project.
- Implemented a content-based filtering hotel recommendation system utilizing a dataset comprising 1500 data points.
- Prepared hotel data, performed preprocessing, and conducted analysis.
- Integrated the recommendation system into the mobile app interface.
## Required Libraries
- pandas
- matplotlib
- seaborn
- nltk






## Code Overview
The code demonstrates the implementation of a hotel recommendation system with NLTK. Key components include:

- **Data Preprocessing:** Cleaning and preprocessing hotel descriptions and tags.
- **Recommendation Function:** Function to recommend hotels based on user input.
- **Example Run:** Running the recommendation system with user input.

## How to Use
1. **Dependencies:** Install required libraries using pip:
   ```bash
   pip install pandas matplotlib seaborn nltk

Ensure NLTK data is downloaded:
```python
import nltk
nltk.download('vader_lexicon')
nltk.download('punkt')
nltk.download('wordnet')
nltk.download('stopwords')

