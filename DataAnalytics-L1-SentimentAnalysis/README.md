# Task 4: Sentiment Analysis

## Project Overview
This project analyzes customer reviews and studies the distribution of positive, negative, and neutral sentiments using Python.

## Dataset
The dataset contains 30 customer reviews with two columns:
- `Review`
- `Sentiment`

The dataset contains 10 positive, 10 negative, and 10 neutral reviews.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Regular Expressions (`re`)
- Jupyter Notebook

## Analysis Steps
1. Loaded and inspected the customer review dataset.
2. Checked missing values.
3. Converted review text to lowercase.
4. Removed punctuation, special characters, and extra spaces.
5. Calculated sentiment counts and percentages.
6. Visualized the sentiment distribution.
7. Counted frequently used words separately for each sentiment.
8. Prepared key findings and a conclusion.

## Results
- Total reviews: 30
- Missing reviews: 0
- Positive: 10 (33.33%)
- Negative: 10 (33.33%)
- Neutral: 10 (33.33%)

## Key Findings
- All three sentiment categories are equally represented.
- The word `product` appears frequently across all three categories.
- Negative reviews include words such as `terrible`, `useless`, `poor`, and `disappointed`.
- Positive reviews include words such as `amazing`, `love`, `excellent`, and `fantastic`.

## Output Files
- `sentiment_analysis_dataset.csv` — Customer review dataset.
- `sentiment_analysis.ipynb` — Notebook containing the analysis.
- `01_sentiment_distribution.png` — Sentiment distribution chart.
- `02_positive_word_frequency.png` — Word frequency chart for positive reviews.
- `02_negative_word_frequency.png` — Word frequency chart for negative reviews.
- `02_neutral_word_frequency.png` — Word frequency chart for neutral reviews.

## Conclusion
The sample dataset contains an equal number of positive, negative, and neutral reviews. Text preprocessing and word frequency analysis help summarize the review data. The findings apply to this sample dataset and should not be generalized to all customers.