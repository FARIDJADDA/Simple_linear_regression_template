#  Appréhendez les différents types de modélisation<a class="anchor" id="id1"></a>

[Retour au sommaire](#sommaire)

Une modélisation statistique consiste à établir une relation entre variables, sous forme d'équation, que l'on estime sur un jeu de données observées. L'enjeu est d'utiliser cette relation, établie et vérifiée, sur des observations, à des fins de prévision : on se trouve ici dans le cadre de l'inférence.

## Les différents types de modélisation<a class="anchor" id="id1_1"></a>

[Retour au sommaire](#sommaire)

Voici les différents types de modélisation que vous retrouverez le plus souvent. Nous allons les étudier ensemble dans ce cours.

* La régression linéaire, qui permet d'expliquer une variable quantitative à partir de variables explicatives quantitatives (éventuellement qualitatives en sus).

* La classification supervisée, qui permet d'expliquer une variable qualitative à partir de variables explicatives quantitatives (éventuellement qualitatives en sus). Attention, il faut la distinguer de la classification non supervisée qu'est le clustering. 

* L'analyse de la variance, pour analyser l'influence d'une ou deux variables explicatives qualitatives sur une variable quantitative.

### La régression<a class="anchor" id="id1_1_1"></a>

[Retour au sommaire](#sommaire)

> Le terme regression a été introduit par Francis Galton, chercheur britannique du XIXe siècle. Il décrivait dans un article scientifique le fait que la taille des enfants nés de parents inhabituellement grands ou petits se rapproche de la taille moyenne de la population.

La régression désigne désormais toute méthode statistique qui permet de mettre en relation une variable quantitative, que l'on cherche à expliquer et/ou prévoir, avec un ensemble de variables quantitatives (potentiellement) explicatives.

> <span style="background-color:Skyblue">Le modèle de régression le plus connu est le modèle linéaire, simple ou multiple, mais il existe de nombreux autres modèles, parmi lesquels les modèles paramétriques non linéaires et les modèles non paramétriques ou semi-paramétriques. Citons aussi les régressions Ridge et Lasso, les modèles GAM (additifs généralisés), les arbres de régression (et les forêts aléatoires), etc. Pour ce cours, nous nous cantonnerons au modèle linéaire, simple et multiple.</span>

### La classification (supervisée)<a class="anchor" id="id1_1_2"></a>

[Retour au sommaire](#sommaire)

Lorsque la variable à expliquer, à prévoir, est qualitative, on parle alors de classification (supervisée). Si la régression logistique est bien le modèle de base, on trouve également les arbres de décision (et les forêts aléatoires), les SVM, etc.

Ces méthodes de classification permettent d'effectuer du scoring (pour l'attribution d'un prêt bancaire, par exemple) ou encore d'évaluer la probabilité qu'un individu statistique appartienne à une catégorie (qu'il guérisse ou non à la suite de la prise d'un médicament).

> <span style="background-color:#EBA286">Attention, le terme régression logistique pourrait laisser penser qu'il s'agit d'une méthode qui s'applique sur données quantitatives, ce qui n'est pas le cas. Cette méthode est en fait liée à la régression linéaire via une fonction appelée logit, ce qui explique son nom !</span>

### L'analyse de la variance<a class="anchor" id="id1_1_3"></a>

[Retour au sommaire](#sommaire)

L'analyse de la variance (terme souvent abrégé par l'anglais ANOVA : ANalysis Of VAriance) est un modèle statistique utilisé pour comparer les moyennes d'échantillons selon les modalités d'une variable qualitative.