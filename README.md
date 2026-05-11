# 🎫 AI Support Ticket Classification & Priority System
**ML Internship Task 2 | Future Interns**

## 📖 Business Overview
This project solves a critical operational challenge for SaaS companies: the manual triage of customer support tickets. 

## ⚙️ Technical Approach
### 1. NLP Text Processing
* **Normalization:** Standardizing cases and removing punctuation.
* **Stopword Removal:** Eliminating noise words to focus on "intent" keywords.

### 2. Feature Extraction (TF-IDF)
I utilized **TF-IDF** to transform raw text into numerical significance, allowing the model to prioritize keywords like "Access," "Payment," or "Error."

### 3. Classification & Priority Logic
* **Categorization:** Routes tickets into departments: Technical, Billing, or General Inquiry.
* **Priority Decision:** I integrated logic to detect urgency. Tickets containing critical failure language are escalated to **High Priority**.

### 4. Model Evaluation
The system was validated using a **Confusion Matrix** to ensure high precision in routing.

---
**Author:** Thomas Debebe
**CIN:** FIT/APR26/ML7294