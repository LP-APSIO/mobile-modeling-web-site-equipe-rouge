# 1. Qu'est ce que l'UML ?


 _Quoi_ :  de l'anglais Unified Modeling Language = Langage de Modélisation Unifié.
Il s’agit d’une standardisation de différents diagrammes de conceptions (modélisations graphiques à base de pictogrammes) pensée pour être un **langage de modélisation visuelle commun**, riche sémantiquement et syntaxiquement.
L'UML n'est pas un langage de programmation, mais il existe des outils qui peuvent être utilisés pour générer du code en plusieurs langages à partir de diagrammes UML.
L'UML a une relation directe avec l'analyse et la conception orientées objet.

_Pour quoi_:  architecture, conception et mise en œuvre de systèmes logiciels complexes par leur structure aussi bien que leur comportement

_Pour qui_ : tous les acteurs du développement d’un projet : client, concepteurs/développeurs/ingénieurs logiciel, designers…

_Quand_ : essentiellement durant les phases d’analyse et de conception, mais utilisable à n’importe quelle étape du développement

_Objectifs_ :

-   Permettre une communication claire entre les différents intervenants du projet
    
-   Fournir des outils pour l'analyse, la conception et la mise en œuvre de systèmes logiciels, ainsi que pour la modélisation de processus métier et d'autres processus similaires.
    
-   Faire progresser l'industrie en permettant l'interopérabilité des outils de modélisation visuelle orientés objet.
    

  

_Historique :_

Les Three Amigos du génie logiciel (  [Grady Booch](https://fr.wikipedia.org/wiki/Grady_Booch), [James Rumbaugh](https://fr.wikipedia.org/wiki/James_Rumbaugh) et [Ivar Jacobson](https://fr.wikipedia.org/wiki/Ivar_Jacobson)), comme on les appelait alors, avaient élaboré d'autres méthodologies. Ils se sont associés pour apporter plus de clarté aux programmeurs en créant de nouvelles normes. La collaboration entre Grady, Booch et Rumbaugh a renforcé les trois méthodes et a amélioré le produit final.

Les efforts de ces penseurs ont abouti à la publication des documents **UML 0.9 et 0.91 en 1996**. Des sociétés comme Microsoft, Oracle et IBM ont vu l'UML comme un élément critique pour leur développement futur. Elles ont donc mis en place des ressources, accompagnées en cela par de nombreuses autres sociétés et personnes, permettant de développer un langage de modélisation complet. Les Three Amigos ont publié **The Unified Modeling Language User Guide en 1999**, qui fut suivi d'une mise à jour comportant des informations sur l'UML 2.0 en 2005. La dernière version de la spécification validée par l'OMG (Object Management Group) est **UML 2.5.1 (2017).**



# 2. Principaux Diagrammes UML
 
### 1 Diagramme de classe

<p align="center">
	<img  align="left"  width="55%"  src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8a/LOM_base_schema.svg/440px-LOM_base_schema.svg.png">
</p>
Le diagramme de classe est l’outil de conception le plus utilisé dans le cadre de la programmation orienté objet (POO). Il permet de représenter les différentes classes, avec leurs attributs et méthodes, ainsi que les relations entre celles-ci (héritage, implémentation d’interfaces, appartenance …).
<br>
<br>
<br>
<br>

### 2 Diagramme de cas d'utilisation 

<p align="center">
	<img  align="left"  width="55%" src="https://lh3.googleusercontent.com/proxy/DYqi4YKFWhcDN6F5aAvDFPyQ84jxgrem1SERmWB1miE0jyJ_7TqV8Lt_5ZpbPM-cuyvl4ZMQghwNv0xeSmz7avfODQV6zuKcQfyIez_zcnQrwuJPdGrQbV2XDmvtwYPYvybP9a9zqFERCRSQp8MLSVf5WTyUuhjl-8kfdKfUkA">
</p>

En UML, un diagramme de cas d'utilisation peut servir à résumer les informations des utilisateurs de votre système (également appelés acteurs) et leurs interactions avec ce dernier. La création de ce type de diagramme requiert un ensemble de symboles et de connecteurs spécifiques.

<br>
<br>
<br>
<br>

### 3 Diagramme d'activités
<p align="center">
	<img  align="left"  width="40%"  src="https://www.researchgate.net/profile/Saad_Lissane_Elhaq/publication/261843860/figure/fig5/AS:714908584914945@1547458897180/Diagramme-dactivites-Gestion-des-commandes-client-Dans-le-diagramme-dactivite-de.ppm">
</p>
Le diagramme d'activité est un diagramme comportemental d'UML, permettant de représenter le déclenchement d'événements en fonction des états du système et de modéliser des comportements parallélisables (multi-threads ou multi-processus). Le diagramme d'activité est également utilisé pour décrire un flux de travail (workflow).

<br>
<br>
<br>
<br>
<br>
<br>

### 4 Diagramme d'objet 
<p align="center">
	<img  align="left"  width="55%"  src="https://laurent-audibert.developpez.com/Cours-UML/images/fig3_23.png">
</p>
Un diagramme d’objets peut être considéré comme un cas particulier d’un diagramme de classes. Les diagrammes d’objets utilisent un sous-ensemble des éléments d’un diagramme de classes afin de souligner la relation entre les instances de classes à un certain moment. Ils sont utiles dans la compréhension des diagrammes de classe. Ils ne montrent rien architecture différente de diagrammes de classes, mais reflètent la multiplicité et rôles.
<br>
<br>
<br>
<br>

### 5 Diagramme de composants
<p align="center">
	<img  align="left"  width="55%"  src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/97/UML_Diagram_Deployment.svg/1200px-UML_Diagram_Deployment.svg.png">
</p>
Le diagramme de composants décrit l'organisation du système du point de vue des éléments logiciels comme les modules (paquetages, fichiers sources, bibliothèques, exécutables), des données (fichiers, bases de données) ou encore d'éléments de configuration (paramètres, scripts, fichiers de commandes). Ce diagramme permet de mettre en évidence les dépendances entre les composants (qui utilise quoi).
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>


### 6 Diagramme états-transitions

<p align="center">
	<img  align="left"  width="55%"  src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/97/UML_Diagram_Deployment.svg/1200px-UML_Diagram_Deployment.svg.png">
</p>
Le diagramme d’état permet d’illustrer tous les état d’un objet/instance au cours de son cycle de vie et de décrire ses réactions à la réception de signaux ou d’utilisation de méthodes.
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

### 7  Diagramme de séquence 

<p align="center">
	<img  align="left"  width="55%"  src="https://lh3.googleusercontent.com/proxy/031PHRJ-PS4Q7cqex90Nb4n7FsX4BvfyS9fgepzTZ9NM6YUVYzHwlJMjZPC8lC_wxVYG5idw8zWAQkI_OutdKPgDMI8wCw5i1hpiyy8T_KSAT5kWOpyWavXDyHR4ME-askP79-1E7UcfXyNtLmrph7cbYk1ITURemDBMmg">
</p>
Le diagramme de séquence met en évidence les étapes et les interactions entre tous les acteurs d’un cas d’utilisation. Cela permet de visualiser la manière dont ils interagissent entre eux.

<br>
<br>
<br>
<br>
<br>
<br>


# 3. Pourquoi s’adapter à la modélisation mobile ?

Entre les années 2000 et 2010, nous avons pu voir se multiplier le nombre de terminaux mobiles. Tant dans leurs variétés que dans leurs puissances, ces terminaux ont fait un saut technologique spectaculaire et sont devenus quasiment omniprésents. En effet, ces smartphones doivent leur succès aux nombreuses applications qu’ils proposent. Par la création de ces nouvelles applications, l’informatique ambiante explore les liens entre l’Homme et l’information. Mais puisque la relation homme-machine devient mobile, elle explore également les liens entre l’Homme et son environnement et donc également, les liens entre l’information et l’environnement. Comme dans une modélisation non mobile, on décrit les exigences fonctionnelles(gestion, recherche, découverte détaillé)comme non fonctionnelles(qualité, performance).


#### sources
- [https://tel.archives-ouvertes.fr/tel-00805487/document](https://tel.archives-ouvertes.fr/tel-00805487/document)
- [http://www.univ-bejaia.dz/jspui/bitstream/123456789/610/1/Conception%20et%20r%C3%A9alisation%20d%27une%20application.pdf](http://www.univ-bejaia.dz/jspui/bitstream/123456789/610/1/Conception%20et%20r%C3%A9alisation%20d%27une%20application.pdf)
- autres sites groupes APSIO
- [https://www.lucidchart.com/pages/fr/langage-uml](https://www.lucidchart.com/pages/fr/langage-uml)
- https://www.omg.org/spec/UML

