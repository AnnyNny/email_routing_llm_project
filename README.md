# Email routing project
Customer support email routing using GPT-2, DistillGPT2, LoRA, DistilBERT and TF-IDF. 

# Results
DistilBERT achieved the best accuracy, while TF-IDF + Logistic Regression was the fastest method and also performed well
| Method | Accuracy | Training time (s) | Inference time (s) |
|---|---:|---:|---:|
| GPT-2 + prompting | 0.2420 | 0 | 6.44 |
| DistilGPT2 + prompting | 0.4243 | 0 | 3.25 |
| GPT-2 + LoRA | 0.6741 | 930.38 | 5.82 |
| DistilGPT2 + LoRA | 0.6530 | 515.86 | 3.34 |
| DistilBERT classifier | **0.8365** | 417.61 | 2.52 |
| TF-IDF + Logistic Regression | 0.7514 | 16.78 | **0.23** |
