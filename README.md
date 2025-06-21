# 🧠 Customer Segmentation & Business Recommendations

This is an interactive **Streamlit web application** that uses **KMeans clustering** to segment customers based on their **Age**, **Work Experience**, and **Family Size**. It also provides personalized **business recommendations** based on the predicted segment.

🔗 **Live Demo:** [https://customersegmentation-stream.streamlit.app/](https://customersegmentation-stream.streamlit.app/)

---

## 📊 Features

- 📥 User input: Age, Work Experience, Family Size
- 🤖 Predicts customer segment using a trained **KMeans model**
- 🧾 Displays segment-specific **profile and business strategy**
- 📈 3D Visualization of user input against cluster centers using **Plotly**

---

## 📦 Tech Stack

- **Frontend:** Streamlit
- **Backend:** Python (scikit-learn, pandas, joblib)
- **Visualization:** Plotly
- **Deployment:** [Streamlit Cloud](https://streamlit.io/cloud)

---

## 🚀 How to Run Locally

### 1. Clone the repository
'''bash
git clone https://github.com/your-username/customer-segmentation-app.git
cd customer-segmentation-app

----------------------------------------------------
Install dependencies
    
    
->pip install -r requirements.txt

----------------------------------------------------------
Run the app
    
    
->streamlit run app.py

-------------------------------------------------------

🧠 Model Details
Scaler: StandardScaler (scaler.pkl)

Clustering Algorithm: KMeans (kmeans_model.pkl)

Trained on normalized customer attributes: Age, Work_Experience, Family_Size

The model segments users into 5 meaningful clusters based on behavioral patterns.

-------------------------------------------------------------------
🎯 Segment Profiles & Recommendations
Cluster	Profile	Business Recommendation

0	Young professionals	Career tools, premium finance

1	Mid-age stable earners	Family bundles, loans

2	Large families with experience	Loyalty offers, education plans

3	Retired / late career	Health, leisure, estate planning

4	Early career starters	Starter kits, gig services

----------------------------------------------------------------------------

🙋‍♂️ Author
Anish Shaw

🔗 LinkedIn (https://www.linkedin.com/in/anish-shaw-2206b8220/?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app/)


📧 Email: sanjayankitanish2013@gmail.com

------------------------------------------------------------------------------

⭐ Acknowledgements

Built using Streamlit

Clustering powered by scikit-learn
