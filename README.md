# 🚢 Titanic Survival Prediction with TF-DF Ensemble

## 🎯 Goal
### Use ensemble modeling with TensorFlow Decision Forests to predict Titanic passenger survival more accurately.

## 🧠 What I Did
### 🌱 Converted the raw dataset to a TensorFlow-friendly format using pd_dataframe_to_tf_dataset
### ✂️ Tokenized passenger names to help TF-DF process text better
### 🌳 Trained 200 models using GradientBoostedTreesModel with different random seeds
### 🧮 Averaged their predictions to get one powerful final prediction

## 🚀 Why Ensemble?
### Instead of trusting one model...
### I let 200 models vote and made my final prediction based on the average of all outputs 🔁

### ✅ Reduced randomness and noise
### ✅ Boosted stability
### ✅ Helped me hit 💯 Kaggle score: ~0.80

## 📦 Tools Used
### 🐼 Pandas
### 🌿 TensorFlow Decision Forests
### 🧪 Jupyter Notebook
### 📊 Kaggle Titanic Dataset

## 🎯 Accuracy Achieved
### ✅ ~ 0.80 Kaggle score (Top-tier!)
### 💡 Ensemble = more reliable, stable & powerful predictions
