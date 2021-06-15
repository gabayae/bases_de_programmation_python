---
layout: default
---



## <a href="http://imsp-benin.com/" ><img src="http://imsp-benin.com/home/images/logoimsp.png" style="float:left; max-width: 80px; display: inline" alt="IMSP"/> |  [*Institut de Mathématiques et Sciences Physiques*](http://imsp-benin.com/home/page.php?index=directeur&parent=presentation)




[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/) 

[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/notebooks/welcome.ipynb?hl=fr)


*Tous les contenus originaux sont sous licence CC BY-NC-SA 4.0, les ressources extérieures (comme bootstrap) sont sous leur licence respective [![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/).*


*Auteur: Yaé Ulrich Gaba, yaeulrich.gaba@gmail.com*


Ce cours vise à vous enseigner les bases de développement de logiciels professionnels dans le contexte de la science.
Le matériel est destiné à être utilisé dans un cours universitaire (à tout niveau où le matériel semble approprié,
en fonction de votre formation!), mais peut également être utilisé pour l'auto-apprentissage. 
Nous nous concentrons uniquement sur Python 3. Ce cours, à la fois minimaliste et pratique, vous permettra de découvrir rapidement les concepts essentiels de la programmation en **Python**. Il faut dire que ça vaut la peine de s'intéresser à Python, c'est un langage qui sera forcément présent dans l'écosystème informatique des années à venir. 


*Pour ce cours, des discussions LIVE! peuvent se faire sur [![Gitter](https://badges.gitter.im/ai-technipreneurs/programmation-python-pratique.svg)](https://gitter.im/ai-technipreneurs/programmation-python-pratique?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge). Vous pourrez toujours joindre la discussion et y poser vos questions, même quand le cours sera terminé.*



## Cahiers virtuels de cours
 
 Vous trouverez les cahiers virtuels pour ce cours sur [ce dépôt GitHub](https://github.com/gabayae/bases_de_programmation_python-cahiers-virtuels-de-cours).


Le langage de programmation Python est souvent utilisé dans les domaines scientifiques aujourd'hui. C’est un langage de programmation relativement accessible et adapté aux universitaires. Dans ce cahier virtuel d'exercices, nous vous présenterons le langage et apprendrons les basiques liés à l'algorithmique. Ce cours n'attend de vous aucun prérequis de programmation.

Les avantages de Python sont nombreux. D'une part c'est sans doute le langage de script le plus utilisé au monde car on peut quasiment tout faire avec: programmation web, statistiques, machine learning, gestion de bases de données. La communauté de Python est la plus grande dans le monde de la programmation: si vous voulez quelque chose, quelqu'un l'a sûrement déjà fait.


## Les sujets que nous aborderons comprennent:
 
  * Programmation et notions de base en informatique avec Python; voir le dossier [cahiers_virtuels_de_cours](https://github.com/gabayae/bases_de_programmation_python/tree/master/cahiers_virtuels_de_cours);
  * Python pour le calcul scientique, voir le dossier [route-calcul_scientifique](https://github.com/gabayae/python-pour-le-cs-et-la-sd/tree/master/route-calcul_scientifique) (... en préparation);
  * Python pour la science des données, voir le dossier [route-sciences_des_données](https://github.com/gabayae/python-pour-le-cs-et-la-sd/tree/master/route-sciences_des_données) (... en préparation).

## [Python: un survol rapide](http://www.larsen-b.com/static/intro_python/)

## Python X ?

Nous utiserons Python 3 dans notre cours. Les versions précédentes peuvent poser des problèmes.
Il y'a deux versions de Python, la 2 et la 3. La 2 n'est plus maintenue depuis 2017, il vaut donc mieux se mettre directement à la 3 (on est actuellement à la version 3.10).



## Installation

Pour installer Python localement, la distribution Anaconda est recommandée, ainsi que l'environnement Jupyter : https://www.anaconda.com/distribution/.

#### OS X

Il existe de nombreuses façons d'installer Python, une des meilleures est d'utiliser le package Anaconda.  Nous vous conseillons donc d'installer la distribution Anaconda. Elle contient tous les modules et packages nécessaires pour ce cours. Elle est disponible pour toutes les plateformes et possède une procédure d'installation assez simple. Vous pouvez la télécharger depuis [Continuum](http://continuum.io/downloads).  Des détails pour l'installation peuvent être trouvés [ici](http://docs.continuum.io/anaconda/install.html). 

Cependant, vous pouvez emprunter une autre route, qui elle, se decompose en deux étapes:
1- Installer [Python](https://www.python.org/);
2- Installer [Jupyter](https://jupyter.org/install.html).

Pour installer Python, il suffit de télécharger la version 3 qui correspond à votre système d’exploitation (Windows ou Mac). 
Pour ce qui est des systèmes Linux, Python est généralement déjà installé par défaut. Il vous suffit d'ajouter [Jupyter](https://jupyter.org/install.html).. Pour ce qui est de Jupyter, faites reference aux liens:
 
         - http://jupyter.org/install.html
         - http://jupyter.readthedocs.io/en/latest/install.html.

 

***********


## Séance 1 – jeudi 17 juillet : 9h00 - 16h00

Programme : Introduction et prise en main du Jupyter. 

Notions: [00. Introduction à python](https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/00_Introduction_%C3%A0_python.ipynb), [01. Variables et affectations](https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/01_Variables_et_affectations.ipynb), [02. Chaînes de caractères](https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/02_Cha%C3%AEnes_de_caract%C3%A8res.ipynb).
 
 En complément du chapitre de présentation des bases du langage Python, vous pourrez également consulter avec profit les [cinq premières sections du tutoriel officiel de Python](https://docs.python.org/fr/3/tutorial/).




## Séance 2 – vendredi 18 juillet : 9h00 - 16h00

Programme :  listes, dictionnaires, tuples et sets, boucles et comparaisons, tests.

Notions: [03. Objets itérables ou conteneurs](https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/03_Objets_it%C3%A9rables_ou_conteneurs.ipynb), [04. Contrôle du flux d'instructions](https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/04_Contr%C3%B4le_du_flux_d_instructions.ipynb).




## Séance 3 – jeudi 24 juillet : 9h00 - 16h00

Programme :  fonctions, modules et paquets, programmation orientée objet.

Notions:[05. Fonctions, Modules et Packages](https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/05_Fonctions_Modules_et_Packages.ipynb), [06. Classes et POO](https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/06_Classes_et_POO.ipynb).








***********

# Démarrage rapide, je voudrais un avant-goût. Pour cela, vous avez deux options: 
 

### Option 1: je veux juste jouer avec ces carnets en ligne sans avoir à installer quoi que ce soit

Pour cela, utilisez l'un des services suivants.

**ATTENTION** : Sachez que ces services fournissent des environnements temporaires : tout ce que vous faites sera supprimé au bout d'un moment, alors assurez-vous de télécharger toutes les données auxquelles vous tenez.

* **Recommandé** : ouvrir ce dépôt en [Colaboratory](https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/):
<a href="https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/"><img src="https://colab.research.google.com/img/colab_favicon.ico" width="90" /></a>

* ou l'ouvrir dans [Binder](https://mybinder.org/v2/gh/gabayae/bases_de_programmation_python/tree/master/cahiers_virtuels_de_cours/HEAD):
<a href="https://mybinder.org/v2/gh/gabayae/bases_de_programmation_python/tree/master/cahiers_virtuels_de_cours/HEAD"><img src="https://matthiasbussonnier.com/posts/img/binder_logo_128x128.png" width="90" /></a> . 

* ou encore en cliquant 👉 [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gabayae/bases_de_programmation_python/tree/master/cahiers_virtuels_de_cours/HEAD) 
 
##### Cahiers de cours dans [Colaboratory](https://colab.research.google.com/notebooks/welcome.ipynb)

Chaque chapitre, entièrement contenu dans un **notebook iPython (Jupyter)**, est directement accessible sur la plateforme **[Google Colab](https://colab.research.google.com/notebooks/welcome.ipynb)**. Google Colab est une plateforme cloud entièrement gratuite, donnant un accès direct et facile à un une interface de programmation en Python (via des cahiers/calepins Jupyter) déjà correctement pré-configurée, et disposant de nombreuses librairies pré-installées. [Accédez au sommaire](https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/Index.ipynb).
Ci-dessous, vous pouvez aller directement aux cahiers de cours dans Google Colab.

 * [Sommaire](https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/Index.ipynb)
 * [00. Introduction à python](https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/00_Introduction_%C3%A0_python.ipynb)
 * [01. Variables et affectations](https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/01_Variables_et_affectations.ipynb)
 * [02. Chaînes de caractères](https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/02_Cha%C3%AEnes_de_caract%C3%A8res.ipynb)
 * [03. Objets itérables ou conteneurs](https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/03_Objets_it%C3%A9rables_ou_conteneurs.ipynb) 
 * [04. Contrôle du flux d'instructions](https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/04_Contr%C3%B4le_du_flux_d_instructions.ipynb)
 * [05. Fonctions, Modules et Packages](https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/05_Fonctions_Modules_et_Packages.ipynb)
 * [06. Classes et POO](https://colab.research.google.com/github/gabayae/bases_de_programmation_python-colab/blob/main/06_Classes_et_POO.ipynb)



##### Cahiers de cours avec [nbviewer](https://nbviewer.jupyter.org/)

Les cahiers peuvent être aussi consultés sous forme de page web statique avec [nbviewer](https://nbviewer.jupyter.org/). Dans cette configuration, 
aucun code ne pourra être exécuté. Les calepins sont lisibles [ici, avec le visualiseur de bloc-notes de jupyter.org](https://nbviewer.jupyter.org/github/gabayae/bases_de_programmation_python-nbviewer/tree/main/).


###  Option 2: je veux juste regarder rapidement quelques carnets, sans exécuter de code

Parcourir ce dépot en utilisant [le visualiseur de bloc-notes de jupyter.org](https://nbviewer.jupyter.org/github/gabayae/bases_de_programmation_python-nbviewer/tree/main/)
<a href="https://nbviewer.jupyter.org/github/gabayae/bases_de_programmation_python-nbviewer/tree/main/
"><img src="https://jupyter.org/assets/nav_logo.svg" width="150" /></a>





## Sur place ou à emporter ?

### 👉 [Vous pouvez aussi télécharger tous les cahiers de cours](https://github.com/gabayae/bases_de_programmation_python-cahiers-virtuels-de-cours).




