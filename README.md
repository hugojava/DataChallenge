# Toxic Gas Identification – Data Challenge Bertin Technologies

Ce projet a été réalisé dans le cadre d’un **data challenge multi-output** visant à prédire la
probabilité de présence de différents gaz à partir de mesures de capteurs.  
Le dataset contient environ **330 000 échantillons**, dont la moitié en test, et présente un fort
problème de **data shift**, notamment sur la variable `Humidity`.

---

## 📁 Structure du projet

```bash
📁 DataChallenge/
│
├── 📁 notebooks_data/
│   ├── Best_Model.ipynb
│   ├── DataChallenge_0.1.0.ipynb
│   ├── DataChallenge_0.1.1.ipynb
│   ├── DataChallenge_0.1.2.ipynb
│   ├── DataChallenge_0.2.0.ipynb
│   ├── DataChallenge_0.2.1.ipynb
│   ├── DataChallenge_0.2.2.ipynb
│   ├── DataChallenge_0.3.0.ipynb
│   ├── DataChallenge_0.3.1.ipynb
│   ├── DataChallenge_0.3.2.ipynb
│   ├── DataChallenge_0.3.3.ipynb
│   ├── DataChallenge_0.3.4.ipynb
│   ├── First_model.ipynb
│   ├── x_test_9F13O5s.csv
│   ├── x_train_T9QMMVq.csv
│   └── y_train_R0MqWmu.csv
│  
├── README.md
├── Report.pdf
└── requirements.txt

```
---

## ⚙️ Installation

1. **Cloner le dépôt :**
    ```bash
    # Cloner le répertoire
    git clone https://github.com/hugojava/DataChallenge
    cd DataChallenge

2. **Installer les dépendances :**
    (uniquement pour le meilleur modèle)
    ```bash
    # 1️⃣ Créer un environnement virtuel 
    # (dépend de la manière dont Python a été installé)

    python -m venv venv
    ou python3 -m venv venv

    # 2️⃣ L'activer
    # Sous Linux / macOS :
    source venv/bin/activate

    # Sous Windows :
    venv\Scripts\activate

    # 3️⃣ Installer les dépendances du meilleur modèle
    pip install -r requirements.txt

## 🧑‍💻 Auteur

Projet développé par Hugo Bouton, dans le cadre du challenge Toxic Gas Identification by Bertin Technologies sur le site https://challengedata.ens.fr.
