# Racoin
lien vers le projet : https://github.com/bnj35/racoin

## Objectif du projet

Racoin est une application web conçue pour gérer des annonces.

## Prérequis

Avant de commencer la maintenance, il est essentiel de comprendre les éléments suivants :

### Langages utilisés

- PHP - Framework : Slim (version 4)
- HTML - Framework : Twig (version 3), CSS - Framework : SASS, JavaScript : Jquery (pour le front-end)

### Frameworks

- Slim (version 4)
- Twig (version 3)
- Illuminate Database (version 8)

### Bases de données

- Le projet utilise une base de données (où ?) SQL. Les fichiers `apikey.sql` et `bdd.sql` contiennent les scripts nécessaires pour créer et initialiser la base de données.

## Installation

1. Clonez le dépôt :
    ```sh
    git clone https://gitlab.univ-lorraine.fr/sauder2/racoin.git
    cd racoin
    ```

2. Installez les dépendances avec Composer :
    ```sh
    composer install
    ```

3. Configurez la base de données :
    - Importez les fichiers [apikey.sql] et [bdd.sql] dans la bdd.

4. Configurez les paramètres de connexion à la base de données dans [connection.php].
   
## Utilisation

### Avec Docker

1. Assurez-vous que Docker et Docker Compose sont installés.
2. Lancez les conteneurs :
    ```sh
    docker-compose up -d
    ```

## Maintenance et Améliorations
   
1. **Améliorations** :

### TODO 

- pas de page compte pro -> important après
- créer la bdd -> ✅
- créer le fichier config.ini -> ✅
- connecter tout le tsintouin -> ✅
- mettre a jour les dépendences -> ✅ 
- possiblement changer les dépendences pour des plus récentes 
- jquery en local pas top -> a mettre dans un package meme version puis monter a la dernière
- mettre sass dans un package json pour faciliter la maintenance et l'update du style
- htaccess autorise l'accès a tout ? server apache ? -> dockerfile passé en php -> pas résolu
- refaire l'archi (crade) -> long à faire -> devrait faciliter celui du dessus
- faire un dossier sql pour éviter d'avoir les trucs qui se baladent 
- mettre a jour le gitignore en conséquence
- importer la font dynamiquement 
- 

