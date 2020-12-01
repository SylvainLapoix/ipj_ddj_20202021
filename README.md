# IPJ Dauphine : master 2 - option datajournalisme

![](https://www.ipj.eu/wp-content/uploads/2019/03/Logo-IPJ-2019.png)

Ce cours se déroule dans le cadre du master journalisme de l'[Institut Pratique de Journalisme - Paris Dauphine](https://www.ipj.eu/).

## Formateur
* Sylvain Lapoix ([#DATAGUEULE](https://www.youtube.com/user/datagueule) + [Datactivist](https://datactivist.coop/))

## Etudiant·e·s

-- à venir --

## Programme


| Jour | Module | Thématique | 
| :-----: | :-----: |  -----: | 
| 19/10/2020 | Cours01 | Introduction à R et à la programmation | 
| 10/11/2020 | Cours02 | Récupérer et charger des données | 
| 23/11/2020 | Cours03 | Nettoyer et manipuler des données | 
| 01/12/2020 | Cours04 | Analyser des données | 
| 04/12/2020 | Cours05 | Visualisation | 
|  | Cours06 | Introduction à l'analyse exploratoire de données | 

------

## Installation

**Attention** : les installations doivent être réalisées dans cet ordre, au risque que les programmes ne fonctionnent pas correctement.

### Windows
1. [dernière version disponible de R base](https://cran.r-project.org/bin/windows/base/) ;
2. [dernière version disponible de Rstudio](https://rstudio.com/products/rstudio/download/#download)
3. [Sublime Text 3](https://www.sublimetext.com/3)

### Mac
1. [dernière version disponible de R base](https://cran.r-project.org/bin/macosx/)
2. [dernière version disponible de Rstudio](https://rstudio.com/products/rstudio/download/#download)
3. [Sublime Text 3](https://www.sublimetext.com/3)

Veillez à installer également XCode et `{fansi}` comme expliqué  [ici](https://community.rstudio.com/t/problems-installing-packages-error-non-zero-exit-status-and-unknown-time-zone/73237/2) pour éviter les problème de timezone avec `{lubridate}` et les fonctions `date` en général.


### Linux

Pré-requis :
```
sudo apt install libcurl4-openssl-dev
sudo apt install libxml2-dev
```


### Packages R
1. {tidyverse} ;
2. {data.table} ;
3. {devtools} ;
4. {rvest}.

## Support

* Cours01 : [R, votre nouvel outil](https://sylvainlapoix.github.io/ipj_ddj_20202021/cours01/#1)
* Cours02 : [Sourcer et lire les données en R](https://sylvainlapoix.github.io/ipj_ddj_20202021/cours02/#1)
* Cours03 : [Nettoyer et manipuler des données en R](https://sylvainlapoix.github.io/ipj_ddj_20202021/cours03/#1)
* Cours04 : [Analyse de données en R](https://sylvainlapoix.github.io/ipj_ddj_20202021/cours04/#1)
* Cours05 : à venir
* Cours06 : à venir

## Bases de données utilisées

### cours02
* [Indicateurs de suivi de l’épidémie de COVID-19](https://www.data.gouv.fr/fr/datasets/indicateurs-de-suivi-de-lepidemie-de-covid-19/), 2020, Ministère de la Santé ;
* [Projet de loi de finances pour 2021 (PLF 2021), données du PLF et des annexes projet annuel de performance (PAP)](https://www.data.gouv.fr/fr/datasets/projet-de-loi-de-finances-pour-2021-plf-2021-donnees-du-plf-et-des-annexes-projet-annuel-de-performance-pap/#_), 2020, Ministère de l'économie, des finances et de la relance ;
* [Clubs sportifs : coût d'une cotisation adulte à Issy-les-Moulineaux](https://www.data.gouv.fr/fr/datasets/clubs-sportifs-cout-dune-cotisation-adulte-a-issy-les-moulineaux/), 2020, Ville d'Issy-les-Moulineaux ;

### cours03
* [Répertoire national des élus (RNE)](https://www.data.gouv.fr/en/datasets/repertoire-national-des-elus-1/), 2020, Ministère de l'Intérieur.

### cours04
* [Registre de Preuve de Covoiturage](https://www.data.gouv.fr/en/datasets/trajets-realises-en-covoiturage-registre-de-preuve-de-covoiturage/), 2020 ;
* [Base Nationale des Lieux de Covoiturage](https://www.data.gouv.fr/en/datasets/base-nationale-des-lieux-de-covoiturage/), Point d'Accès National transport.data.gouv.fr, 2020.

### cours05
* à venir

### cours06
* à venir


## Références

### Généralités sur R
* [R for datascience](https://r4ds.had.co.nz/) ;
* [Introduction à R et au tidyverse](https://juba.github.io/tidyverse/) ;
* les raccourcis claviers de Rstudio : [Keyboard shortcuts, Rstudio](https://support.rstudio.com/hc/en-us/articles/200711853-Keyboard-Shortcuts) ;
* quelques "feuilles de triches" des packages R (notamment tidyverse) : [Rstudio Cheat Sheets, Rstudio](https://rstudio.com/resources/cheatsheets/).

### Sur la gestion des fichiers
* créer un projet sous R, organiser ses fichiers ... [dans la très bonne introduction du parcours de formation à R du Ministère de la Transition énergétique et solidaire ](https://mtes-mct.github.io/parcours-r/m2/bien-commencer.html) ;
* [le chapitre Organiser ses fichiers](http://larmarange.github.io/analyse-R/organiser-ses-fichiers.html) du tutoriel en ligne Analyse-R créé et maintenu par Joseph Larmarange ;
* [Organiser ses scripts](https://juba.github.io/tidyverse/05-organiser.html) dans l'Introduction à R et au tidyverse de Julien Barnier, référence en langue française s'il en est.

### Sur le scraping
* [la cheatsheet xPath de Devhints](https://devhints.io/xpath), très complète et didactique.

### Sur les regex
* [Strings - Maching patterns with regular expressions in R for data science](https://r4ds.had.co.nz/strings.html), Hadley Wickham ;
* [les regex avec StringR](https://stringr.tidyverse.org/articles/regular-expressions.html), documentation {tidyverse}.