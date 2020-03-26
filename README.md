# Covid-19.be
 Extraction de données belges liées à l'épidémie Covid-19
 
 ## Situation
 
 L'Institut scientifique belge de santé publique (Sciensano) publie depuis mars des rapports quotidiens sur l'évolution de l'épidémie de Covid-19 en Belgique. Ces rapports constituent pour les journalistes et les citoyens la principale source d'informations chiffrées sur le volet belge de la pandémie.
 
Problème : tant le format de ces rapports (des fichiers PDF) que leur contenu (essentiellement des graphes, dont les données sous-jacentes sont souvent non indiquées) rendent leur interprétation difficile. 

Par exemple, qui serait capable d'évaluer à partir de ce graphe, et avec une marge d'erreur raisonnable, le nombre de décès en Flandre le 24 mars ?

![essayez de deviner les chiffres sous-jacents](https://github.com/ettorerizza/Covid-19.be/blob/master/2020-03-26/Evolution%20du%20nombre%20de%20d%C3%A9c%C3%A8s%20COVID-19%20par%20r%C3%A9gion_original.png)


Des journalistes et des membres de la communauté scientifique s'en sont émus publiquement, et il n'est pas impossible que dans les prochains jours (nous écrivons ces lignes le 26 mars), [ces données publiques soient enfin publiées dans un format structuré, en open data](https://www.rtbf.be/info/belgique/detail_quand-le-federal-refuse-d-ouvrir-les-donnees-sur-l-epidemie-de-coronavirus-un-probleme-majeur-qui-retarde-les-scientifiques?id=10466339). 

En attendant, le monde continue de tourner, l'épidémie de progresser et les médias de la raconter et de l'illustrer à l'aide des maigres données disponibles.

## Contenu de ce répertoire

Ce repo Github vise à stocker, pour chaque rapport Sciensano publié à partir du 26 mars, des données extraites automatiquement de ces graphes en PDF. Nous avons utilisé pour cela l'outil gratuit [snapchart.co](https://www.snapchart.co/), qui possède le double avantage d'être très simple d'utilisation et de gérer relativement bien les graphes empilés (*stacked bar charts*).

Ces données sont mises à disposition au format CSV, accompagnées du graphe original ainsi que d'une version améliorée de ce dernier (hélas au format png, l'export en image vectorielle étant impossible avec l'outil utilisé).

**ATTENTION : ces données et ces graphes n'ont rien d'officiel ! Il s'agit d'une extrapolation sur base de l'apparence des graphes originels !** 

En conséquence, la seule vocation de ce répertoire est de mettre à disposition:

- Pour les journalistes et pour les citoyens, une estimation au doigt mouillé, mais plus précise que l'oeil humain, des **grandes tendances** dissimulées dans les graphes - par exemple la mortalité par région.

- Pour les infographistes, une base plus pratique pour **reproduire (grosso modo) les graphiques originels**.

- Pour chacun, une version des graphiques (un peu) plus agréable à l'oeil.

Toute utilisation de ces données à des fins d'analyse statistique est vivement déconseillée (ou à vos risques et périls).

## Si vous souhaitez participer

Les push requests sont les bienvenues, que ce soit pour ajouter des graphes ou corriger les données existantes (arrondir les chiffres, les modifier sur base des chiffres réels indiqués dans les rapports Sciensano antérieurs, etc.)
