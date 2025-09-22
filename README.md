# 🤖 AI-Powered Phishing Detection System  

## 📌 Project Description  
The **AI-Powered Phishing Detection System** leverages **machine learning and natural language processing (NLP)** to identify and classify phishing emails.  
Using **Scikit-learn** and **NLTK**, the system analyzes email subjects, body content, and sender patterns to determine whether an email is **phishing** or **legitimate**.  

To extend its functionality, the system integrates with the **Ironscales API** and **Microsoft Graph API**, enabling automated analysis of **M365 mailbox threats**.  

---

## 🚀 Impact  
- Enhanced **email security** by automatically classifying phishing attempts with high accuracy.  
- Reduced **manual investigation time** through automated detection workflows.  
- Strengthened **M365 threat response** by integrating with mailbox APIs for proactive scanning.  
- Provided a **scalable and adaptable** solution for enterprise security operations.  

---

## 🛠️ Tech Stack  
- **Python** – Core development language.  
- **Scikit-learn** – Machine learning model training and classification.  
- **NLTK** – Natural Language Processing for email text analysis.  
- **Ironscales API** – Integration for advanced phishing threat intelligence.  
- **Microsoft Graph API** – Automated mailbox scanning and incident analysis.  
- **M365** – Primary email environment for deployment.  

---

## 🏗️ Architecture Overview  
1. **Data Collection**  
   - Emails ingested from **M365 mailboxes** via **Microsoft Graph API**.  
   - Threat intelligence enrichment through **Ironscales API**.  

2. **Preprocessing & Feature Engineering**  
   - Tokenization, stopword removal, and text normalization using **NLTK**.  
   - Feature extraction from **subject lines, body text, and sender metadata**.  

3. **Machine Learning Model**  
   - Trained classification model using **Scikit-learn** (e.g., Logistic Regression, Random Forest, or SVM).  
   - Model predicts whether an email is *Phishing* or *Legitimate*.  

4. **Automated Response**  
   - Detected phishing attempts flagged in **M365 mailboxes**.  
   - Alerts and incident data pushed into SOC tools or dashboards.  

---

## ✨ Key Features  
- **ML-Based Detection** – Classify phishing vs. legitimate emails using subject, body, and sender patterns.  
- **NLP-Powered Analysis** – Clean and process email text for accurate predictions.  
- **Mailbox Integration** – Scan and analyze real-time M365 email data.  
- **Threat Intelligence Enrichment** – Combine model results with **Ironscales threat data**.  
- **Automation Ready** – Seamlessly integrates into enterprise SOC workflows.  

---

## 📖 Getting Started  

### 🔧 Prerequisites  
- Python 3.8+  
- M365 account with Microsoft Graph API access.  
- Ironscales API key.  
- Required Python packages:  
  ```bash
  pip install scikit-learn nltk requests pandas
