# 1. Overview

### 1.1 Problem statement
- definition claire et precise du problème (eventuellement passer par un peu de maths)
- essayer de trouver si le problème peut se rattacher à une "task" générique ex. multilabel classification, object detection, ...

### 1.2 Metrics
- definition des metrics pour mesurer les performances du model
- si metrics déjà proposées par le challenge, comprendre comment elles sont calculées

# 2. Data analysis
 - qualifier le type de données et extraire statistiques
 - par ex. pour du texte : est-ce que le language est familier type twitter ? 
 - taille du vocabulaire, frequency distribution, ... (cf. notebook)
 - quel preprocessing steps à prévoir si les données présentent beaucoup de bruit

# 3. Model definition
 - definition du modèle à utiliser pour résoudre le problème ex. Logistic Regression, RNN, K-CCA, ... ==> lecture de papier de recherche
 - définir les features : comment représenter les données. Pour du texte : array de int, 1-hot encoding, wordvectors ?

# 4. Implementation

### 4.1 Benchmark
- entrainer benchmark model avec hyperparameters de base, va servir de référentiel pour le refinement
- éventuellement prendre le modèle d'un participant du challenge Kaggle (je sais pas encore)

### 4.2 Refinement
- modifier hyperparameters du modèle afin d'ameliorer performances : dropout, batch norm, variable initizalition, optimizer, ...
