# Mobile Recommendation System 

This is a content-based machine learning recommendation system that suggests similar mobile phones based on their specifications.

## Dataset
The dataset contains mobile phone details such as:
- Name
- Ratings
- Price
- Technical specifications (corpus)

## Model Used
- TF-IDF Vectorizer
- Cosine Similarity

## How it works
1. Converts phone descriptions into numerical vectors
2. Computes similarity between all phones
3. Recommends top 5 most similar phones

## Libraries Used
- pandas
- numpy
- scikit-learn

## Example

Input:
"iPhone 13 mini"

Output:
Similar smartphones based on specs

## Author
Reem Abou Khalil
