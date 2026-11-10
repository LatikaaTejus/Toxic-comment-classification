# Toxic Message Classification with Zero-Shot LLMs

A machine learning and NLP project that evaluates and classifies toxic text comments using zero-shot prompting with the Google GenAI SDK (Gemini).

## Project Overview
- **Dataset:** Jigsaw Toxic Comment Classification Challenge (Kaggle)[cite: 2]
- **Approach:** Zero-shot classification using `gemini-2.5-flash`[cite: 7]
- **Metrics Evaluated:** Accuracy, Precision, Recall, and Confusion Matrix[cite: 10]

## Project Structure
- `toxic_msg_classify.ipynb`: The main Google Colab notebook containing EDA, data sampling, API inference, and evaluation metrics[cite: 2, 5, 6, 8, 10].
- `requirements.txt`: List of required Python dependencies.
- `README.md`: Project documentation.

## How to Run
1. Open the Jupyter Notebook in Google Colab or your local environment.
2. Set up your Gemini API key in Colab Secrets as `GEMINI_API_KEY`[cite: 6].
3. Run the cells sequentially.
