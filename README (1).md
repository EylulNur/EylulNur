<div align="center">

<img src="assets/cv-banner.svg" alt="Eylül Nur — Cybersecurity Analyst" width="100%"/>

<br/>

<a href="https://linkedin.com/in/EylulNur"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
<a href="mailto:mail@ornek.com"><img src="https://img.shields.io/badge/Email-6366F1?style=flat-square&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/EylulNur?tab=followers"><img src="https://img.shields.io/github/followers/EylulNur?style=flat-square&logo=github&color=111827"/></a>

</div>

<br/>

## 👋 About Me

I'm a **3rd-year Management Information Systems (MIS) student** focusing on **cybersecurity analytics and threat monitoring**. I'm interested in how raw network telemetry becomes actionable security insight, and I learn best through hands-on projects that go beyond basic CSV filtering: structuring log data in SQL, finding the metrics that actually separate attacks from normal traffic, and presenting them in SOC-style dashboards.

- 🎓 **Management Information Systems (Yönetim Bilişim Sistemleri)**, 3rd-year undergraduate at **Arel University**, İstanbul
- 🤝 **Open to internship opportunities** in cybersecurity, SOC, and data analytics
- 🔭 Currently working on: **SOC Threat Intelligence & Network Traffic Analysis**
- 🌱 Learning: **threat detection, anomaly analysis, SOC dashboards**
- 🛡️ Interested in: **SOC / blue team, threat intelligence, security & data analytics**
- 📍 **İstanbul, Türkiye**

---

## 🧰 Tech & Skills

| Area | Tools |
|------|-------|
| **Languages & Data** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) |
| **Visualization & BI** | ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) ![DAX](https://img.shields.io/badge/DAX-6366F1?style=flat-square) ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square) |
| **Security Focus** | ![SOC](https://img.shields.io/badge/SOC_Monitoring-0F172A?style=flat-square&logo=hackthebox&logoColor=22D3EE) ![Threat Intel](https://img.shields.io/badge/Threat_Intelligence-F43F5E?style=flat-square) ![Network Analysis](https://img.shields.io/badge/Network_Traffic_Analysis-22D3EE?style=flat-square&logoColor=black) ![CICIDS2017](https://img.shields.io/badge/CICIDS2017-475569?style=flat-square) |
| **Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white) |

---

## 🏅 Certifications

<a href="https://www.coursera.org/"><img src="https://img.shields.io/badge/IBM-Introduction_to_Cybersecurity_Careers-052FAD?style=for-the-badge&logo=ibm&logoColor=white" alt="IBM Introduction to Cybersecurity Careers"/></a>
<img src="https://img.shields.io/badge/via_Coursera-0056D2?style=for-the-badge&logo=coursera&logoColor=white" alt="Coursera"/>

---

## 🛡️ Featured Project

### [SOC Threat Intelligence & Network Traffic Analysis](https://github.com/EylulNur/ai-cybersec-dashboard)

I built this project to analyze network flow anomalies and tell **DDoS attack patterns apart from legitimate traffic** using the **CICIDS2017** dataset. It combines a local SQLite database, Python for anomaly visualization, and custom DAX measures designed for SOC monitoring dashboards.

<div align="center">
<img src="assets/soc-findings.svg" alt="DDoS vs Benign key findings" width="90%"/>
</div>

**Key findings**

- 📦 DDoS flows carry larger packets on average (**822.6 B** vs **249.7 B**), roughly **3.3×** higher.
- ⏱️ The median DDoS flow lasts **1.88 s** vs **0.17 s** for benign traffic. Means are similar (~15.3M vs ~17.0M µs), so skewed outliers matter when comparing.
- ⚖️ 56.7% of the 225,711 analyzed flows are DDoS and 43.3% benign. This reflects the dataset sample, not a real-world ratio.

**How it works**

| Layer | What it does |
|-------|--------------|
| `sql/` | Cleans raw logs and ingests them into SQLite (`cybersecurity.db`) to simulate connection-log indexing |
| `src/visualize.py` | Queries flow records with Pandas, computes volume distribution, plots packet metrics with Seaborn |
| `docs/` | Documented DAX formulas (attack ratios, discrepancy indexing) ready for Power BI SOC dashboards |

<details>
<summary><b>▶ How to run</b></summary>

```bash
git clone https://github.com/EylulNur/ai-cybersec-dashboard.git
cd ai-cybersec-dashboard
pip install pandas matplotlib seaborn
python3 src/visualize.py
```

The chart is saved to `reports/figures/soc_traffic_overview.png`.

</details>

<div align="center">

<a href="https://github.com/EylulNur/ai-cybersec-dashboard"><img src="https://github-readme-stats.vercel.app/api/pin/?username=EylulNur&repo=ai-cybersec-dashboard&theme=tokyonight&hide_border=true"/></a>

</div>

---

## 📊 GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=EylulNur&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=EylulNur&layout=compact&theme=tokyonight&hide_border=true" alt="langs"/>

</div>

---

<div align="center">

**Let's talk security analytics.** → [Email](mailto:mail@ornek.com) · [LinkedIn](https://linkedin.com/in/EylulNur)

</div>
