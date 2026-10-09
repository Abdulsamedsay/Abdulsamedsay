<h1 align="center">Hey, I'm Samed 👋</h1>

<p align="center">
  <a href="https://github.com/Abdulsamedsay">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&width=640&lines=AI+student+%40+Radboud+University;Building+end-to-end+ML+systems;Shipping+automation+pipelines+in+production;data+%E2%86%92+model+%E2%86%92+deployment" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/samed-say-754981392/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:sameddsayy@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=Abdulsamedsay&style=for-the-badge&color=58A6FF&label=PROFILE+VIEWS" />
</p>

---

```python
class Samed:
    role      = "BSc Artificial Intelligence @ Radboud University"
    extra     = "Radboud Honours Academy"
    location  = "Nijmegen, NL"
    currently = [
        "Automation & AI Working Student @ Kodros",
        "Intern @ ASML",
    ]
    previously = ["TA, Human-Centered Design @ Radboud", "Mechanical Engineering @ ESTU"]
    focus     = ["ML engineering", "training pipelines", "computer vision for manufacturing"]
    next_step = "MSc @ ? "

    def motto(self):
        return "If it doesn't run end-to-end, it's not done."
```

---

## 🚀 Featured: Wafer Defect Detection & Yield Risk Dashboard

End-to-end CV pipeline for semiconductor quality control.

```
WM-811K (172,950 wafer maps, 9 classes)
   └─▶ PyTorch CNN  ──▶  Grad-CAM heatmaps
          └─▶ yield-risk scoring (Low / Medium / High / Critical)
                 └─▶ Streamlit app with live inference
```

- **Macro F1 0.686** (+0.134 over a logistic regression baseline) on a heavily imbalanced dataset
- **Grad-CAM** to show *where* the model looks, not just what it predicts
- Risk layer that turns class probabilities into something an engineer can act on

[![Live demo](https://img.shields.io/badge/▶_Live_demo-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://wafer-defect-detection-dashboard-jbxkmaiauhllreewbzctav.streamlit.app)
[![Source](https://img.shields.io/badge/Source-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Abdulsamedsay/wafer-defect-detection-dashboard)

---

## ⚙️ In production: Lead Automation Pipeline @ Kodros

A 9-workflow n8n system that replaced manual lead entry for a recruitment company.

```
Meta Ads ─┐
LinkedIn ─┼─▶ webhooks (HMAC verified) ─▶ dedup + quality filter ─▶ classify & route
TikTok ───┘        OAuth2 token refresh        (Postgres / Supabase)        │
                                                                            ▼
                         OpenAI lead scoring (HOT / WARM / NURTURE) ◀── Bullhorn CRM
                                                                            │
                                                              personalized outreach email
```

- Integrated **6+ external APIs**: Meta Graph API, LinkedIn Advertising API, TikTok Business API, Bullhorn, OpenAI
- **Zero human intervention per lead**: ingestion, deduplication, owner assignment and outreach run fully automatically
- **LLM-based scoring** of candidates from intake forms, run on a schedule to drive follow-up priority
- Lead a small student automation team and translate pipeline decisions for non-technical stakeholders

---

## 🛠️ Stack

<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,haskell,postgres,supabase,git,github,linux,vscode,latex&theme=dark" />
</p>

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat&logo=openai&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

| Area | What I work with |
|---|---|
| **Deep Learning** | CNNs, Grad-CAM, imbalanced classification, model evaluation |
| **Classic ML** | Logistic regression from scratch, scikit-learn, predictive modeling |
| **NLP / LLMs** | Tokenization, n-gram LMs, perplexity, LLM-based classification |
| **Automation** | n8n, REST APIs, webhooks, OAuth2, HMAC, data pipelines |
| **Other** | Functional programming (Haskell), reinforcement learning |

---

## 📂 Other work

| Repo | What it does | Stack |
|---|---|---|
| `NLP-course-assignments` | Tokenization, bigram LMs, perplexity | Python · NLTK |
| `knowledge-based-ai-projects` | Circuit diagnosis via conflict sets & hitting sets | Python |
| `from-data-to-model-ml` | Logistic regression from scratch + evaluation metrics | Python · NumPy |
| `research-summaries` | Literature reviews, conceptual maps | LaTeX |

---

## 📊 Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Abdulsamedsay&theme=github-dark-blue&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Abdulsamedsay&theme=github-compact&hide_border=true" />
</p>

<p align="center"><sub>🇳🇱 🇹🇷 · Turkish (native) · English (C2) · Dutch (B1)</sub></p>
