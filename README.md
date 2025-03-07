# Géolocalisation-Météo 🌍🌦️

## Description du projet :
Ce projet permet de gérer la géolocalisation et les données météo pour afficher dynamiquement les informations liées à une ville donnée. Il utilise deux API principales :
- **API ArcGIS** pour la géolocalisation des villes sur une carte 🗺️.
- **API OpenWeather** pour récupérer les données météo associées 🌡️.

Le but est d'afficher la carte et les données météo sur un site web et de permettre à l'utilisateur d'ajouter, supprimer et gérer des villes 🏙️.

## Technologies utilisées : 🛠️
- **Node.js** : pour le backend.
- **Express.js** : pour la création du serveur.
- **API ArcGIS** : pour la géolocalisation des villes.
- **API OpenWeather** : pour récupérer les données météo.
- **Base de données** (ex : MongoDB) : pour stocker les informations sur les villes.

## Fonctionnalités : ✨
- **Découverte de l'API ArcGIS** : Exploration et compréhension de l'API ArcGIS pour récupérer les informations géographiques 🗺️.
- **Création d'un compte ArcGIS** : Inscription sur ArcGIS et récupération de la clé d'API 🔑.
- **Affichage dynamique des cartes** : Implémentation des cartes interactives sur l'interface web en utilisant les données d'ArcGIS 🖥️.
- **Formulaire de saisie de ville** : Création d'un formulaire pour saisir le nom d'une ville et l'afficher sur la carte 🏙️.
- **Récupération des données météo** : Utilisation de l'API OpenWeather pour récupérer les informations météo en temps réel ☔.
- **Affichage des données météo** : Affichage dynamique des données météo (température, humidité, etc.) selon la ville choisie 🌡️.
- **Suppression d'une ville** : Fonctionnalité permettant de supprimer une ville de la liste ❌.
- **Basculer entre les cartes** : Permet de passer d'une carte à l'autre en fonction des villes sélectionnées 🔄.
- **Stockage des données** : Sauvegarde des informations sur les villes et leurs données météo dans une base de données 💾.

## Installation et lancement : 🚀
1. Clonez ce repository sur votre machine.
2. Installez les dépendances avec la commande `npm install`.
3. Ajoutez vos clés API ArcGIS et OpenWeather dans vos variables d'environnement 🔑.
4. Lancez le serveur avec `npm start` 🔥.

## Fonctionnalités principales : 🎯
- Visualisation dynamique des cartes 🗺️.
- Affichage des données météo en temps réel 🌡️.
- Gestion des villes : ajout, suppression, et basculement entre les cartes 🏙️🔄.
