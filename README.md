# bart_distilbart_pegasus_t5_text_summarization
Multi-Model Text Summarizer

This project compares **4 state-of-the-art summarization models** using Hugging Face Transformers and Gradio:

- **BART (facebook/bart-large-cnn)**
- **DistilBART (sshleifer/distilbart-cnn-12-6)**
- **Pegasus (google/pegasus-xsum)**
- **T5 (t5-base)**

## 🚀 Features
- Input any long text (e.g., articles, reports).
- Generate summaries from all 4 models.
- Compare results side by side.
- (Optional) Provide a reference summary and compute **ROUGE scores**.

## 🖥️ Tech Stack
- Python
- Hugging Face Transformers
- PyTorch
- Gradio (for UI)
- Evaluate (for metrics)

## 📦 Setup
To run locally:

    pip install -r requirements.txt
    python app.py

## 🌐 Deployment
This app can run locally or be deployed on **Hugging Face Spaces**.
