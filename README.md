# 🩺 Clinique & Soins Médicaux - Tableau de Bord Décisionnel Power BI

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data%20Analysis%20Expressions-blue?style=for-the-badge)
![Healthcare Management](https://img.shields.io/badge/Healthcare-Management-crimson?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

Solution décisionnelle Power BI dédiée au **pilotage opérationnel, financier et qualitatif d'un établissement de santé / clinique**. Ce projet modélise le cycle des consultations, l'analyse de la patientèle, le suivi des diagnostics et le recouvrement des honoraires.

---

## 📌 Objectifs et Périmètre Décisionnel

Le dashboard a été conçu pour répondre aux problématiques clés de gestion hospitalière :
- **Suivi d'activité & performance financière :** Chiffre d'affaires global, volume des consultations, taux de recouvrement des règlements.
- **Répartition médicale :** Performance et charge par médecin et par spécialité médicale.
- **Démographie et patientèle :** Répartition des patients par tranche d'âge, genre, ville de provenance et type de couverture/assurance.
- **Qualité des soins & prise en charge :** Suivi de la récurrence des consultations par patient et cartographie des diagnostics récurrents.

---

## 📊 Pages du Dashboard Power BI

Le rapport [`projetPOWERBI.pbix`](./projetPOWERBI.pbix) est composé de **deux pages d'analyses interactives** :

### 1. Page "Vue d'ensemble"
- **Indicateurs Clés (KPIs) :**
  - Chiffre d'Affaires Total réalisé
  - Nombre Total de Consultations
  - Nombre de Patients Uniques
  - Taux Global de Paiement (Règlements honorés vs En attente)
- **Analyses Visuelles :**
  - Évolution temporelle des consultations par mois (Line Chart).
  - Répartition du chiffre d'affaires et des consultations par spécialité (Bar Charts).
  - Répartition par statut de paiement et type d'assurance (Donut Chart).
  - Cartographie géographique par ville d'origine (Visual Map).
  - Table synthétique avec détails des consultations par praticien.

### 2. Page "Patients & Qualité"
- **Indicateurs Qualité & Fréquentation :**
  - Nombre moyen de consultations par patient.
  - Taux de fidélisation et récurrence des soins.
- **Analyses Cliniques & Démographiques :**
  - Distribution par tranche d'âge et par genre (Pyramide / Colonnes groupées).
  - Répartition des diagnostics les plus fréquents (Bar Charts).
  - Corrélation entre âge, spécialité et fréquence des visites (Scatter / Nuage de points).
  - Volet de filtres avancés (Spécialités, Médecins, Diagnostics, Périodes temporelles).

---

## 📐 Mesures DAX Calculées

Le rapport intègre plusieurs mesures DAX personnalisées pour le calcul dynamique des indicateurs :

- **`[Chiffre d'Affaires Total]`** : Somme pondérée des montants de consultations.
- **`[Total Consultations]`** : Comptage total des actes et rendez-vous réalisés.
- **`[Patients Uniques]`** : Calcul distinct du nombre de patients enregistrés (`DISTINCTCOUNT`).
- **`[Consultations par Patient]`** : Ratio d'intensité médicale mesurant le suivi patient.
- **`[Consultations par Mois]`** : Analyse de la dynamique temporelle et de la saisonnalité.
- **`[Taux de Paiement]`** : Pourcentage des consultations régularisées par rapport au volume global facturé.

---

## 📂 Contenu du Projet

```
Projet-Clinique-PowerBI/
│
├── 📊 projetPOWERBI.pbix      # Fichier principal Power BI Desktop
├── 🖼️ assets/                 # Arrière-plans, chartes graphiques et captures
├── ⚙️ .gitignore              # Exclusion des fichiers temporaires
└── 📖 README.md               # Documentation détaillée du projet
```

---

## 🚀 Utilisation

1. **Prérequis :** Installer [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. **Clonage du projet :**
   ```bash
   git clone https://github.com/MOUTAOUAKIL-Aya/clinique-powerbi.git
   cd clinique-powerbi
   ```
3. **Ouverture :**
   Ouvrez le fichier `projetPOWERBI.pbix` dans Power BI Desktop pour explorer les données et interagir avec les slicers et visuels.

---

## 👩‍💻 Auteur
- **Aya MOUTAOUAKIL** - *Élève Ingénieur en Business Intelligence & Informatique Décisionnelle (ESISA)*
- GitHub : [@MOUTAOUAKIL-Aya](https://github.com/MOUTAOUAKIL-Aya)
