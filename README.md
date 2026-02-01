FIFA Player Role Classification using Machine Learning

This project predicts a football player's on–field role using their FIFA-style attributes.  
Roles are encoded into 8 classes (0–7), corresponding to positions such as GK, CB, FB, DM, CM, AM, W, and ST.

The project explores multiple machine learning algorithms and builds an end‑to‑end pipeline from data loading to an interactive prediction system.


## Project Structure

```text
.
├── 1.player_classification_1.ipynb        # Main EDA + preprocessing notebook
├── 2.KNN.ipynb                            # K‑Nearest Neighbors experiment
├── 3.player-naive-bayes.ipynb             # Naive Bayes experiment
├── 4.player_class_randomF_andDT-1.ipynb   # Decision Tree + Random Forest
├── 5.bagging_player.ipynb                 # Bagging ensemble
├── 6.Boosting_player.ipynb                # AdaBoost + HistGradientBoosting
├── 7.Stacking.ipynb                       # Stacking ensemble (best model)
├── 8.pipeline_player_classification.ipynb # End‑to‑end pipeline + UI/prediction
├── pipeline_predictions.csv               # Sample predictions (actual vs predicted)
├── models/                                # Saved .pkl models and scaler
└── data/                                  # cleaned_data.csv
```
## Dataset

This project uses publicly available football player data from Kaggle:


https://drive.google.com/file/d/1J-JMUD4TO6f9s-B7Ck0Rbe0DCHQZQ6pX/view?usp=sharing
https://www.kaggle.com/datasets/hugomathien/soccer
