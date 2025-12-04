RetailPredict 360 – AI Store Intelligence

RetailPredict 360 is a lightweight yet powerful machine-learning suite designed for modern retail analytics.
It combines three core predictive business models under one unified system:

📈 Store Footfall Forecast

🚚 Delivery Time Prediction

💰 Customer Lifetime Value (CLV) Prediction

The project includes:

✔️ A console app

✔️ A modern Flask web app with 3D cards and AI/AR-inspired UI

🚀 Tech Stack

Languages & Libraries

Python

Pandas, NumPy

scikit-learn, joblib

Flask + Bootstrap

Matplotlib / Seaborn (optional for EDA)

🤖 Models Overview
1. Footfall Forecasting

Predicts daily store visitor count
Used for staffing, inventory, and sales planning.

2. Delivery Time Prediction

Predicts delivery ETA in minutes
Useful for logistics efficiency and route optimization.

3. CLV Prediction

Predicts 12-month Customer Lifetime Value (High / Medium / Low)
Enables segmentation and targeted retention strategies.

⚙️ How to Run the Project
🔹 1. Install Dependencies

Run in CMD / Terminal / Anaconda Prompt:

pip install numpy pandas matplotlib seaborn scikit-learn flask joblib

🔹 2. Prepare (Clean) the Data

This step generates cleaned datasets for training.

python prepare_data.py

🔹 3. Train All Three Models

This will generate the model .pkl files:

python train_models.py


Output files:

footfall_model.pkl  
delivery_model.pkl  
clv_model.pkl  

🔹 4. Run the Flask Web App

Start the animated 3D-card interface:

python web_app.py


Then open in your browser:

http://localhost:5000

🧠 Business Applications
✔️ Footfall Forecast

Staff scheduling

Stock & replenishment planning

Peak hour strategy

✔️ Delivery Time Prediction

Route optimization

Operations SLAs

Last-mile efficiency

✔️ CLV Prediction

Loyalty personalization

High-value customer targeting

Marketing ROI optimization
