# Rent it - Agence de Location de Voitures

Bienvenue sur le dépôt GitHub de Rent it, une application web pour la gestion d'une agence de location de voitures.
[Live website](https://rentitmcsi.000webhostapp.com/index.php) 

## Description

Rent it est une application web permettant aux utilisateurs de s'inscrire, de se connecter, de parcourir les voitures disponibles et de réserver des voitures en ligne. Cette application est développée en PHP et utilise MySQL pour la gestion de la base de données.

## Fonctionnalités

- Inscription et authentification des utilisateurs.
- Consultation des voitures disponibles à la location.
- Réservation de voitures en ligne.
- Gestion des utilisateurs et des réservations par l'administrateur.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé les éléments suivants :

- [XAMPP](https://www.apachefriends.org/index.html) (Inclut Apache, MySQL, PHP et phpMyAdmin)
- Un navigateur web (Google Chrome, Mozilla Firefox, etc.)

## Installation

Suivez les étapes ci-dessous pour installer et configurer l'application Rent it sur votre machine locale en utilisant XAMPP.

### 1. 
2. Copier les fichiers dans le répertoire XAMPP
Copiez les fichiers du projet cloné dans le répertoire htdocs de XAMPP. Par défaut, ce répertoire se trouve à l'emplacement suivant :

Windows : C:\xampp\htdocs\
macOS : /Applications/XAMPP/xamppfiles/htdocs/
Linux : /opt/lampp/htdocs/
3. Créer la base de données
Ouvrez XAMPP et démarrez les services Apache et MySQL.
Ouvrez votre navigateur web et accédez à phpMyAdmin en allant à l'adresse suivante : http://localhost/phpmyadmin/
Dans phpMyAdmin, créez une nouvelle base de données nommée carrent.
Importez le fichier carrent.sql situé dans le répertoire du projet pour créer les tables nécessaires. Pour ce faire :
Sélectionnez la base de données RENTIT.
Cliquez sur l'onglet "Importer".
Choisissez le fichier carrent.sql et cliquez sur "Exécuter".
