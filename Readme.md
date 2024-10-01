# Projet Base de Données Tifosi

Ce projet consiste en la création et la gestion d'une base de données pour le restaurant de Street-Food italien "Le Tifosi".

## Structure du Projet

Le repository contient les éléments suivants :

- `sql_scripts/` : Dossier contenant tous les scripts SQL
  - `import_database.sql` : Script pour créer la structure de la base de données
  - `insert_test_data.sql` : Script pour insérer les données de test
  - `backup_tifosi.sql` : Sauvegarde complète de la base de données

## Installation et Utilisation

1. Créez une base de données MySQL nommée "tifosi".
2. Exécutez le script `import_database.sql` pour créer les tables.
3. Exécutez le script `insert_test_data.sql` pour insérer les données de test.

## Structure de la Base de Données

La base de données comprend les tables suivantes :
- `marque` : Stocke les informations sur les marques de boissons
- `boisson` : Contient les détails des boissons disponibles
- `client` : Informations sur les clients
- `focaccia` : Liste les différentes focaccias proposées
- `ingredient` : Répertorie tous les ingrédients utilisés
- `menu` : Détails des menus proposés
- `acheter` : Table de liaison entre clients et focaccias achetées
- `payer` : Table de liaison entre clients et menus payés
- `contient` : Table de liaison entre menus et boissons
- `comprendre` : Table de liaison entre focaccias et ingrédients

## Fonctionnalités

- Gestion des focaccias et de leurs ingrédients
- Suivi des boissons et de leurs marques
- Gestion des clients et de leurs achats
- Gestion des menus et de leur composition
- Possibilité d'ajouter, modifier ou supprimer des éléments dans chaque table

## Développement

Ce projet a été développé dans le cadre d'un devoir sur la conception de bases de données avec MySQL.

## Auteur

Anne Villette