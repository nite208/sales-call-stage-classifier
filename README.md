# sales-call-stage-classifier
A logistic regression-based text classifier for predicting sales call stages from transcripts.


# Sales Call Stage Classifier

This project uses machine learning (Logistic Regression) to classify the **stage of a sales call** (e.g., Opening, Qualifying, Closing) from the call transcript.

## Files

- `extended_sales_transcripts.csv` — Dataset containing call transcripts and their corresponding sales stage.
- `sales_stage_classifier.ipynb` — Jupyter notebook with preprocessing, model training, evaluation, and Gradio app.

## Libraries Used

- pandas, numpy, scikit-learn
- matplotlib, seaborn
- gradio (for web interface)

## How it Works

1. Load & clean the data
2. Transform text into features using TF-IDF
3. Train a logistic regression model
4. Predict the stage of a new call transcript
5. Evaluate with Accuracy, Log Loss, Confusion Matrix

## Sample Output

- Accuracy: `92.6%`
- Log Loss: `0.24`
- Confusion matrix displayed with seaborn heatmap

## Try the Web App

Used the Gradio interface to test the model

## Confusion Matrix
![image](https://github.com/user-attachments/assets/1817e11d-d55b-4f9e-bf49-6d53d6e02cc3)

## Web Interface
![image](https://github.com/user-attachments/assets/ee921454-02a7-48de-845e-8a4afc471cc6)

