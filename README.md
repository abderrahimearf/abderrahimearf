# <p align="center">🚀 Abderrahim ARFAOUI</p>
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=24&pause=1000&color=00D1FF&center=true&vCenter=true&width=700&lines=Data+Engineer+🛠️;Élève+Ingénieur+@+EMI+🎓;GenAI+%26+RAG+Architect+🧠;BI+%26+Data+Governance+Expert+📊" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/abderrahim-arfaoui-25534a2b7"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:arfaouiabderrahim061@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

## 👨‍💻 À propos
Élève Ingénieur en 3ème année à l'**École Mohammadia d'Ingénieurs (EMI)**. Je me spécialise dans la création d'architectures de données robustes, le déploiement de pipelines automatisés et la conception d'agents IA à fort impact métier.

- 🏆 **Distinction :** 2ème Place au **Orange Challenge** (53 équipes).
- 🔬 **Recherche :** Auteur d'une publication scientifique sur la **Modélisation Multiphysique**.
- ⚡ **Impact :** Réduction du cycle de réponse business de **3 jours à 4 heures** via GenAI.

---

## 🛠️ Expertise Technique

### 🏗️ Data Engineering & Infrastructure
<p align="left">
  <img src="https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/SSIS-B8D432?style=for-the-badge&logo=microsoft-sql-server&logoColor=black" />
</p>

### 🧠 Data Science & AI Layer
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black" />
</p>

---

## 🏗️ Projet Focus : Architecture Medallion (Olist)
*Un pipeline complet de bout en bout orchestré par Airflow et transformé par dbt.*

```mermaid
graph LR
    subgraph Ingestion
    A[Bronze: Raw Data] --> B[Docker/PostgreSQL]
    end
    subgraph Transformation
    B --> C[Silver: Cleaned & Typed]
    C --> D[Gold: Star Schema / Marts]
    end
    subgraph Exploitation
    D --> E[ML Layer: K-Means/Recommender]
    D --> F[BI: Power BI Insights]
    end
    style C fill:#f9f,stroke:#333,stroke-width:2px
    style D fill:#00D1FF,stroke:#333,stroke-width:4px
