# Introduction

Objectifs de la présentation : Présenter le projet Gaïa et son rôle dans la gestion des données géographiques à l'Insee avec le moteur de recherche.
Contexte et importance : Besoin d’un référentiel fiable et stable pour répondre aux usages internes (ex. : programme Resil + d'autres utilisateurs du ssp)

# Présentation du Projet Gaïa
Qu'est-ce que Gaïa ? : Présentation du référentiel et des objectifs.
Sources de données : Cadastre, recensement, Base Adresse Nationale.
Identifiant unique : Importance de l’identifiant pérenne pour la stabilité et la traçabilité des adresses dans le temps.

# Usages des Données d’Adresses
Besoins des utilisateurs : Utilisation des adresses dans des projets comme Resil, où il est essentiel de retrouver le bon identifiant même à partir de libellés d'adresses contenant des fautes.
Lien entre les adresses : Relation entre adresses sur une même parcelle ou bâtiment (création de “lieux géographiques”).

# Moteur de Recherche ElasticSearch : L’Innovation au Cœur du Projet Gaïa
Pourquoi un moteur de recherche ? : Importance de l’identification rapide et de la mise à jour efficace des adresses.
Présentation d'ElasticSearch : indexation, mappings/settings, requetes + avantages par rapport à une méthode sans index inversé.
Description du moteur développé : Gestion des synonymes, résilience aux fautes dans les libellés, recherche en ngrams...
Validation des requêtes mises en place : jeu de test pasrau x resil x majic

# Avancement et Résultats Actuels du Projet
État d’avancement du référentiel : la mise à jour des données qui fonctionne bien
Tests et validations du moteur de recherche : Retours d’expériences, améliorations continues, et exemples de résultats obtenus.
Perspectives de développement : Améliorations prévues pour le moteur de recherche, nouvelles sources à intégrer.

# Conclusion et Perspectives
Résumé des bénéfices de Gaïa pour l'Insee : Impact sur la qualité et l’accessibilité des données d’adresses.
Prochaines étapes : Optimisation du moteur ElasticSearch, renforcement des liens avec les autres projets géographiques.
