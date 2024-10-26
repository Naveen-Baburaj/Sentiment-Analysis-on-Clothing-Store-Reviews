# Sentiment Analysis on Clothing Store Reviews

## Project Overview

This project analyzes customer sentiment on a variety of clothing products to help a fashion retailer understand customer opinions and improve product quality and customer experience. 

## Data Description

The dataset consists of customer reviews of a clothing store categorised by product types, including **Bottoms**, **Dresses**, **Intimate Wear**, **Jackets**, and **Tops**. 

## Project Features

1. **Sentiment Classification**:
   - Uses VADER (Valence Aware Dictionary and sEntiment Reasoner) from the NLTK library to classify reviews as positive, neutral, or negative based on sentiment scores.
2. **Data Visualization**:
   - Grouped bar charts display the distribution of sentiment across product categories.
   - Word clouds highlight common adjectives used in each sentiment category.
3. **Insights and Reporting**:
   - Summarizes customer satisfaction trends by product category.
   
## Usage

1. **Data Preprocessing**:
   - Open the Jupyter notebook to clean and preprocess the text data, removing stopwords and tokenizing the reviews.

2. **Sentiment Analysis**:
   - The VADER sentiment analyzer is applied to classify reviews into positive, neutral, and negative sentiments.

3. **Visualization**:
   - Bar charts and word clouds are generated to visualize the sentiment distribution and common descriptive words.

Run the Jupyter notebook (`sentiment_analysis.ipynb`) to execute the analysis and generate visualizations.

## Visualizations

- **Sentiment Distribution Bar Chart**: Displays the counts of positive, neutral, and negative sentiments for each product category.
- **Word Clouds**: Highlights common adjectives in positive, neutral, and negative reviews.
  
The visualizations are saved in the project directory and displayed within the notebook for ease of reference.

## Conclusion

The analysis reveals:
- High customer satisfaction across all product categories, especially for **Bottoms** and **Jackets**.
- Minimal negative feedback, with slightly more neutral sentiment in **Dresses**.
  
These insights can guide improvements in product offerings and customer service strategies to align better with customer expectations.

## Technologies Used

- **Python**: Data analysis and NLP
- **NLTK**: Sentiment analysis with VADER
- **Seaborn & Matplotlib**: Data visualization
- **Pandas**: Data manipulation and analysis

---
