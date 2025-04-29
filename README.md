# sarcasm Detection
**Sarcasm Detection with DistilBERT**  
---

## 📝 Project Overview

This project focuses on fine-tuning the lightweight transformer model DistilBERT for the task of sarcasm detection in social media text, particularly tweets. Sarcasm is inherently nuanced and often requires understanding tone, context, and contradiction, making it one of the more complex challenges in NLP.


##  Directory Structure
```
Assignment-9-LLM/
├── Fine Tuning Sarcam.ipynb  # Main training and evaluation notebook  
├── README.md                    # Project documentation  
```

---

##  Setup Instructions

## Clone the repository
```bash
git clone https://github.com/your-username/Assignment-9-LLM.git
```

##️ Key Components

- *Dataset*: Automatic-Sarcasm-Detection-Twitter
- *Model*: `DistilBERT-base-uncased`
- *Evaluation Metrics*:
  - Accuracy
  - Weighted F1 Score
  - Precision and Recall
  - Confusion Matrix

---

## Results

| Metric                  | Value   |
|--------------------------|---------|
|Accuracy                   | 74.8%   |
| Test Weighted F1 Score    | 74.3%   |

---
# Future Improvements
Use back translation or GPT-generated paraphrasing for sarcastic data augmentation
Experiment with LoRA/Adapters for fine-tuning larger models with fewer parameters
Implement early stopping, learning rate warm-up, and checkpointing for stable training
Deploy the model using Gradio or upload to the Hugging Face Model Hub




