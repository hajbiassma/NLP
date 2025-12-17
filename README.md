# Analyse et recommandation de produits à partir des avis clients

## 📝 Contexte
Ce projet combine **NLP et graphes** pour analyser les avis clients, détecter le sentiment, prédire les notes, et proposer des recommandations de produits. Il s'appuie sur le dataset [Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews).

## 🎯 Objectifs
- Analyser le sentiment des avis clients (positif / négatif / neutre)
- Construire un graphe **User ↔ Product** pondéré par la note ou les embeddings
- Prédire la note d’un produit via **Graph Neural Networks (GNN)**
- Recommander des produits aux utilisateurs
- Répondre à des questions simples via le graphe (mini Q&A)

## 🛠 Techniques utilisées
- **NLP** : nettoyage du texte, tokenization, embeddings BERT
- **Graphes** : construction d’un graphe biparti User ↔ Product
- **GNN** : GraphSAGE pour prédiction de notes
- **Evaluation** : RMSE pour mesurer la qualité de la prédiction
