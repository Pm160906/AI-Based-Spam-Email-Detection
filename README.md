# AI-Based Protocols for Spam Email Detection

This project explores the use of Artificial Intelligence in email communication protocols to detect and block spam at the Application Layer (OSI Layer 7).
Instead of relying on static rule-based filters, the system integrates Machine Learning into the SMTP workflow and uses IMAP for real-time email inspection.

---

## 📌 Objectives

- Design an AI-based protocol for spam detection.
- Integrate content analysis with SMTP decision logic.
- Perform real-time email scanning using IMAP.
- Reduce false positives for academic and professional emails.

---

## 🧮 Technologies Used
- Python
- Scikit-learn (Naive Bayes, CountVectorizer)
- IMAP & SMTP (protocol simulation)
- Streamlit (for visualization)
- Enron & Kaggle Email Datasets

---

## 📂 File Structure

| File / Folder                                      | Description                                                           |
|----------------------------------------------------|-----------------------------------------------------------------------|
| `ai based protocols for spam email detection.pdf`  | Full technical report                                                 |
| `email_spam_dataset.csv`                     | Dataset used for secondary validation                                 |
| `final_icn.ipynb`                                  | Complete implementation: training, hybrid logic, protocol simulation  |
| `introduction to computer networs.pdf`             | Summary presentation                                                  |

---

## 🔬 System Highlights
The system follows a hybrid decision pipeline:
- Whitelist Layer – trusted domains bypass filtering
- Keyword Heuristics Layer – academic/professional terms trigger safety override
- AI Confidence Layer – email is blocked only if spam probability exceeds threshold
- AI decisions are mapped directly to SMTP responses:
  - Spam → 550 Rejected
  - Safe → 250 OK

This simulates how an intelligent mail server could operate in a real network environment.

---

## 📊 Outcome

The model achieves high accuracy with low false positives and successfully monitors live email traffic using IMAP, demonstrating practical integration of AI with computer networking concepts.

