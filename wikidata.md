
Dans Wikidata, chaque entrée, qu’il s’agisse d’un concept, sujet ou objet, a sa propre page est représenté par plusieurs caractéristiques. Le constat du projet CITES : certaines espèces qui sont dans Wikidata ont déjà un identifiant CITES attribué.

  

Chaque élément de WikiData est constitué d’un ensemble de “Statements”, soit, des catégories de données qui caractérisent l’élément.

  

Exemple : Marie Curie

L’item “Marie Curie” sera représentée par plusieurs “statements” comme sa profession, sa photo, son lieu de naissance, ses prix et récompenses reçues, pays de nationalité etc.

  

Exemple : Paris

Statements : Continent, Pays, Capitale de, Population, Maire, Saint Patron, Devise etc..

  

Exemple pour les espèces : Chouette des pagodes

  

Statements : taxon name (nom de l’espèce en latin, référence scientifique), statut de conservation IUCN, taxon common name (nom commun de l’espèce), IUCN-ID

  

On pourra maintenant créer le statement CITES-ID

  

→ Possibilité de créer de nouvelles propriétés mais leur validation doit être validée par la communauté WikiData. Cela n’est pas immédiat et peut prendre quelques jours.

  

Dans la partie “Identifiers”, la priopriété “CITES Species+ ID” avait déjà été crée.

  

On pourrait ajouter d’autres propriétés comme : Statut juridique CITES, Couverture Pays, Photo si pas déjà. ( afin de savoir dans quel pays proviennent les espèces et quel est leur statut juridique de protection )

  

( Pour cela il faut que les données aient une licence domaine public. )

  

Dans notre cas, nous disposons de plusieurs fichiers contenant des information sur les espèces CITES, mais ils ne sont pas en usage libre.

  

L’objectif est maintenant de rajouter en bulk dans Wikidata les espèces manquantes de la base CITES. ( on a remarqué que seules certaines espèces y étaient .. )

  

Dans les données dont nous disposons, nous isolons : le nom scientifique de l’espèce (appelé taxon) qui est le nom utilisé en règle générale pour identifier les espèces + l’ID Cites qui est déjà crée. Puis nous créons un tableau de correspondance entre :

  

L’ID WikiData ←→ l’ID Cites

  

Ce, grâce à un outil appelé “Mix & Match”

  

→ import dans Mix'n'Match [https://tools.wmflabs.org/mix-n-match/import.php](https://tools.wmflabs.org/mix-n-match/import.php)

  

![Capture d’écran 2017-01-28 à 13.11.20.png](https://lh4.googleusercontent.com/0cMtCBLVQbJHQbAaA5Abq2ehD2ADzVyou6bNoWCLEHuFx9Eh_qpy3tnjK5hzc5LfeUIaoLa3KnNnAHgAN6QArwjSQBdZMKg24gz0jxD0W-7Xlzos8uBjJgT-LW8mHkUWJwUmIm4P)

  

→ Synchro automatique → ~18 000 entrées déjà présentes dans Wikidata avec le bon identifiant sur ~21 000

→ Matching semi-automatique : [https://tools.wmflabs.org/mix-n-match/#/catalog/364](https://tools.wmflabs.org/mix-n-match/#/catalog/364)

  

![Capture d’écran 2017-01-28 à 13.12.37.png](https://lh5.googleusercontent.com/zBci5QTwyx4S7vOKyy9BVF7D_AfSvjGzAbjkKvFmT5P78ZACQBWZ5HGl-MqvoIoY55bb71QUUFUAzQb8wl-efkjFKbWFUtozdIqGPa3Bn6gTeVrLARw6OKL6XdEN8PtzEceLjsZ3)

  

Résultat : il faut maintenant

  

-   Valider les 900 entrées qui n’ont pas été identifiées (user matched: il existe des taxons candidats existant mais l’outil Mix and Match n’a pas réalisé d’auto match)
    
-   Créer le 2000 entrées manquantes (unmatch : à priori le taxon n’existe pas dans wikidata).
    

  
  

Exemple de visualisation :

-   Reasonator (canis lupus) [https://tools.wmflabs.org/reasonator/?q=Q18498&lang=fr](https://tools.wmflabs.org/reasonator/?q=Q18498&lang=fr)
    

  

![Capture d’écran 2017-01-28 à 13.08.47.png](https://lh4.googleusercontent.com/PRbuFg1zyvTIZ5KFDozgnZVLZkZfvnUaWJUHvPWSdZYA5KfZGB0e_kwc4VfXSWDludsbl9qFqvPUxXDMKgYEiSiNBMRB3HwwA4zqoUM9zou6VuBKsB0iqq0AubvUxgB3HjB0CcVT)

  

- Sparql : [http://tinyurl.com/h589574](http://tinyurl.com/h589574)

- Github : [https://github.com/okfnfr/CITES-biodiversity](https://github.com/okfnfr/CITES-biodiversity)

  

# Outils et liens

Projet Taxonomie sur Wikidata [https://www.wikidata.org/wiki/Wikidata:WikiProject_Taxonomy](https://www.wikidata.org/wiki/Wikidata:WikiProject_Taxonomy)

### Les données

  

Table TableSPECIES+.csv : table des espèces cites avec statuts cites et pays aires de distribution, source SPECIES + (WCMC-UNEP)

Table suspension_cites.csb : table des suspensions CITES, source WCMC-UNEP

Table Sources de production.csv : table des sources de production issue du règlement cites, source MNHN

Table But_utilisation.csv : table des buts d'utilisation issue du règlement cites, source MNH
  


