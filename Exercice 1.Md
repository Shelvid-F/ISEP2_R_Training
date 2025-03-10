Exercice d'analyse de données économiques avec R
Contexte
Vous êtes un analyste dans un institut de recherche économique. On vous a confié un jeu de données sur des indicateurs économiques de différents pays sur une période de 10 ans. Votre mission est d'analyser ces données, d'en extraire des tendances et de préparer un rapport synthétique.
# 1. Créez un jeu de données simulé avec les variables suivantes: 
# - pays (facteur): 10 pays différents
 # - annee (numérique): 2013-2022 
# - pib_per_capita (numérique): PIB par habitant en dollars
 # - taux_chomage (numérique): pourcentage de chômage 
# - inflation (numérique): taux d'inflation annuel
 # - dette_publique (numérique): pourcentage du PIB
 # - investissement_etranger (numérique): en millions de dollars 
# - region (facteur): continent ou région économique

# 2.1 Examinez la structure des données
# 2.2 Vérifiez les valeurs manquantes
# 2.3 Remplacez les valeurs manquantes par la moyenne de la variable pour le pays concerné
# 2.4 Vérifiez les statistiques descriptives par région
# 3.1 Créez une nouvelle variable indiquant si le pays connaît une "récession" # (définie comme 2 années consécutives de baisse du PIB)
# 3.2 Calculez la corrélation entre les différentes variables économiques
# 3.3 Analysez l'évolution des indicateurs au fil du temps pour chaque région
# 3.4 Calculez les moyennes mobiles sur 3 ans pour lisser les tendances
# 5.1 Créez une matrice de corrélation visuelle
# 5.2 Identifiez les pays ayant les meilleures et pires performances économiques
