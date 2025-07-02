🪑 Smart Furniture Sales Analyzer

📌 Project Summary
Smart Furniture Sales Analyzer is a beginner-friendly data analytics project using an e-commerce furniture dataset. It helps sellers understand how price and shipping options influence sales, and provides a live sales prediction tool based on product details like title, price, and shipping type.

Built with Python, Streamlit, pandas, scikit-learn, and a sprinkle of data magic ✨

🎯 Features
📊 Interactive Dashboard: Visual insights on price bins, shipping type, and keywords that boost sales.

🤖 Live Prediction App: Predict how many units your product might sell.

🧠 Keyword Intelligence: Discover buzzwords commonly found in top-selling product titles.

🧪 Built-in ML Models: Random Forest Regressor & Classifier used for predictions.

📁 Dataset Overview
📌 Source: AliExpress (scraped via Apify)

🪑 Products: 2,000+ furniture items

📦 Columns: productTitle, price, sold, tagText

⚠️ Note: originalPrice column was dropped due to missing values

🚀 How to Run the Project
1. Clone or Download this repo
git clone https://github.com/your-username/furniture-sales-analyzer.git
cd furniture-sales-analyzer
2. Install required libraries
pip install -r requirements.txt
3. Launch the Streamlit app
streamlit run app.py
Or (if streamlit command isn't recognized):
    python -m streamlit run app.py

🔍 File Structure
📦 furniture-sales-analyzer
ecommerce_furniture_dataset_2024.csv
app.py
requirements.txt
README.md                            

📊 Screenshots 

![Screenshot 2025-07-02 191638](https://github.com/user-attachments/assets/032ee9ea-5038-4468-8465-9ed8e5531498)


![Screenshot 2025-07-02 191733](https://github.com/user-attachments/assets/d4519bc2-d439-4857-8a1a-507246f8527a)



💡 Future Ideas
🧾 Add a downloadable report (PDF or CSV)

🧠 Improve model with advanced NLP (e.g., BERT for product titles)

🌐 Deploy on Streamlit Cloud or Hugging Face Spaces

