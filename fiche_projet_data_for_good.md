# Fiche Projet Data for Good


## Description du projet

Le trafic d’espèces menacées, animales ou végétales, est le quatrième commerce illégal dans le monde après celui des armes, des drogues et des médicaments. Il permet de financer le terrorisme dans certains pays et contribue à l’extinction des espèces. En réponse, un cadre international de collaboration a été mis en place, la CITES, qui signifie Convention sur le commerce international des espèces de faune et de flore sauvages menacées d’extinction.

La Convention CITES définit une liste des espèces menacées par pays, ainsi que les mesures de protection associées à appliquer, comme l’interdiction de la vente, ou la délivrance de certificats ou permis d’importation.

En France, c’est le Ministère des Affaires Étrangères qui coordonne la lutte contre le trafic illégal d’espèces à l’international, en lien avec d’autres institutions telles que les Douanes, le Ministère du Développement Durable mais également le Museum d’Histoire Naturelle et le secrétariat international CITES basé à Genève au sein de l’UNEP, l’Agence des Nations Unis pour l’Environnement.

L’objectif de la CITES est de garantir que le commerce international des animaux et plantes, vivants ou morts, ainsi que de leurs parties et de leurs produits dérivés ne nuise pas à la conservation de la biodiversité et repose sur une utilisation durable des espèces sauvages.

Les peines applicables en cas d’absence des permis ou certificats requis par la réglementation CITES ou en cas d’infractions commises vont de 2 ans d’emprisonnement et une amende de 150 000 euros à 7 ans d’emprisonnement en cas de délit en bande organisée

Ces sanctions varient selon le degré d’extinction ou de vulnérabilité des espèces, ainsi qu’en fonction de leur provenance géographique, et des règlementations en vigueur dans le territoire d’importation (UE, France, Cameroun, etc..)

## Naissance du projet

Le projet est porté par l’association Open Knowledge France, qui, suite à un hackathon réalisé en janvier 2017 au Ministère des Affaires Étrangères, a visé à constituer une base de données d'espèces animales et végétales menacées issues de la liste CITES, et à la verser sur Wikipedia et Wikidata. Convaincus que les communs numériques ont un rôle fondamental à jouer dans la vulgarisation d’information scientifique aussi importante que les espèces menacées, nous souhaitons les nourrir de données recoupées, propres et utiles au plus grand nombre.

À l’heure actuelle, le touriste qui se promène sur un marché local et qui fait une requête sur son moteur de recherche préféré aura peu de chance d’obtenir directement l’information sur le statut de protection de l’espèce et les risques juridiques encourus.

Il en va de même pour les agents des douanes qui, faute de base de donnée spécifique, n’ont pas d’outils appropriés pour facilement identifier les espèces protégées et adopter la bonne réponse.

## Les enjeux de l’accès aux données

L’une des principales difficultés de la mise en œuvre de l’accord CITES est de pouvoir identifier précisément quelles sont les espèces menacées et les sanctions à appliquer en fonction du pays.

L’objectif est à la fois de

-   Mieux sensibiliser les potentiels acteurs du trafic (vendeurs, acheteurs, touristes, etc.) sur les sanctions encourues, et ce en fonction des pays d’importation et de provenance
    
-   Pouvoir mieux informer les différents intervenants dans la lutte contre le trafic, notamment les autorités de contrôle, les acteurs institutionnels, associatifs, mais également la communauté scientifique.
    

## Les données

Il existe déjà un grand nombre d’informations sur la protection des espèces menacées, notamment le registre [Species+](https://speciesplus.net/) qui répertorie les espèces et leur statut juridique par pays. Cependant, ce registre est plutôt destiné aux experts, moins aux agents de contrôle ou aux acteurs du commerce, et n’a pas pour fonction l’identification d’une espèce.

Cette base de données est téléchargeable mais disponible dans une licence non commerciale ce qui empêche son versement sur les bases wiki commons par exemple. Elle dispose par ailleurs d’une API publique.

Le résultat de notre action sur Wikidata: nous avons ajouté environ 21 000 espèces répertoriées dans la base CITES sur la base de données communes wikidata en leur ajoutant l’identifiant “cites”, ce qui est une première étape pour ensuite associer d’autres données telles que le statut juridique, les pays, les sanctions encourues, etc  

Ci-dessous un exemple de requête Wikidata sur les identifiants CITES illustrant l’hétérogénéité des illustrations.Cliquer sur le lien suivant [http://tinyurl.com/h589574](http://tinyurl.com/h589574) puis sur sur ‘run’ pour voir le résultat vous même.


![](https://lh5.googleusercontent.com/6R_I3McmpFrfRDq8b8vetLYv6T2vH8mpsMODLXVqYbrm6uBcMZz8dGritsk11hf0r6yjCJNNeiKhNE7UREHSzUuDdz3DCbV5VmMZrtEEPFXpLHJatjCMhwkMSU0OqAfeV67pprhe)
  

[Voir également l’annexe en fin de document à ce sujet](https://docs.google.com/document/d/19KMcwqeJdauGqaNL-7fdujrmjokjTImWUrrppHoZKmg/edit#bookmark=id.9s17owkdl95l)

## Le travail des bénévoles

### Intégration de données :

-   Constituer une première base de données qui inclut des informations sur les taxons (espèces), leur couverture géographique, leur statut juridique suivant la convention CITES et les pays membres, les illustrations, ainsi que des données sur les clés de détermination.
    

  

-   Explorer les possibilités offertes par les communs numériques, notamment wikidata, wiki commons et encyclopedia of life et les bases de données telles que UICN pour améliorer la collecte, qualité et diffusion des données sur les espèces et leur statut juridique.
    

### Développement d’outils et applications numériques

Nous avons réalisé l’année dernière un prototype d’application web permettant d’effectuer une recherche très basique dans une base de données limitées à une centaine d’espèces : [http://cites.okfn.fr/en/home/](http://cites.okfn.fr/en/home/)

  

Outre le fait que l’application soit une bêta, il apparaît clairement que les données alimentant les fiches individuelles des espèces sélectionnées sont limitées en information.

  

Si des bénévoles sont plus intéressés par une amélioration du développement de la plateforme que par la manipulation des données et la constitution d’une base de données, nous sommes évidemment preneur. Idéalement une équipe avec plusieurs profils pourrait travailler en parallèle.

## Objectifs à 3 mois

-   Contribuer à Wikidata en améliorant les données sur les espèces avec les informations CITES comprenant les noms et familles de taxons, catégories, statut juridique cites, pays d’origine..
    
-   Améliorer notre prototype avec des fiches espèces plus fournies ([Voir l’annexe sur les fiches Taxon existantes](https://docs.google.com/document/d/19KMcwqeJdauGqaNL-7fdujrmjokjTImWUrrppHoZKmg/edit#bookmark=id.xsql615wnqhm))
    

## Perspectives

Le projet est soutenu par le Ministère de l’Europe et des Affaires Étrangères qui s’est engagé à en faire la promotion et le porter à la connaissance de toute organisation ou structure susceptible de le faire avancer. Nous pouvons envisager à l’issue des 3 mois une présentation du résultat de notre travail au Ministère et aux autres partenaires

  

Le Ministère facilite également la prise de contacts avec les partenaires originaux du projet : le Muséum national d’Histoire Naturelle, les douanes (DGDDI), le secrétariat CITES basé à Genève et l’UNEP-WCMC basé à Cambridge et qui gère la base Species+.

  

Enfin, des contacts ont été pris pour une collaboration avec des partenaires au Royaume Uni, notamment Open Data Institute et WildLabs.

## Bonus pour les futur.es bénévoles

L’association Open Knowledge France propose d’organiser un week-end de collaboration dans un lieu emblématique associé à la protection de la biodiversité et réunissant des experts.

  

Par ailleurs, tous les apéros sont pris en charge les mercredi soirs :)

## Quel est notre rôle ou statut dans le projet ? Open Knowledge France est-il décisionnaire s'il faut prendre des décisions ?

L’association Open Knowledge France a une totale liberté d’action dans ce projet. Nous sommes décisionnaires sur les choix techniques et de manipulation/présentation des données qui appartiennent au périmètre du projet, à savoir les données CITES des espèces dont le commerce est réglementé, et nous souhaitons donner souplesse et liberté également aux bénévoles qui nous rejoindront.

  

Notre rôle est d’assurer une cohérence dans les orientations du projet, ainsi que d’apporter les contacts qui ont les connaissances nécessaires en droit public et international, ou en sciences de conservation des espèces, et qui pourront intervenir pendant le déroulement de l’activité. Nous pouvons coordonner le travail entre différents partenaires et experts déjà mobilisés sur ce projet, en France comme à l’international.

  

Si un plaidoyer doit être fait pour l’ouverture de données ou l’utilisation de communs numériques à des fins de vulgarisation scientifique, l’association est également disposée à l’assurer.

## De quels compétences avons-nous besoin pour être épaulés sur ce projet ?

En priorité des personnes avec des compétences en data science, si possible avec un intérêt pour les questions de biodiversité, capables de participer à la définition de la problématique et des solutions, identifier et qualifier les sources de données nécessaires, et réaliser un travail d’intégration de données, incluant des contenus images, sur une base de données unifiée.

Des compétences en web sémantique et gestion et utilisation de données sur wikidata serait également très utiles.

Enfin des personnes avec des compétences en développement ou design web sont également les bienvenues, afin de proposer, voire développer un site ou une application pour améliorer ou remplacer le prototype existant.

## Équipe projet

L’équipe projet est composée de :

 -   Pierre Chrzanowski, co-fondateur de l’association Open Knowledge France et Digital Development Specialist pour la Banque Mondiale. Il est également membre de Open Data for Resilience Initiative (opendri.org) qui aide les pays et institutions internationales à appliquer les principes de l’open data et de l’open source pour la gestion des risques de catastrophe et l’adaptation au changement climatique. Pierre est basé en région parisienne.
    
-   Cécile Le Guen, membre de Open Knowledge France et consultante à Datactivist, basée à Paris et spécialisée également sur les questions d’open data et de gouvernance des données.

-   D
