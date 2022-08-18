# Detection-de-faux-billet
Le machine learning vient en aide à la lutte contre la criminalité.
Ce Projet est réalisé en formation de data analyst. Grâce à la régression logistique, créez un modèle qui permet de détecter les faux billets.

# Scénario
Votre société de consulting informatique vous propose une nouvelle mission au ministère de l'Intérieur, dans le cadre de la lutte contre la criminalité organisée, à l'Office central pour la répression du faux monnayage. Votre mission si vous l'acceptez : créer un algorithme de détection de faux billets.

Vous vous voyez déjà en grand justicier combattant sans relâche la criminalité organisée en pianotant à mains de maître votre ordinateur, pour façonner ce fabuleux algorithme  qui traquera la moindre fraude et permettra de mettre à jour les réseaux secrets de faux-monnayeurs ! La classe, non ?

... Bon, si on retombait les pieds sur terre? Travailler pour la police judiciaire, c'est bien, mais vous allez devoir faire appel à vos connaissances en statistiques, alors on y va !

# Les Data
La PJ vous transmet un [jeu de données](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-analyst/notes.csv) contenant les caractéristiques géométriques de billets de banque. Pour chacun d'eux, nous connaissons :

la longueur du billet (en mm) ;
la hauteur du billet (mesurée sur le côté gauche, en mm) ;
La hauteur du billet (mesurée sur le côté droit, en mm) ;
la marge entre le bord supérieur du billet et l'image de celui-ci (en mm) ;
la marge entre le bord inférieur du billet et l'image de celui-ci (en mm) ;
la diagonale du billet (en mm).
# Mes missions
## mission 0
Afin d'introduire votre analyse, effectuez une brève description des données (analyses univariées et bivariées).
## mission 1
Vous réaliserez une analyse en composantes principales de l'échantillon, en suivant toutes ces étapes :

analyse de l'éboulis des valeurs propres ;
représentation des variables par le cercle des corrélations ;
représentation des individus par les plans factoriels ;
analyser de la qualité de représentation et la contribution des individus.
Pour chacune de ces étapes, commentez les résultats obtenus. La variable donnant la nature Vrai/Faux du billet sera utilisée comme variable illustrative.
## mission 2
Appliquez un algorithme de classification, puis analysez le résultat obtenu.

Visualisez la partition obtenue dans le premier plan factoriel de l'ACP, puis analysez-la.
## mission 3
Modélisez les données à l'aide d'une régression logistique. Grâce à celle-ci, vous créerez un programme capable d'effectuer une prédiction sur un billet, c'est-à-dire de déterminer s'il s'agit d'un vrai ou d'un faux billet. Pour chaque billet, votre algorithme de classification devra donner la probabilité que le billet soit vrai. Si cette probabilité est supérieure ou égale à 0.5, le billet sera considéré comme vrai. Dans le cas contraire, il sera considéré comme faux.

# Compétence évaluées
- Réaliser une ACP
- Utiliser un algorithme de clustering de type Kmeans
- Modéliser grace à la régression logistique
- Interpreter une ACP
