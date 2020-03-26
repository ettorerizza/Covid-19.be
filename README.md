# Covid-19.be
 Extraction de données belges liée à l'épidémie Covid-19
 
 ## Situation
 
 L'Institut scientifique belge de santé publique (Sciensano) publie depuis mars des rapports quotidiens sur l'évolution de l'épidémie de Covid-19 en Belgique. Ces rapports constituent pour les journalistes et les citoyens la principale source d'informations chiffrées sur le volet belge de la pandémie.
 
Problème : tant le format de ces rapports (des fichiers PDF) que leur contenu (essentiellement des graphes, dont les données sous-jacentes sont souvent non indiquées) rendent leur interprétation difficile. Des journalistes et des membres de la communauté scientifique s'en sont émus publiquement et il n'est pas impossible que dans les prochains jours (nous écrivons ces lignes le 26 mars), ces données publiques soient enfin publiées dans un format structuré, en open data. 

En attendant, le monde continue de tourner, l'épidémie de progresser et les médias de la raconter et de l'illustrer à l'aide des maigres données disponibles.

## Contenu de ce répertoire

Ce repo Github vise à stocker, pour chaque rapport Sciensano publié à partir du 26 mars, des données extraites automatiquement de ces graphes en PDF. Nous avons utilisé pour cela l'outil gratuit snapchart.co, qui a le double avantage d'être très simple d'utilisation et de gérer relativement bien les graphes empilés (*stacked bar charts*) que Sciensano affectionne.

Ces données sont mises à disposition au format CSV, accompagnées du graphe original ainsi que d'une version améliorée de ce dernier (hélas au format png, l'export en image vectorielle étant impossible avec l'outil utilisé).

**ATTENTION : ces données et ces graphes n'ont rien d'officiel ! Il s'agit d'une extrapolation sur base de l'apparence des graphes originels !** 

En conséquence, la seule vocation de ce répertoire est de mettre à disposition:

- Pour les journalistes et pour les citoyens, une estimation au doigt mouillé, mais plus précise que l'oeil humain, des **grandes tendances** dissimulées dans les graphes - par exemple la mortalité par région.

- Pour les infographistes, une base plus pratique pour **reproduire les graphiques originels**.

Toute utilisation de ces données à des fins d'analyse statistique est déconseillée. Ou a vos risques et périls.

