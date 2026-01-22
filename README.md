# Réseau & Visualisation : Chercheurs en Histoire de l'Art (USA ↔ France)

> **Projet de Humanités Numériques - 2026**

Ce projet est une visualisation interactive de données explorant les connexions, les sujets de recherche et les collaborations institutionnelles des historiens de l'art affiliés à 6 grandes universités américaines, avec un focus particulier sur leurs liens avec la France.

### [Voir la visualisation en ligne](https://shanakiyu.github.io/ArtHistory/)

---

## Description du Projet

L'objectif est de cartographier la communauté de recherche en histoire de l'art pour comprendre :

* **Qui étudie quoi ?** (Identification des sujets majeurs vs sujets de niche).
* **Qui étudie la France ?** (Sujets liés à l'art français, l'histoire, la culture).
* **Qui collabore activement ?** (Co-publications avec des institutions françaises comme le CNRS, Musées, Universités).

La visualisation permet de filtrer par université, par type de sujet, et de mettre en évidence les "ponts" entre les chercheurs américains et les thématiques françaises.

## Fonctionnalités

### Visualisation & Dashboard
* **Graphe Interactif (D3.js) :** Nœuds auteurs et sujets liés par des liens de force.
* **Dashboard Analytique :** Statistiques en temps réel sur les nœuds visibles dans le panneau latéral.

### Filtres Avancés
* **Filtrage par type :** Affichez ou masquez les Chercheurs, les Sujets Généraux ou les Sujets France.
* **Slider de "Degré" :** Permet de nettoyer le graphe en masquant les sujets mineurs pour réduire le bruit visuel.
* **Barre de recherche :** Fonction avec **Focus Zoom** automatique sur le chercheur ou le sujet tapé.

### Design Intuitif
*  **Losanges Turquoise :** Sujets liés spécifiquement à la France.
*  **Glow (Lueur) :** Indique une collaboration institutionnelle avérée avec la France.
*  **Code Couleur :** La couleur des nœuds correspond à l'université d'appartenance.

---

## Structure du Répertoire

* `index_ultimate.html` : **Le fichier principal.** Contient tout le code (HTML, CSS, JS) et les données JSON intégrées. Il est autonome et fonctionne hors ligne.
* `FINAL_ARTHISTORY_DONE.csv` : Le dataset source nettoyé et enrichi.
* `scripts/` : Scripts Python utilisés pour le nettoyage des données et la génération du graphe.

---

## Comment l'utiliser ?

1.  **Clonage :** Clonez ce dépôt ou téléchargez le fichier `index_ultimate.html`.
2.  **Lancement :** Ouvrez simplement le fichier dans n'importe quel navigateur web moderne (Chrome, Firefox, Edge).
3.  **Aucune installation** de serveur ou de Python n'est requise pour la lecture de la visualisation.

---

## Mentions Légales & RGPD (Protection des Données)

### Cadre du projet
Ce projet a été réalisé dans un cadre strictement universitaire et pédagogique. Il s'agit d'un exercice de recherche en Humanités Numériques visant à expérimenter les techniques de visualisation de réseaux.

### Nature des données
Les données présentées dans cette visualisation concernent des chercheurs et leurs travaux académiques. Elles proviennent exclusivement de sources publiques et accessibles librement (**Open Data**), notamment :
* **OpenAlex** (Index bibliographique ouvert).
* Sites web institutionnels des universités.

### Conformité RGPD
Conformément au Règlement Général sur la Protection des Données (RGPD) et aux directives du Délégué à la Protection des Données (DPD) de l'Université :

1.  **Usage Non-Commercial :** Ces données ne sont utilisées qu'à des fins d'analyse statistique et de représentation graphique dans un but d'étude.
2.  **Données Professionnelles :** Seules les informations liées à l'activité professionnelle et publique des chercheurs (nom, affiliation, publications, sujets de recherche) sont traitées. Aucune donnée sensible ou privée n'est collectée.
3.  **Droit d'accès et de retrait :** Toute personne concernée souhaitant le retrait de ses informations de cette base de données expérimentale peut en faire la demande en contactant les auteurs du dépôt via GitHub.

*Ce projet respecte l'équilibre entre la liberté de la recherche académique et le respect de la vie privée des auteurs cités.*

---

### Projet réalisé par
**Emna Ben Ameur, Lélie Chénouga, Tabara Guissé, Safia Lamri et Nina Vivier Barte**
*Université Paris Sciences et Lettres - 2026*
