# Projet 01 – SQL : interroger une base de réservations de vols

## Objectif du projet

Ce projet a pour objectif de construire et d’interroger une base de données de réservations de vols.

À travers ce projet, je vais pratiquer les bases du SQL, notamment :

- la création de tables ;
- l’insertion de données ;
- les requêtes simples ;
- les filtres avec `WHERE` ;
- les agrégations avec `COUNT`, `AVG`, `SUM`, etc. ;
- les jointures entre plusieurs tables ;
- les sous-requêtes.

## Contexte

En attendant un vol à l’aéroport de Paris Charles de Gaulle, je me mets dans la peau d’une analyste Data chargée d’explorer le système de réservations de l’aéroport.

La base de données contient des informations sur :

- les passagers ;
- les vols ;
- les réservations.

## Schéma de la base de données

![Schéma de la base de données](assets/base_de_donnees.png)

## Structure du projet

```text
projet_01_sql_reservations_vols/
│
├── README.md
├── assets/
│   ├── projet_01_image.png
│   └── base_de_donnees.png
│
├── sql/
│   ├── 01_create_tables.sql
│   ├── 02_insert_data.sql
│   └── 03_queries.sql
│
└── database/
    └── .gitkeep