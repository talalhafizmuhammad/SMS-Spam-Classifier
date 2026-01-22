# 📧 Email/SMS Spam Classifier

A simple and interactive **Machine Learning web app** built with **Streamlit** that classifies messages as **Spam 🚫** or **Not Spam ✅** using a trained model and TF-IDF vectorizer.

---

## 🚀 Live Demo
🔗 [View on Streamlit Cloud](https://share.streamlit.io/your-username/sms-spam-classifier)

*(Replace with your actual Streamlit app link after deployment.)*

---

## 🧠 Features
- 🔤 Clean text preprocessing (lowercasing, tokenization, stopword removal, stemming)
- 🧩 Trained ML model using **Scikit-learn**
- 🧰 TF-IDF vectorization for feature extraction
- 💻 Streamlit-based web interface
- ⚡ Real-time spam detection with a single click

---

## 🧾 Tech Stack
| Component       | Technology |
|-----------------|------------|
| Language        | Python     |
| Web Framework   | Streamlit  |
| Machine Learning| Scikit-learn |
| Text Processing | NLTK       |
| Model Storage   | Pickle     |

---

## 🧪 How It Works
1. User enters a message or email text in the input box.  
2. Text is **preprocessed** (tokenized, cleaned, and stemmed).  
3. Preprocessed text is transformed into a numerical vector using the trained TF-IDF model.  
4. ML model predicts whether the message is **Spam** or **Not Spam**.  

---

## 🧰 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/sms-spam-classifier.git
cd sms-spam-classifier
```
### Install dependencies
```
pip install -r requirements.txt
```
### Run the app
```
streamlit run app.py
```
### Requirements
```
streamlit
scikit-learn
nltk
pandas
numpy
```
