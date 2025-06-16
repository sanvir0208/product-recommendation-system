# 🛒 Personalized Product Recommendation System

An end-to-end hybrid recommender system built using transactional and demographic data from Horizon Hobby. This project combines collaborative filtering, content-based modeling, and business logic to generate real-time, personalized product suggestions.

> 📍 **Built in Python | Modeled in Jupyter | Fully deployable**

---

## 🎯 Objective

To improve customer retention and conversion rates by delivering context-aware product recommendations. This system leverages customer demographics, transaction history, and product metadata to drive personalized discovery, uplift loyalty, and maximize ROI.

---

## 🧱 Solution Architecture

- **Data Modeling**: Star schema with fact + dimension tables (transactions, products, customers, dates, promotions)
- **Feature Engineering**: Loyalty tiering, RFM, purchase recency, promotion exposure, seasonality
- **Modeling Stack**:
  - Global & Segmented Popularity (baselines)
  - Matrix Factorization using ALS (implicit feedback)
  - Content-based similarity (TF-IDF + user profiles)
  - Hybrid Recommender (weighted ensemble of above)
- **Evaluation**: Precision@5, Recall@5, NDCG@5 across user segments
- **Deployment Ready**: FastAPI pipeline (proposed), batch inference + schema for frontend integration

---

## 🧠 Key Modules

| Module | Description |
|--------|-------------|
| 🧹 Data Preprocessing | Merged customer, product, promo, and transaction tables |
| 📊 User Segmentation | Loyalty tiering, gender/age breakout |
| 🔄 Collaborative Filtering | ALS-based user-product matrix with cold-start fallback |
| 🧾 Content-Based Modeling | Cosine similarity on TF-IDF vectors |
| ⚙️ Hybrid Strategy | Weighted blend of collaborative + content-based scores |
| 📈 Evaluation Dashboard | NDCG, Precision@5, Recall@5 by loyalty, age group, promo exposure |

---

## 📊 Evaluation Results

| Model               | Precision@5 | Recall@5 | NDCG@5 |
|--------------------|-------------|----------|--------|
| Global Popularity   | 0.035       | 0.082    | 0.044  |
| Segmented Popularity| 0.045       | 0.095    | 0.052  |
| ALS Collaborative   | 0.072       | 0.162    | 0.094  |
| Hybrid Model      | **0.084**   | **0.177**| **0.108** |

---

## 🧪 Files Included

- `DS_FINAL.ipynb` – Jupyter Notebook with full EDA, modeling, and evaluation
- `Data science Report.docx` – Business-facing narrative summary
- `Personalized Product Recommendation System.pptx` – Executive pitch deck
- `requirements.txt` – Python dependencies
- `README.md` – This file

---

## 👨‍💻 Author

**KANNETI NAGA SHIVA SAI RAM KOUSHIK**  
🎓 MS in Business Analytics, University of Illinois Urbana-Champaign  
📫 koushikkanneti123@gmail.com   
🔗 [LinkedIn](https://www.linkedin.com/in/koushik-k-796900202/) • [GitHub](https://github.com/Koushik-kanneti)

---

## 💼 Why This Project Matters

This project demonstrates:
- ✳️ End-to-end ML system design from data wrangling to API planning
- 🔀 Strong hybrid modeling expertise (ALS + TF-IDF)
- ⚙️ MLOps awareness through pipeline planning and segment-wise evaluation
- 🧠 Business alignment with promotions, loyalty tiers, and margin-aware filtering

> Note: This is a production-style recommender system built from scratch with a strong balance of business impact and machine learning rigor.

---

## 🔧 Skills Highlighted

`Python` · `Pandas` · `scikit-learn` · `ALS` · `TF-IDF` · `Cosine Similarity` · `MLOps` · `Data Wrangling` · `Customer Segmentation` · `Model Evaluation` · `Collaborative Filtering` · `Content-Based Filtering`

