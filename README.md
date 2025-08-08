# WUDAC 2025 Datathon: User Segmentation & Uplift Modeling

**What**  
Segmented 16 M+ sessions into four personas (K-means) and built an XGBoost model to predict high-value users, driving 28 % lift in conversions and 2.6× ROI.

**How**  
1. **Data prep**: cleaned and feature-engineered session/transaction data  
2. **Clustering**: K-means to define four user personas  
3. **Modeling**: trained XGBoost classifier on labeled cohorts  
4. **Evaluation**: measured ROC-AUC (0.87) and lift/ROI on top decile  

**Tech**  
- Python 3.9+  
- Pandas, NumPy  
- scikit-learn, XGBoost  
