# 🛍️ Segmentation de Clients pour un Site E-commerce  

## 🎯 Objectifs du projet
La segmentation de clients est un levier essentiel pour toute entreprise cherchant à optimiser sa relation client et à améliorer sa performance commerciale. 
Une analyse clients approfondie permet aux organisations de :

- Comprendre le comportement des clients  
- Calculer les indicateurs marketing RFM  
- Segmenter les clients via un algorithme de clustering  
- Interpréter les segments obtenus  
- Proposer des recommandations marketing exploitables  

Ce projet est pensé comme un cas complet de **Data Science marketing**, depuis la préparation des données jusqu'à l’analyse stratégique.

---

## 📊 Méthodologie

Ce projet repose sur la segmentation client à partir de la méthode **RFM (Recency – Frequency – Monetary)**.  
L’objectif est d’identifier des groupes de clients ayant des comportements similaires afin d'orienter des stratégies marketing efficaces : rétention, fidélisation, relance, offres personnalisées, etc.

### 🔎 Comprendre les variables RFM

La méthode RFM s’appuie sur trois indicateurs clés issus de l’historique d’achats d’un client :

- **Recency (Récence)**  
  Mesure le nombre de jours écoulés depuis le dernier achat du client.  
  → Plus la récence est faible, plus le client est considéré comme "actif".

- **Frequency (Fréquence)**  
  Correspond au nombre total de transactions réalisées par le client.  
  → Les clients qui achètent souvent témoignent d’un engagement élevé envers le site E-commerce.

- **Monetary (Montant dépensé)**  
  Représente la somme totale dépensée par le client sur la période étudiée.  
  → Les clients à forte valeur monétaire contribuent le plus au chiffre d’affaires.

Ces trois dimensions permettent de dresser un profil comportemental précis de chaque client et servent de base à la construction des segments via un algorithme de clustering.

---

# 📁 Contenu du dépôt

📦 Segmentation_Clients_FR 
|-- client_segmentation.ipynb # Notebook complet (analyse, clustering, interprétations)  
|-- data/ # Dossier pour les données (si nécessaire)  
|-- README.md # Documentation du projet



