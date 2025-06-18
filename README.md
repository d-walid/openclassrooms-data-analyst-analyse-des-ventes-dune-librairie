# Analyse des ventes d'une librairie

Ce projet analyse les ventes de clients B2C et B2B à partir de plusieurs fichiers de données. L’étude s’organise en trois grandes étapes : nettoyage, analyse exploratoire, et tests de corrélations statistiques.

## 1. Nettoyage et préparation des données

Cette première étape consiste à :
- Vérifier et nettoyer les fichiers `customers.csv`, `products.csv`, et `transactions.csv`.
- Effectuer des traitements complémentaires sur chaque table pour fiabiliser les données.
- Réaliser les jointures nécessaires pour regrouper toutes les informations pertinentes.
- Ajouter des informations dérivées (découpage des dates, discrétisation de l’âge).
- Visualiser la base de données nettoyée pour contrôler la qualité du traitement.

## 2. Analyse exploratoire des données (EDA)

L’EDA permet d’obtenir une vision synthétique des ventes et des comportements d’achat :
- Analyse des clients B2C et B2B (nombre de clients, CA).
- Étude des achats selon le genre.
- Étude des achats par tranche d’âge.
- Analyse des produits (nombre d’articles, panier moyen).
- Analyse des fréquences et des répartitions d’achats, par tranche d’âge et par catégorie de produit.

## 3. Tests de corrélations statistiques

Des tests statistiques sont réalisés pour valider l’existence de liens entre certaines variables :
- **Test du chi2** : lien entre la catégorie de produit et le genre du client.
- **Test de Spearman** : lien entre l’âge et le montant total des achats.
- **Test du chi2** : lien entre la catégorie de produit et la tranche d’âge.

## 4. Description des fichiers de données

- `customers.csv` : informations sur les clients (B2C/B2B, genre, âge, etc.)
- `products.csv` : informations sur les produits (catégorie, prix, etc.)
- `transactions.csv` : enregistrements des transactions (dates, montants, identifiants client/produit, etc.)

---

*Projet réalisé dans le cadre de ma formation Data Analyst avec OpenClassrooms.*
