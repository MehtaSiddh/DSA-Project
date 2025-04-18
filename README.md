# 📧 Spam Email Classifier (DSA Project)

This project implements a **Spam Email Classifier** using data structures like **hash maps (chaining and open addressing)**. It also includes a **GUI built with GTK** to classify, analyze, and update word frequencies based on spam/ham emails.

---

## 🔧 Features
- **Email classification** based on word frequencies
- Two custom hash map implementations:
  - Chaining Hash Map
  - Open Addressing Hash Map
- GUI to:
  - Load and classify emails
  - View and filter word dataset
  - Mark emails as spam/ham
  - Visualize spam/ham word influence using color highlights

---

## 🧠 How It Works
- Loads a **transposed CSV file** containing words and their frequency in spam and ham emails.
- Computes **spam probability** for a given email.
- Classifies as "Spam" or "Not Spam" based on a threshold (default: 0.7).
- Highlights influential words in the text editor using colored tags.

---

## 🛠️ Technologies Used
- **C++**
- **GTK+ 3** for GUI
- **Custom Hash Maps** for performance comparison

---

## 🗂️ File Structure
- `spam_classifier.cpp`: Main program with GUI, classification logic, and data structure implementations.
- `final.csv`: Dataset (should be a transposed CSV with "Word", "Spam Frequency", and "Ham Frequency" rows).

---

## 🚀 How to Run

### 1. Install GTK dependencies (Linux):
```bash
sudo apt install libgtk-3-dev
