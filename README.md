# 🔐 Data Anonymization Tool

A privacy-focused tool that anonymizes sensitive information from files such as **CSV, Excel, PDF, Word, and text documents** while keeping their formats intact.

---

## 📌 Why Anonymization?

Anonymizing data is essential for:
- Data privacy & compliance (GDPR, HIPAA, etc.)
- Secure data sharing & ML training
- Preventing exposure of personal or confidential info

---

## ⚙️ Features

✅ Randomized anonymization of:
- Names (e.g., "Amit" → "Lrkz")
- Phone numbers (e.g., `9876543210` → `9847543219`)
- Emails, addresses, IDs, etc.

✅ Format preserved — no masking with asterisks  
✅ Works with:
- `.csv`, `.xlsx`
- `.docx`, `.txt`
- PDF (text-based only)

✅ Group-wise anonymization:  
Same original value maps to the same anonymized output (e.g., all "Delhi" entries map to "Xyzia").

---

## 🛠️ Requirements

Add these to your `requirements.txt`:

