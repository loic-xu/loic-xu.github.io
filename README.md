# 🌐 Loïc Xu — Portfolio & Site Personnel

[![Website](https://img.shields.io/badge/Website-loic--xu.github.io-0969da?style=flat&logo=githubpages&logoColor=white)](https://loic-xu.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-loic--xu-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/loic-xu/)
[![GitHub](https://img.shields.io/badge/GitHub-loic--xu-181717?style=flat&logo=github&logoColor=white)](https://github.com/loic-xu)

Portfolio technique et vitrine professionnelle de **Loïc Xu**, Data & AI Engineer.  
Ingénieur diplômé de l'**ENSIIE** (spécialisation Data / IA) et titulaire d'un **Master 2 Data Science à l'Université Paris-Saclay**.

🔗 **Accéder au site : [loic-xu.github.io](https://loic-xu.github.io)**

---

## 🎯 Philosophie & Conception

Ce site a été conçu avec une approche volontairement sobre, rapide et orientée ingénierie :
- **Zéro surcharge / Zéro framework lourd :** Pages statiques pures (HTML5 / Tailwind CSS) garantissant un chargement instantané (< 100 ms) et un score de performance Lighthouse optimal.
- **Dark theme minimaliste :** Palette sobre inspirée des standards de GitHub (`#0d1117`), typographie technique soignée (*Inter* & *JetBrains Mono*) et absence totale d'artifices superflus.
- **Contenu axé sur l'impact technique :** Présentation des projets orientée sur les **problèmes réels résolus**, les arbitrages d'architecture et les résultats mesurables.

---

## 📑 Structure du Site

| Page | Description |
| :--- | :--- |
| **[`index.html`](https://loic-xu.github.io/)** | **Accueil & Synthèse :** Positionnement d'ingénieur, parcours professionnel (Sanofi, ANSSI, Prorizon AI) et sélection des réalisations clés. |
| **[`projets.html`](https://loic-xu.github.io/projets.html)** | **Fiches Techniques Détaillées :** Analyse approfondie de chaque projet (contexte métier, architecture, captures d'écrans et accès aux dépôts de code). |
| **[`cv.html`](https://loic-xu.github.io/cv.html)** | **Parcours & Compétences :** Détail des missions en entreprise, formation d'ingénieur ENSIIE / Paris-Saclay et matrice des compétences techniques. |

---

## 🚀 Projets Présentés

| Projet | Domaine | Stack Technique | Description |
| :--- | :--- | :--- | :--- |
| **[RailTrack](https://github.com/loic-xu/rail-track)** | Data Engineering | DuckDB, Polars, dbt, Airflow, Docker, Streamlit | Transit Lakehouse temps réel ingérant les flux IDFM des 5 lignes RER (3,4M trajets/jour) avec compaction nocturne et modélisation en étoile Kimball. |
| **[Assistant Documentaire](https://github.com/loic-xu/RAG)** | GenAI & Vector Search | Python, LangChain, Weaviate, Ragas | Pipeline RAG de production avec recherche hybride (BM25 + Dense), réordonnancement (HyDE, Reranking) et évaluation continue sans hallucination. |
| **[BabyStats](https://babystats.pages.dev/)** | Data Engineering & Web *(En ligne)* | Architecture Médaillon, Jamstack, Playwright, Cloudflare | Plateforme d'analytics des tournois officiels de baby-foot : empreinte web réduite de 2,7 Go à < 250 Mo et moteur de face-à-face instantané. |
| **[Job Tracker](https://github.com/loic-xu/job-tracker)** | Software Engineering | FastAPI, Pydantic v2, Chrome MV3, CSV Local | Extension Chrome et backend local-first pour capturer et centraliser les candidatures sans fuite de données personnelles. |
| **[Classification Simpsons](https://github.com/loic-xu/simpson-classification-simCLR)** | Deep Learning / Vision | PyTorch, SimCLR, Apprentissage Contrastif | Benchmark sur données faiblement annotées démontrant un gain de +13,4 points d'accuracy (+40 % relatif) via l'apprentissage auto-supervisé. |

---

## 💻 Exécution en Local

Pour tester ou modifier le site localement :

```bash
# Cloner le dépôt
git clone https://github.com/loic-xu/loic-xu.github.io.git
cd loic-xu.github.io

# Lancer le serveur local
python3 -m http.server 8000
```

Accéder ensuite à : [http://localhost:8000](http://localhost:8000)

---

## 📬 Contact & Liens Professionnels

- **LinkedIn :** [linkedin.com/in/loic-xu](https://www.linkedin.com/in/loic-xu/)
- **GitHub :** [github.com/loic-xu](https://github.com/loic-xu)
- **Localisation :** Paris, France
