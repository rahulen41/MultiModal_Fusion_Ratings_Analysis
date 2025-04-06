## Multimodal Rating Analysis with NLP:
This analysis focuses on predicting credit ratings by combining structured financial market data with unstructured textual information using Natural Language Processing (NLP).

Here, end-to-end pipeline implemented by covering the required steps like data cleaning, feature engineering, modeling, and interpretation.

With NLP integration, Cleaned and lemmatized the financial text data. Extracted TF-IDF features to represent text numerically. This includes the sentiment polarity and subjectivity scores from TextBlob to enrich the feature set.

In this analysis, three models are trained: Structured-only, Text-only (NLP features) and combined model using both structured and unstructured data.
The combined model outperformed the individual models, demonstrating the value of integrating textual insights.

Here, SHAP values used to interpret model predictions and understand feature impact. Also, Plotted sentiment vs. rating, showing that more negative sentiment was generally linked with lower ratings.

Textual sentiment in financial commentary can act as a leading signal for rating downgrades. Combining market data with NLP leads to more accurate and explainable credit risk predictions.
