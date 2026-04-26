# Spotify Hit Analysis: What Makes a Song Popular?

## Overview

This project analyzes a large-scale Spotify dataset to understand the factors influencing song popularity and listener engagement. It uses data analysis and visualization techniques to identify patterns across audio features, genres, and track characteristics.

---

## Problem Statement

What makes a song popular?

This project investigates whether popularity is driven by audio features such as energy and danceability, or whether external factors play a more significant role.

---

## Dataset

* Source: Kaggle Spotify Tracks Dataset
* Features include:

  * Popularity (0–100)
  * Danceability
  * Energy
  * Loudness
  * Duration
  * Genre
  * Artist

---

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Key Analysis Performed

### 1. Popularity Distribution

* Most songs fall within mid-to-low popularity ranges
* A small number of tracks achieve very high popularity

### 2. Feature Relationships

* Weak correlation between audio features and popularity
* No single feature strongly determines success

### 3. Genre Analysis

* Genres show distinct patterns in duration and structure
* Popularity varies significantly across genres

### 4. Correlation Analysis

* Strong relationships exist between some audio features (e.g., energy and loudness)
* Weak relationships with popularity

### 5. Custom Metric (Hit Score)

* A composite score was created using multiple audio features
* This improves interpretability compared to individual features

---

## Key Insights

* Popularity is multi-factorial and not explained by audio features alone
* Popularity distribution is highly skewed
* Audio features describe songs but do not fully explain success
* External factors such as marketing and artist influence likely play a major role

---

## Real-World Applications

* Music producers can use these insights to refine song characteristics
* Streaming platforms can improve recommendation systems
* Artists can better understand patterns in successful tracks

---

## Limitations

* No user behavior or playlist data included
* Popularity treated as a static metric
* External industry factors not captured

---

## Future Work

* Build predictive machine learning models
* Incorporate user listening and playlist data
* Perform clustering to identify song types
* Analyze trends over time

---

## Project Structure

```bash id="r3xqds"
spotify-analysis/
│── Exploratory_Data_Analysis_Spotify.ipynb
│── README.md
│── requirements.txt
│── images/
```

---

## How to Run

```bash id="0g95u9"
pip install -r requirements.txt
```

Run the notebook in Jupyter Notebook or Google Colab.

---

## Results

This project demonstrates that song popularity is influenced by a combination of factors, and cannot be explained by audio features alone.

---

## License

This project is licensed under the MIT License.
The dataset is sourced from Kaggle and follows its original licensing terms.

---

## Contact

Feel free to reach out for discussion or collaboration.
