# AI Voice Detection and Vishing Detection Models

This repository contains two AI models developed for detecting deepfake voice audio and vishing (voice phishing) text messages.

---

## 1. AI Voice Detection Model

### Key Details:
- **Library Used:**
   - PyTorch  
   - Torchaudio  
   - Transformers (Hugging Face)

- **Model Name:**
   - Wav2Vec2 (Fine-tuned for audio classification)

- **Datasource:**
   - [Kaggle Deepfake Audio Dataset](https://www.kaggle.com/datasets/mohammedabdeldayem/the-fake-or-real-dataset)

### Purpose:
The AI Voice Detection model is fine-tuned on deepfake audio data to detect manipulated or synthetic voices effectively.

---

## 2. Vishing Detection Model

### Key Details:
- **Library Used:**
   - Transformers (Hugging Face)  
   - PyTorch  

- **Model Name:**
   - ScamLLM (Fine-tuned LLM for text classification)

- **Datasource:**
   - Custom-labeled dataset of phishing and non-phishing text samples

### Purpose:
The Vishing Detection model classifies text messages into phishing (vishing) and non-phishing categories using a fine-tuned large language model.

---

## Development Environment
- **Primary IDE:** Jupyter Notebook
- Both models are trained, tested, and implemented in a Jupyter Notebook environment to ensure flexibility and reproducibility.
