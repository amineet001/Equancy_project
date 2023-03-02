# Equancy_project

A partir d'un dataset de compétences, réaliserez :
* pré-traitement des données
* Un clustering non supervisé afin d'identifier les groupes de
profils techniques distincts
* Une prédiction des profils dont le métier n'est pas labellisé


## Descriptif des données:

`data.csv` : ce fichier contient un tableau de ~10 000 lignes décrivant le profil des candidats. Ce tableau est composé de 6 colonnes :
- Entreprise : correspondant à une liste d'entreprises fictives
- Métier : correspondant au métier du candidat (Cette liste contient les valeurs : « data scientist », « lead data scientist », « data engineer » et « data architecte »
- Technologies : correspond aux compétences maîtrisées par le profil
- Diplôme : correspond à son niveau scolaire (Bac, Master,PhD...)
- Expérience : correspond au nombre d'années d'expériences
- Ville : correspond au lieu de travail

### Methods Utilisées
* Clustering  
* kNN (k plus proches voisins) 


### Bibliothèques Python
* matplotlib 
* pandas
* numpy 
* searbon
* scikit-learn 
