# AI/ML Formation Parcours vers AI/ML Engineer

Dépôt de suivi de ma formation en Machine Learning et Deep Learning, dans l'objectif de devenir AI/ML Engineer. Développeur web full stack de formation, je documente ici chaque étape : exercices, projets de synthèse par phase, et notes techniques.

## Objectif

Acquérir en environ 30 semaines les compétences fondamentales en ML/DL et une spécialisation NLP/LLMs, avec un accent particulier sur les projets combinant développement web et IA (RAG, agents, applications déployées).

## État actuel du dépôt

Pour l'instant tout le travail est centralisé dans `main.ipynb` (Phase 1 — Python data science, Semaine 1 : NumPy et Pandas, exercices sur le dataset Titanic).

```
ai-ml-formation/
├── main.ipynb    # Notebook de travail en cours (Phase 1, Semaine 1)
└── readme.md
```

## Organisation cible

Une fois la Phase 1 avancée, je séparerai le travail par phase pour garder le dépôt lisible :

```
ai-ml-formation/
├── 01-python-maths/        # NumPy, Pandas, algèbre linéaire, probabilités
├── 02-ml-classique/        # scikit-learn : régression, classification, clustering
├── 03-deep-learning/       # PyTorch : réseaux denses, CNN, Transformers
├── 04-nlp-llms/            # Hugging Face, fine-tuning, RAG, agents
├── 05-mlops-portfolio/     # Docker, FastAPI, tracking d'expériences, projets finaux
└── README.md
```

Chaque dossier de phase contiendra un notebook par exercice ou projet, nommé de façon descriptive (ex. `titanic-exploration.ipynb`).

## Progression

| Phase | Sujet | Statut |
|---|---|---|
| 1 | Python data science & maths appliquées | 🔄 En cours (`main.ipynb`) |
| 2 | Machine Learning classique | ⏳ À venir |
| 3 | Deep Learning (PyTorch) | ⏳ À venir |
| 4 | NLP & LLMs | ⏳ À venir |
| 5 | MLOps & portfolio | ⏳ À venir |

## Environnement technique

- Python 3.12, environnement virtuel géré avec `uv`
- Bibliothèques principales : NumPy, Pandas, scikit-learn, PyTorch, Jupyter Lab
- GPU : entraînement local en CPU, calculs intensifs sur Google Colab / Kaggle Notebooks

Installation :

```bash
uv venv
source .venv/bin/activate
uv pip install numpy pandas matplotlib seaborn scikit-learn jupyterlab torch torchvision torchaudio
jupyter lab
```

## Notes

Chaque notebook contient des cellules Markdown expliquant la démarche et les résultats, pas seulement du code brut l'objectif est que ce dépôt serve aussi de portfolio consultable par un recruteur.
