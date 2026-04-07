# 🧠 NeuroBarrier-AI

🔗 **Live App:** https://neurobarrier-ai.streamlit.app/

---

## 🚀 Overview

**NeuroBarrier-AI** is an AI-powered web application designed to predict critical drug properties related to the **blood-brain barrier (BBB) permeability** and **aqueous solubility (ESOL)**.

The application enables users to input molecular features and instantly receive predictions using trained machine learning models.

Built using **Python** and deployed with **Streamlit**, this project demonstrates the real-world application of machine learning in **drug discovery and cheminformatics**.

---

## 🎯 Features

* 🧪 **BBBP Prediction**
  Predicts whether a compound can cross the blood-brain barrier.

* 💧 **ESOL Prediction**
  Estimates the solubility of compounds in water.

* ⚡ **Real-time Predictions**
  Instant results through an interactive UI.

* 🌐 **Deployed Web App**
  Accessible from anywhere via browser.

---

## 🧠 Tech Stack

* **Frontend & Deployment:** Streamlit Streamlit
* **Backend:** Python
* **ML Libraries:**

  * scikit-learn
  * NumPy
  * Pandas
* **Model Serialization:** Joblib
* **Version Control:** Git + GitHub

---

## 📂 Project Structure

```
NeuroBarrier-AI/
│── app.py
│── bbbp_model.pkl
│── esol_model.pkl
│── requirements.txt
│── model.ipynb
│── BBBP.csv
│── ESOL.csv
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/NeuroBarrier-AI.git
cd NeuroBarrier-AI
```

---

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 3. Run the App Locally

```bash
streamlit run app.py
```

---

## 📊 How It Works

1. User selects the prediction type (BBBP or ESOL)
2. Inputs molecular features
3. The trained ML model processes the input
4. Prediction is displayed instantly on the UI

---

## 🧪 Models Used

* **BBBP Model:** Classification model for blood-brain barrier permeability
* **ESOL Model:** Regression model for solubility prediction

Both models are trained using curated datasets and optimized for performance.

---

## 🌍 Deployment

This app is deployed using **Streamlit Cloud**, which allows quick and free deployment of ML apps directly from GitHub. ([Medium][1])

---

## 📌 Future Improvements

* 🔬 SMILES input support using RDKit
* 📈 Model performance visualization
* 🧠 Deep learning-based models
* 📦 API integration for scalability

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

## 📬 Contact

**Abhinav Mishra**

* GitHub: https://github.com/your-username
* LinkedIn: (add your profile)

---

## ⭐ Acknowledgements

* Streamlit for rapid ML app deployment
* Open-source ML community

---

## 📄 License

This project is open-source and available under the MIT License.

---

[1]: https://medium.com/%40abuzar_mahmood/let-ai-do-the-work-a-k-a-rapid-deployment-using-streamlit-apps-0d290aa6908d?utm_source=chatgpt.com "Let AI do the work a.k.a. Rapid deployment using Streamlit ..."
