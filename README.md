Integrated Predictive Analytics Framework for Retail Growth and Customer Insight
As part of my MSc in Computer Science with Data Science, I developed an integrated predictive analytics framework designed to optimise the performance and strategic growth of retail stores. The project united multiple datasets to address critical business challenges in retail including sales forecasting, customer segmentation, inventory planning, and customer sentiment analysis. This end-to-end solution leveraged statistical modelling, machine learning (ML), deep learning (DL), and natural language processing (NLP) to deliver actionable insights, enhance operational efficiency, and inform strategic decision-making.

Project Overview
Retail environments today are data-rich but insight-poor. Businesses face challenges in anticipating sales patterns, understanding customer behaviour, managing inventory, and adapting to customer feedback. My project addressed these challenges using four publicly available datasets:

Historical Retail Sales Data (for forecasting),

Customer Transaction Data (for segmentation),

Inventory & Supply Chain Data (for inventory planning), and

Customer Feedback Reviews (for sentiment analysis).

Each dataset was cleaned, pre-processed, and analysed using modern data science techniques. The artefact followed the CRISP-DM methodology and was built in Python using libraries such as pandas, scikit-learn, Prophet, TensorFlow/Keras, XGBoost, and NLP tools.

1. Sales Forecasting (Retail Sales Dataset)
Objective: Predict future sales to support stock and revenue planning.

Using the historical retail sales dataset, I performed time-series forecasting with two models:

Facebook Prophet: Chosen for its interpretability and effectiveness in capturing seasonality. It achieved a Mean Absolute Error (MAE) of 2.21 and enabled planning for promotional peaks.

LSTM (Long Short-Term Memory) neural network: Deployed using TensorFlow/Keras, LSTM captured non-linear and seasonal dependencies in time-series data, delivering a Root Mean Square Error (RMSE) of 1.84.

The data was resampled into monthly intervals, and missing values were handled appropriately. Exploratory Data Analysis (EDA) was conducted to identify trends, spikes, and holiday effects. These models were compared based on interpretability, accuracy, and responsiveness to changes in the data.

Business Outcome: Retailers can now anticipate high-demand periods, align stock replenishment accordingly, and reduce understocking or overstocking losses.

2. Customer Segmentation (Customer Transaction Dataset)
Objective: Group customers into behavioural clusters for targeted marketing.

Using online transaction data from thousands of customers, I created an RFM (Recency, Frequency, Monetary) model. The RFM features were:

Recency – Days since last purchase

Frequency – Number of transactions

Monetary – Total spending

After scaling and transforming the data, I applied three clustering algorithms:

K-Means Clustering (elbow method and silhouette score for optimal k),

DBSCAN (density-based clustering for anomaly detection), and

Hierarchical Clustering (to visualise customer group hierarchy).

The silhouette score peaked at 0.61, confirming meaningful segmentation. Cluster profiling revealed segments such as “high-value loyal customers,” “one-time buyers,” and “at-risk customers.”

Business Outcome: The segmentation empowered retail marketers to customise promotions, increase retention, and design loyalty programmes for different customer groups.
