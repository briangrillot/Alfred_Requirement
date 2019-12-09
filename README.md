# Rapport

### Diagramme Requirement

![alt text](https://github.com/briangrillot/Alfred_Requirement/img/Alfred_req.PNG)

### Diagramme User Case

![alt text](https://github.com/briangrillot/Alfred_Requirement/img/Alfred_UC.PNG)

Pour ce diagramme on a place Alfred en tant qu'acteur principale, et on a pris comme action
"Mesurer le taux de CO2" et "Mesurer le taux de COV", ces actions permettent de préserver la
qualité de l'air. 
on a aussi pris comme action "Mesurer la température" et "Mesurer le taux d'humidité"; ces actions
permettant respectivement de "regler la temperature" et "regler l'aération".    

### Diagramme de blocs (BDD)

![alt text](https://github.com/briangrillot/Alfred_Requirement/img/Alfred_BDD.PNG)

Pour ce diagramme on est parti d'un bloc representant le système souhaité ("Systeme"), ce block est composée
des capteurs et des indicateurs. On a representé les elements dont on a besoin pour utiliser les indicateurs en tant que
blocs (Electricité, Eau, Air, Température, etc...). Ensuite on sait que le Systeme est composée des ces elements, ce systeme
calcule les données dont Alfred a besoin. Puis Alfred recupere les statistiques/indicateurs à partir du Systeme.

### Diagramme de bloc internes (IBD)

