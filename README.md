# Predicting Song Popularity Using Machine Learning

This project uses machine learning techniques to predict a song's popularity score (0–100) based on its audio features such as danceability, energy, loudness, valence, tempo, and more. The analysis includes exploratory data analysis (EDA), data preprocessing, multiple regression models, and final evaluation.

All materials represent original work completed independently as part of graduate-level coursework.

---

## Project Overview

The goal of this project is to explore whether measurable audio features can predict a song’s popularity.  
This is a **regression problem**, and the notebook includes:

- Exploratory data analysis (EDA)
- Data cleaning and preprocessing
- Multiple machine learning models
- Performance comparison
- Feature importance analysis
- Final conclusions and insights

---

## Dataset

The dataset contains audio features for 170,000+ of Spotify tracks, including:

- `danceability`
- `energy`
- `loudness`
- `speechiness`
- `acousticness`
- `instrumentalness`
- `liveness`
- `valence`
- `tempo`
- `duration_ms`
- **Target:** `popularity` (0–100)

**Note:**  

You can also download the raw dataset from Kaggle here:  
*[https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db ]*

---

## Goals

- Determine which audio features most strongly influence popularity,  
- Compare regression models taught in the course,   
- Evaluate models using RMSE, MAE, and R-squared,   
- Identify the best-performing model,  
- Provide insights for music analytics and recommendation systems.

---

## Machine Learning Methods Used

This project uses models covered in the Machine Learning course, including:

- Linear Regression
- k-Nearest Neighbors Regression (kNN)
- Decision Tree Regression

---

## Files Included

- notebooks/
  - `01_Introduction_and_EDA.ipynb`
  - `02_Preprocessing_and_Modeling.ipynb`
  - `03_Evaluation_and_Conclusion.ipynb`
- slides/
  - `SpotifyPopularityPredictionSlides.pdf`
- `SpotifyTracksDataset.Popular.csv`
- `README.md`
- `LICENSE`


## Project Artifacts

This repository includes the following materials:

- **Jupyter Notebooks:** Full exploratory analysis, data preprocessing, model training, and evaluation workflow  
- **Project Slides:** A concise presentation summarizing the motivation, methodology, results, and conclusions  

The slides provide a high-level overview of the project, while the notebooks contain the complete technical implementation.

All materials represent original work completed independently as part of graduate-level coursework.


## License

This project is licensed under the MIT License. See the LICENSE file for details.


## Citation

If you reference this project, please cite:

Olsen, A. N. (2026). *Spotify Song Popularity Prediction using Machine Learning*. GitHub repository.



