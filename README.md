# Climate-Change
Climate Change Using NLP
# Climate Change Public Sentiment Analysis

This project analyzes public sentiment on climate change using comments collected from NASA's official Facebook page dedicated to climate change discussions. It leverages Natural Language Processing (NLP) techniques to extract insights from user comments and track sentiment trends over time.

---

## Project Overview

Climate change is a critical global issue, and public opinion plays a vital role in shaping awareness and policy actions. This project uses NLP to analyze over 500 user comments from NASA’s Facebook posts (2020-2023) to:

- Perform **sentiment analysis** on user comments.
- Identify **trends in public sentiment** over time.
- Understand user engagement patterns.
- Extract common themes using **topic modeling**.

---

## Dataset Description

- **Source:** NASA's Facebook page on Climate Change (https://web.facebook.com/NASAClimateChange/)
- **Entries:** 522 comments collected from high-performing posts.
- **Columns:**
  - `date`: Timestamp when the comment was posted.
  - `likesCount`: Number of likes the comment received.
  - `profileName`: Anonymized user identifier (hashed for privacy).
  - `commentsCount`: Number of replies to the comment.
  - `text`: The text content of the comment.

---

## Project Structure

- `data/` - Folder containing the dataset file.
- `notebooks/` - Jupyter notebooks for data exploration and analysis.
- `results/` - Output plots and summary reports.

---

## Methodology

1. **Data Preprocessing:** Cleaning the comments, handling missing values.
2. **Sentiment Analysis:** Using VADER sentiment analyzer to assign sentiment scores (positive, negative, neutral, compound).
3. **Trend Analysis:** Aggregating sentiment scores daily to observe trends over time.
4. **Visualization:** Plotting sentiment trends and engagement metrics.
5. **Insights:** Interpreting public opinion dynamics and engagement.

---

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- nltk (VADER Sentiment Analyzer)

Install dependencies via:

```bash
pip install pandas numpy matplotlib seaborn nltk
