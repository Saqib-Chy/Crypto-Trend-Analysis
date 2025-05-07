# Real-Time Cryptocurrency Trend Analysis

## Project Overview
This project focuses on building a real-time data pipeline to analyze cryptocurrency market trends using big data technologies. The primary goal is to process live market data, detect significant trends, and identify similar cryptocurrencies in real time.

## Key Features
- **Real-Time Data Pipeline:** Utilizes **Apache Kafka** for streaming live cryptocurrency data from the CoinGecko API and processes data using **AWS EMR** for scalable distributed storage.
- **Data Processing Techniques:** Applied **MapReduce** for aggregation, **Reservoir Sampling** for efficient streaming, and **Bloom Filters** for duplicate detection.
- **Advanced Trend Detection:** Implemented **Flajolet-Martin algorithm** for trend estimation and **Locality Sensitive Hashing (LSH)** to identify similar cryptocurrencies.
- **Security and Privacy:** Integrated **Differential Privacy** for data security and **Explainable AI** techniques for enhanced interpretability.

## Technology Stack
- **Big Data Frameworks:** Hadoop, Spark, Kafka
- **Cloud Platforms:** AWS EMR
- **Programming Languages:** Python
- **Libraries:** Pandas, NumPy
- **Visualization Tools:** Matplotlib, Seaborn
