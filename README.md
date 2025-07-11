# 📝 Veille : Concepts d’Apprentissage Automatique Supervisé

## 1. Qu’est-ce que l’apprentissage automatique supervisé ?  
L’apprentissage automatique supervisé (*supervised learning*) consiste à entraîner un algorithme sur des **données étiquetées** (avec des résultats connus). L’objectif est que le modèle apprenne à prédire le résultat sur de **nouvelles données**.  

---

## 2. Qu’est-ce que les données étiquetées (ou labellisées) ?  
Les données étiquetées sont des exemples pour lesquels on connaît déjà la **réponse attendue** (*étiquette*).  
**Exemple :** pour un client de banque, l’étiquette peut être « souscrit » ou « non souscrit » à un dépôt à terme.  

---

## 3. Qu’est-ce que la classification supervisée ?  
C’est un type d’apprentissage supervisé où la variable cible est **catégorielle** (exemple : *abonné/non abonné*).  
**Objectif :** prédire à quelle classe une donnée appartient.  

---

## 4. Qu’est-ce qu’un modèle d’apprentissage automatique ?  
Un modèle est une **fonction mathématique** construite à partir des données d’entraînement.  
Il apprend les relations entre les variables d’entrée et la sortie cible pour faire des prédictions.  

---

## 5. Qu’est-ce que les données d’entraînement ? Et l’entraînement d’un modèle ?  
- **Données d’entraînement :** elles servent à apprendre au modèle la relation entre entrées et sorties.  
- **Entraînement :** étape où le modèle ajuste ses paramètres pour reproduire au mieux ces relations.  

---

## 6. Qu’est-ce que la donnée cible (*target*) ?  
C’est la variable qu’on souhaite prédire.  
**Exemple :** dans Bank Marketing, *le client a-t-il souscrit à un dépôt à terme ?* (yes/no).  

---

## 7. À quoi sert la phase d’entraînement d’un modèle ?  
Elle permet au modèle d’**apprendre** à généraliser les relations observées dans les données vers de nouvelles situations.  

---

## 8. À quoi sert la phase de prédiction ?  
Elle consiste à utiliser le modèle entraîné pour **prédire la cible** sur des données encore inconnues.  

---

## 9. Qu’est-ce que le prétraitement des données ? Pourquoi est-ce important ?  
Le prétraitement inclut :  
- Nettoyage (valeurs manquantes, doublons)  
- Encodage des variables catégorielles  
- Normalisation des données  
👉 Il est essentiel car un modèle ne peut pas traiter des données brutes efficacement.  

---

## 10. Comment évaluer un modèle de classification ? Qu’est-ce que l’accuracy ?  
📊 **Accuracy** : pourcentage de prédictions correctes.  

\[
\text{Accuracy} = \frac{\text{Nombre de bonnes prédictions}}{\text{Nombre total de prédictions}}
\]

✅ C’est un bon indicateur si les classes sont équilibrées. Sinon, il peut être **trompeur**.  

---

## 11. Qu’est-ce que l’AutoML ? Pourquoi est-il utile aux débutants ?  
L’**AutoML** (*Automated Machine Learning*) automatise toutes les étapes : nettoyage, choix du modèle, réglage des hyperparamètres…  
💡 **Avantage :** créer rapidement des modèles performants avec peu de code (*exemple : PyCaret*).  

---

## 12. Qu’est-ce qu’un arbre de décision ?  
C’est un modèle qui **divise les données** en fonction de conditions logiques (*exemple : âge > 35 ?*).  
**Les feuilles** indiquent une classe prédite.  
✅ Facile à comprendre et à interpréter.  
