# ACL Task A – Sentiment Analysis

## 📌 Project Overview
This project is part of **ACL Task A** from the **ACL Shared Task on Sentiment Analysis**, where we fine-tuned **Google's Gemini LLM** to enhance sentiment classification performance. The goal was to accurately classify text samples based on emotional tone while considering **bias and fairness metrics** in language model outputs.

## 🚀 Methods Used
- **Dataset Preparation:** Preprocessed text data for sentiment classification.
- **Model Fine-Tuning:** Fine-tuned **Gemini LLM** for improved classification accuracy.
- **Prompt Engineering:** Experimented with various prompt structures to optimize results.
- **Evaluation Metrics:** Used accuracy, precision, recall, and **fairness metrics** to assess model performance.

## 🔬 Results & Findings

### Classification Performance by Model:
| Emotion   | Llama 3 (Non-Fine-Tuned) | DistilBERT (Non-Fine-Tuned) | DistilBERT (Fine-Tuned) | Gemini (Fine-Tuned) |
|-----------|---------------------------|-----------------------------|--------------------------|----------------------|
| **Anger** | Precision: 88%, F1: 62%  | Precision: 1%, F1: 22%     | Precision: 65%, F1: 51% | Precision: 97%, F1: 93% |
| **Fear**  | Precision: 53%, F1: 60%  | Precision: 42%, F1: 25%    | Precision: 78%, F1: 81% | Precision: 77%, F1: 77% |
| **Joy**   | Precision: 93%, F1: 79%  | Precision: 60%, F1: 0%     | Precision: 68%, F1: 62% | Precision: 86%, F1: 86% |
| **Sadness**| Precision: 85%, F1: 88% | Precision: 68%, F1: 34%    | Precision: 72%, F1: 67% | Precision: 83%, F1: 83% |
| **Surprise**| Precision: 80%, F1: 83%| Precision: 68%, F1: 12%    | Precision: 75%, F1: 67% | Precision: 84%, F1: 79% |

### Key Insights:
- **Llama 3 (Non-Fine-Tuned):** Performed moderately well, particularly on anger and joy, but struggled with recall for other emotions.
- **DistilBERT (Non-Fine-Tuned):** Showed poor performance across all categories, highlighting the need for fine-tuning.
- **DistilBERT (Fine-Tuned):** Demonstrated significant improvements, particularly for fear (F1: 81%) and sadness (F1: 67%).
- **Gemini (Fine-Tuned):** Delivered the best overall performance, with F1-scores above 77% across all emotions.

---

## 🚀 Contributors:
- **Deepansh Batra:** deepanshbatra13@gmail.com  
- **Aya El-Dassouki:** dassoukiaya24@gmail.com  
