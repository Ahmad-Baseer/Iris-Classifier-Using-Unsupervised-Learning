---
title: Iris Classifier Using Unsupervised Learning
emoji: 👁
colorFrom: indigo
colorTo: green
sdk: streamlit
sdk_version: 1.39.0
app_file: app.py
pinned: false
---

Status Badge: [![Sync to Hugging Face hub](https://github.com/Ahmad-Baseer/Iris-Classifier-Using-Unsupervised-Learning/actions/workflows/CD_to_HuggingFace.yml/badge.svg)](https://github.com/Iris-Classifier-Using-Unsupervised-Learning/actions/workflows/CD_to_HuggingFace.yml/)

# How to run the application

1. Download all the files and place them in a specific folder. Open up Vs code in that folder.
2. Install the required libraries using this command: ```pip install -r requirements.txt```
3. Run the **Prediction_Using_Unsupervised_Learning** file first and then **prediction_helper**.
4. Open up the terminal in the same folder and type this command: ```streamlit run app.py```. It will open your application in your default browser.
5. Now you can follow any YouTube video to deploy this application.
6. You can use my application here: [Iris-Classifier-Using-Unsupervised-Learning](https://huggingface.co/spaces/AhmadHashim/Iris-Classifier-Using-Unsupervised-Learning)

# Project Working
📊 Exploratory Data Analysis (EDA): I started by loading the Iris dataset from the scikit-learn library and performed EDA. Thankfully, there were no missing values, making it a high-quality dataset that didn't require data cleaning.

🔗 Feature Selection: To avoid multicollinearity, I initially considered selecting only one feature from petal width and length. However, this resulted in lower accuracy. I later retained all features, which significantly improved the model's performance.

📈 Cluster Analysis: While plotting graphs, I analyzed the relationship between petal width and length and discovered that there should be 2 or 3 optimum clusters.

📉 Finding Optimum Clusters: I employed the elbow method and silhouette score to determine the optimal number of clusters. The results are remarkable, as shown in the comparison, highlighting the effectiveness of the model's classification.

🚀 Exporting the Model: Finally, I exported the model, making it ready for use in a Streamlit application.

🌐 Model Deployment: I extended the project by adding a user-friendly frontend, enhances the experience using custom css and dynamic animations provided by lottie files. Users can input all four features, and the model classifies the Iris species using two methods: Euclidean distance from each data point and distances from cluster centers.

## Thanks for reading
