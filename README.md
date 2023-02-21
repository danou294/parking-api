# Projet Parking api

Ce projet React est la création d'une api recensant tout les parkings de Nantes et leurs status.

## Prérequis
Avant d'installer le projet, vous devez vous assurer d'avoir les éléments suivants installés sur votre machine :
***

- Java/kit jdk
- Maven

## Installation
- ### Étape 1 : Cloner le projet
-
Ouvrez un terminal et exécutez la commande suivante :

```
git clone https://github.com/danou294/parking-api.git
```
***

- ### Étape 2 : Installer les dépendances + compiler le projet
Ouvrez un terminal à la racine du projet et exécutez la commande suivante :

```
mvn clean install
```

***

- ### Étape 3 : Lancer le projet
Ouvrez un terminal à la racine du projet et exécutez la commande suivante :

```
mvn springboot run
```

L'api sera accessible et consommable à l'adresse http://localhost:8080/api/parkings.

