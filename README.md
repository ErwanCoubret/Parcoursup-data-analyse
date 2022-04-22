# **Parcoursup Data Analyse** 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1CaLyq1azazLa3682fGXkIn8g3O-qlqdO?usp=sharing)

## **Préambule 📜** 

>Je suis Erwan Coubret, actuellement élève de MP2I qui aime bien jouer avec les données. Alors j'ai récupéré celles de parcoursup et j'ai fait ce notebook pour permettre à tout le monde d'y jeter un coup d'œil facilement. Normalement j'ai fait en sorte que ce qui est mis est compréhensible et facilement modifiable pour qui le veut, à condition d'avoir 2/3 connaissances en python.
> <br/><br/>
> Voilà, pas de soucis de copyright, faites en ce que vous voulez. Si vous avez un problème, vous pouvez me contacter sur twitter : https://twitter.com/ErwanCoubret.

## **Pas de prérequis 😊**
>Vous êtes sur un notebook Colaboratory, une adaptation de Jupyter à la sauce Google pour les connaisseurs. Il s'agit d'un service très pratique, utilisant les serveurs de Google pour faire tourner vos scripts (pas mal si vous avez une petite machine où êtes en déplacement). Si jamais vous galérez vraiment allez voir le [tutoriel d'introduction à Colaboratory](https://colab.research.google.com/notebooks/intro.ipynb#scrollTo=GJBs_flRovLc).

**Normalement la base de données est téléchargée automatiquement.** Mais si jamais il y a un problème, voici la procédure  :

**1.**   Rendez vous sur cette URL : https://data.enseignementsup-recherche.gouv.fr/explore/dataset/fr-esr-parcoursup/export/ et téléchargez le .csv (cela peut aussi servir si vous voulez jouer avec les données de votre côté)<br/>
**2.**   Cliquez ensuite sur l'icone fichier sur la barre de gauche et importez le .csv, soit en le glissant dans la zone, ou manuellement<br/>
**3.**   Et voilà c'est fini. **(Par contre attention il faudra le remettre si jamais vous quittez la page)**
****

## **Librairies utilisées 📚**

* **🐼 Pandas** : Librairie pour transformer vos datasets en "dataframe", un outil puissant pour manipuler des données.

* **📊 Plotly** : Librairie pour visualiser les données, de manière plus propre que matplotlib, avec notamment une meilleure interaction avec le graphe... Bien qu'encore trop peu utilisée aujourd'hui, la techno est très puissante. Si vous voulez jeter un coup d'oeil aux capacités je vous redirige vers ce tutoriel : https://github.com/antonin-lfv/Plotly_tutorial. Ici on utilisera **plotly.graph_objects**, mais d'autres versions existent, avec leurs propres avantages.
