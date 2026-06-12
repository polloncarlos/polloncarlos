# Carlos Pollon

**Data Scientist** — projetos end-to-end com foco em impacto de negócio real.


[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carlos-pollon)
[![Portfolio](https://img.shields.io/badge/Portfólio-000000?style=for-the-badge&logo=github&logoColor=white)](https://polloncarlos.github.io/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:carlos.pollon0015@gmail.com)

---

## Projetos em Destaque

### 🔁 PA006 — Churn Prediction + A/B Testing + Uplift Modeling
**Pipeline de retenção de 3 camadas com deploy em Streamlit**

Solução end-to-end para um e-commerce B2C de 4.300 clientes: **Camada 1** — XGBoost + Optuna (50 trials) + calibração sigmoid, ROC-AUC 0,776, threshold 0,20 definido pela relação FN/FP de 7×. **Camada 2** — Teste A/B (χ²=6,96, p=0,008), ARR 7,6%, ROI 51,7% por ciclo. **Camada 3** — T-Learner com Logistic Regression; CATE individual por cliente; segmentação em 4 perfis (Persuadible, Sure Thing, Lost Cause, Sleeping Dog).

**Resultado de negócio:** top-200 Persuadibles com CATE médio 0,153 e ROI projetado de 221,5%. Dashboard interativo para time de negócio com download Excel e filtro de budget.

🔗 [Repositório](https://github.com/polloncarlos/churn_ab_uplift_pipeline) · [Dashboard](https://churnabupliftpipeline-s.streamlit.app/)

---

### 🎯 PA005 — Customer Value Segmentation
**Clusterização de clientes de e-commerce com deploy em AWS**

Pipeline end-to-end de segmentação não supervisionada: feature engineering com 17 variáveis comportamentais, comparação experimental entre KMeans, GMM, H-Clustering e DBSCAN (com embeddings via Random Forest + UMAP), Silhouette Score de **0.72**, e deploy produtivo em EC2 + RDS PostgreSQL + Metabase.

**Resultado de negócio:** identificação de 35 clientes VIP (0,8% da base) responsáveis por 24% da receita total, e 1.200 clientes em risco de churn.

🔗 [Repositório](https://github.com/polloncarlos/customer_value_segmentation)

---

### 📈 PA004 — Health Insurance Cross-Sell Ranking
**Ranqueamento de clientes por propensão à compra**

Solução de Learning to Rank para priorizar clientes com maior probabilidade de contratar seguro veicular. Modelos Random Forest e XGBoost avaliados com Gain@K, Lift@K e NDCG. Estimativa de uplift financeiro e integração com Google Sheets via API em Flask.

🔗 [Repositório](https://github.com/polloncarlos/health_insurance_ranking)

---

### 📦 PA003 — Rossmann Sales Forecast
**Previsão de vendas end-to-end com deploy via Telegram**

Modelo XGBoost com seleção de features via Boruta + ExtraTrees e tuning com Optuna, otimizado para ambiente com restrição de memória (512 MB). Deploy como API Flask com bot no Telegram para consulta de previsões por loja.

🔗 [Repositório](https://github.com/polloncarlos/rossmann_sales_predict)

---

## 🧠 Tech Stack

| Categoria | Ferramentas |
|-----------|-------------|
| **Linguagem** | Python 3.11 |
| **Machine Learning** | Scikit-learn, XGBoost, UMAP, Optuna |
| **Data** | Pandas, NumPy, SQLAlchemy |
| **Cloud** | AWS EC2, S3, RDS |
| **Banco de Dados** | PostgreSQL, MySQL |
| **Dashboards** | Metabase, Streamlit Cloud |
| **Deploy** | Flask, API REST |
| **Ambiente** | Jupyter Notebook, VSCode |

---

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=polloncarlos&show_icons=true&theme=tokyonight)](https://github.com/polloncarlos)
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=polloncarlos&layout=compact&theme=tokyonight)](https://github.com/polloncarlos)
