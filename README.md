# 🌾 Drought Phase Prediction App

This Streamlit web application uses machine learning (Random Forest) to predict drought phases based on survey and environmental data. The app also provides interactive visualizations, feature importance, and real-time prediction from user inputs.

🔗 **Live App:** [Streamlit Deployment]([(https://drought-prediction-project.streamlit.app/)])

📂 **Dataset:** Cleaned and preprocessed dataset hosted at:  
[https://github.com/studentofstars/Drought-Prediction/blob/main/data_labels_cleaned.csv](https://github.com/studentofstars/Drought-Prediction/blob/main/data_labels_cleaned.csv)

---

## 📌 Project Description

This project was developed as part of a college mini-project to understand and forecast drought phases in Africa. The dataset contains survey-based features, and the target variable is **Drought Phase Classification**.

**Key Goals:**
- Build a reliable drought prediction model using scikit-learn
- Make drought prediction accessible through a clean UI using Streamlit
- Visualize trends and geospatial insights related to drought occurrences
- Help local decision-makers and communities better prepare for dry periods

---

## 🚀 Features

✅ Upload and process cleaned CSV dataset  
✅ Explore dataset statistics and structure  
✅ Visualize:
- Correlation heatmap
- Spatial drought distribution (Mapbox)
- Interactive pairplots/scatter matrix  

✅ Train Random Forest Classifier  
✅ Evaluate model performance (Accuracy, Classification Report, Confusion Matrix)  
✅ View Feature Importance rankings  
✅ Custom input-based drought prediction via slider form  
✅ Download raw dataset  

---

## 📊 Technologies Used

| Tool           | Purpose                         |
|----------------|----------------------------------|
| Streamlit      | Web App UI                      |
| Pandas         | Data Wrangling                  |
| Seaborn/Matplotlib | Static Visualizations        |
| Plotly         | Interactive Maps & Scatterplots |
| Scikit-learn   | Model Training & Evaluation     |

---

## 🛠 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/studentofstars/Drought-Prediction.git
cd Drought-Prediction

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run Drought_Prediction_App.py
