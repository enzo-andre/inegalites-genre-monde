# Projet Data : Analyse des inégalités de genre dans la participation au marché du travail en 2018

## 🧠  Objectif du projet

Ce projet vise à explorer les **inégalités de genre** dans la participation économique à travers le monde, en s’appuyant sur des données de la Banque mondiale et des indicateurs de développement humain (IDH). L'objectif est d’identifier des **groupes de pays similaires** et d’analyser leurs dynamiques, via des méthodes de **clustering** et de **cartographie**.

---

## 🔎  Données utilisées

- **Taux de participation des femmes (2018)** – Source : [Banque mondiale]
- **Taux de participation des hommes (2018)** – Source : [Banque mondiale]
- **Ratio femmes/hommes de participation (2018)** – Source : [Banque mondiale]
- **PIB/Habitant (2018)** - Source : [Banque mondiale]
- **Indice de Développement Humain (IDH)** – Source : [PNUD]

---

## Méthodologie

1. **Nettoyage et transformation** des données 
2. **Visualisation des ratios femmes/hommes** par pays
3. **Clustering K-Means** :
   - 4 groupes selon le ratio femmes/hommes
   - 4 groupes selon l’IDH
4. **Cartographie** des clusters
5. **Régression linéaire** exploratoire

---

## Résultats visuels

- **Carte 1 : Clusters de pays selon les inégalités de genre**
- **Carte 2 : Cartes comparées** avec un code couleur harmonisé

---

## 💡 Interprétations clés

- Certains pays à **IDH élevé** présentent encore des **inégalités fortes** entre femmes et hommes.
- D’autres pays à **IDH faible** affichent un **ratio équilibré**, parfois dû à des conditions structurelles.
- L’égalité de genre ne suit **pas systématiquement** le niveau de développement.
- La lecture croisée permet de **repérer les pays "en tension"** entre égalité et développement.

---

## Bonus

Une régression linéaire a été tentée entre le ratio femmes/hommes et l'IDH :
- **Aucune corrélation significative** n'a été trouvée
- Cela **renforce la pertinence** de la lecture par cluster

---

## Reproductibilité

> ⚠️ Ce projet a été réalisé avec Google Colab

Il est possible de :
- Télécharger le fichier `.ipynb`
- L’ouvrir dans Google Colab ou Jupyter Notebook
- Reproduire l’intégralité de l’analyse avec les mêmes jeux de données

---

## 👤 Auteur

> Réalisé par **Enzo André**, dans le cadre d'une transition en data science.  
> [LinkedIn](https://www.linkedin.com/in/enzoandre/) | [Portfolio](https://github.com/enzo-andre)
