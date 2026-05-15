## Detection de Fraude Bancaire

Projet data analyst - detection de transactions frauduleuses sur donnees bancaires reelles.

## Resultats

| Metrique | Score |
|----------|-------|
| AUC-ROC | 0.9688 |
| Precision (fraude) | 0.82 |
| Recall (fraude) | 0.82 |
| Fraudes detectees | 80 / 98 |

## Objectif

Identifier les fraudes parmi 284 807 transactions de cartes bancaires europeennes (0.17% de fraudes).

## Dataset

- Source : [Kaggle ULB](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284 807 transactions - 31 variables - 492 fraudes

## Stack technique

- Python - Pandas - Scikit-learn - Matplotlib - Seaborn
- Jupyter Notebook - Git / GitHub - SMOTE (imbalanced-learn)

## Methodologie

1. Chargement et exploration du dataset (EDA)
2. Normalisation des variables Amount et Time
3. Gestion du desequilibre avec SMOTE
4. Modelisation avec Random Forest
5. Evaluation avec AUC-ROC, precision, recall

## Etapes

- [x] Etape 1 - Chargement et exploration
- [x] Etape 2 - EDA et visualisations
- [x] Etape 3 - Nettoyage et SMOTE
- [x] Etape 4 - Modele et evaluation AUC-ROC
- [ ] Etape 5 - Dashboard et synthese
  
