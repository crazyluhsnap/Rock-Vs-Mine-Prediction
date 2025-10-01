# Rock Vs Mine Prediction 

This is a small machine learning project where I trained a model to classify whether an object detected by sonar is a **Rock** or a **Mine**.

The dataset I used is the **Sonar dataset** (often referred to as the *Rock vs Mine dataset*), which contains 60 features for each sonar signal and a label (`R` for Rock, `M` for Mine).

---

## 📂 Project Structure
- `sonar_classification.ipynb` → Jupyter/Colab notebook with all the code  
- `sonar data.csv` → dataset (if you want to run it locally, place it in the same folder)  

---

## 🚀 Steps in the Notebook
1. Imported libraries (`pandas`, `numpy`, `sklearn`)  
2. Loaded the dataset into a pandas DataFrame  
3. Split the data into features (`X`) and labels (`Y`)  
4. Trained a **Logistic Regression model**  
5. Evaluated model accuracy on training & test sets  
6. Made predictions on sample sonar readings (Rock or Mine)  

---

## 🔮 Sample Prediction
For example, if we input sonar readings like this:

```python
(0.0414,0.0436,0.0447,0.0844,...,0.0198)

```
The output will look like
```python
['R']
The object is a Rock
```
## 📊 Accuracy
- The Logistic Regression model reached around X% accuracy on the test set (depends on your train/test split).

## ⚙️ How to Run
1. Clone this repo
2. Open the notebook in Jupyter or Google Colab
3. Run all cells (make sure you have pandas, numpy, and scikit-learn installed)

## 📝 Notes
- This is a beginner-friendly project I made while learning ML concepts.
- Logistic Regression works decently well for this dataset, but you can also try other classifiers (Random Forest, SVM, etc.) for comparison.
