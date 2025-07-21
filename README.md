Salary Predictor App


This is a machine learning-based web application that predicts an individual's salary based on various inputs. The application is built using Streamlit and uses a pre-trained LightGBM model for salary prediction.

🔍 Features
Clean and interactive user interface using Streamlit

Salary prediction powered by LightGBM

Easy-to-use sliders and input fields

Deployed-ready Python code and model integration

📁 Project Structure
bash
Copy
Edit
salary_predector_app-main/
│
├── streamlit_app.py              # Streamlit app script
├── salarypredector.ipynb         # Jupyter notebook for model training and experimentation
├── model_lightgbm_v2.pkl         # Pre-trained LightGBM model
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
🚀 Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/salary_predector_app.git
cd salary_predector_app
2. Create a Virtual Environment (Optional but recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Run the Streamlit App
bash
Copy
Edit
streamlit run streamlit_app.py
📊 Model Information
The app uses a LightGBM model (model_lightgbm_v2.pkl) trained to predict salary using features processed in the accompanying Jupyter notebook. You can retrain or tweak the model using salarypredector.ipynb.

🧾 Requirements
All required packages are listed in requirements.txt. Key libraries include:

streamlit

pandas

lightgbm

scikit-learn


📬 Contact

Name: Leevanshu

LinkedIn: www.linkedin.com/in/leevanshu


