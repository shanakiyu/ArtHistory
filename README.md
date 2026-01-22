Réseau & Visualisation : Chercheurs en Histoire de l'Art (USA ↔ France )
Ce projet est une visualisation interactive de données explorant les connexions, les sujets de recherche et les collaborations institutionnelles des historiens de l'art affiliés à 6 grandes universités américaines, avec un focus particulier sur leurs liens avec la France.

Voir la visualisation en ligne : https://shanakiyu.github.io/ArtHistory/

Description du Projet
L'objectif est de cartographier la communauté de recherche en histoire de l'art pour comprendre :

Qui étudie quoi ? (Sujets majeurs vs sujets de niche).

Qui étudie la France ? (Sujets liés à l'art français, l'histoire, la culture).

Qui collabore activement ? (Co-publications avec des institutions françaises comme le CNRS, Musées, Universités).

La visualisation permet de filtrer par université, par type de sujet, et de mettre en évidence les "ponts" entre les chercheurs et les thématiques françaises.

Fonctionnalités
Graphe Interactif (D3.js) : Nœuds auteurs et sujets liés par des liens de force.

Dashboard Analytique : Statistiques en temps réel sur les nœuds visibles.

Filtres Avancés :

Filtrer par type (Chercheurs, Sujets Généraux, Sujets France).

Slider de "Degré" pour nettoyer le graphe des sujets mineurs.

Barre de recherche avec Focus Zoom automatique.

Design Intuitif :

Losanges Turquoise : Sujets liés à la France.

Glow autour du noeud : Collaborations institutionnelles avérées.

Couleurs : Code couleur par université d'appartenance.

Structure du Répertoire
index_ultimate.html : Le fichier principal. Contient tout le code (HTML, CSS, JS) et les données JSON intégrées. Il est autonome et fonctionne hors ligne.

FINAL_ARTHISTORY_DONE.csv : Le dataset source nettoyé.

scripts/ : Scripts Python utilisés pour le nettoyage des données et la génération du graphe (optionnel si tu les mets).

Comment l'utiliser ?
Clonez ce dépôt ou téléchargez le fichier index_ultimate.html.

Ouvrez simplement le fichier dans n'importe quel navigateur web moderne (Chrome, Firefox, Edge).

Aucune installation de serveur ou de Python n'est requise pour la lecture.

Mentions Légales & RGPD (Protection des Données)
Cadre du projet : Ce projet a été réalisé dans un cadre strictement universitaire et pédagogique. Il s'agit d'un exercice de recherche en Humanités Numériques visant à expérimenter les techniques de visualisation de réseaux.

Nature des données : Les données présentées dans cette visualisation concernent des chercheurs et leurs travaux académiques. Elles proviennent exclusivement de sources publiques et accessibles librement (Open Data), notamment :

OpenAlex (Index bibliographique ouvert).

Sites web institutionnels des universités.

Conformité RGPD : Conformément au Règlement Général sur la Protection des Données (RGPD) et aux directives du Délégué à la Protection des Données (DPD) de l'Université :

Usage Non-Commercial : Ces données ne sont utilisées qu'à des fins d'analyse statistique et de représentation graphique dans un but d'étude.

Données Professionnelles : Seules les informations liées à l'activité professionnelle et publique des chercheurs (nom, affiliation, publications, sujets de recherche) sont traitées. Aucune donnée sensible ou privée n'est collectée.

Droit d'accès et de retrait : Toute personne concernée souhaitant le retrait de ses informations de cette base de données expérimentale peut en faire la demande en contactant les auteurs du dépôt via GitHub.

Ce projet respecte l'équilibre entre la liberté de la recherche académique et le respect de la vie privée des auteurs cités.

Projet réalisé par [Emna Ben Ameur, Lélie Chénouga, Tabara Guissé, Safia Lamri et Nina Vivier Barte] - [2026]
