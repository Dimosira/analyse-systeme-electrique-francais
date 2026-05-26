
# Données utilisées dans le projet
# Données du projet

Les données utilisées dans ce projet proviennent de la plateforme open data éCO2mix de RTE (Réseau de Transport d’Électricité).

## Source des données

- Source : RTE – éCO2mix
- Type : Données énergétiques régionales consolidées
- Période : 2013 – 2024
- Granularité temporelle : demi-heure
- Maille géographique : régions françaises

## Variables principales

- consommation
- nucléaire
- hydraulique
- thermique
- solaire
- éolien
- bioénergies
- échanges physiques

## Volume de données

Le jeu de données complet contient plus de 2,5 millions de lignes.

Les données complètes ne sont pas directement stockées sur GitHub en raison de leur taille.

## Accès aux données

Les données peuvent être téléchargées depuis :

-	https://opendata.reseaux-energies.fr/explore/dataset/eco2mix-regional-cons-def/information/?disjunctive.libelle_region&disjunctive.nature&sort=-date_heure
-	https://www.data.gouv.fr/fr/datasets/donnees-eco2mix-regionales-consolidees-et-definitives-janvier-2013-a-mai-2022/#description

## Prétraitements réalisés

- Nettoyage des valeurs manquantes
- Suppression des doublons
- Conversion des variables temporelles
- Création d’indicateurs énergétiques
- Construction de variables d’analyse régionale
