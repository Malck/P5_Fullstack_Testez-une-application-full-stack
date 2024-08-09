# P5_Fullstack_Testez-une-application-full-stack

## Installation de la base de données

1. Assurez-vous d'avoir une instance de la base de données (par exemple, MySQL) installée et configurée sur votre machine.
2. Création de la base de données fourni dans le dossier `ressources/sql`.
3. Renseignez les informations de connexion à la base de données dans le fichier de configuration `application.properties`.

## Installation de l'application

1. Avoir les dépendances nécessaires installées : Java, Node.js, Maven.
2. Clonez ce dépôt sur votre machine locale.
3. Accédez au répertoire du projet back-end et exécutez la commande `mvn clean install`.
4. Accédez au répertoire du projet front-end et exécutez la commande `npm install`.

## Lancement de l'application

1. Pour démarrer l'application front-end : aller dans le répertoire du projet frontet exécutez la commande `npm run start` .
2. Pour démarrer l'application back-end : aller dans le répertoire du projet back et exécutez la commande `mvn spring-boot:run` .

### Tests end-to-end Cypress

1. Aller au répertoire du projet front-end et exécutez la commande `npm run e2e` pour lancer les tests.
2. Pour afficher le rapport de couverture, exécutez la commande `npm run e2e:coverage`.

### Tests unitaires et d'intégration front-end Jest

1. Aller au répertoire du projet front-end et exécutez la commande `npm run test`.
2. Pour afficher le rapport de couverture, exécutez la commande `npm run test -- --coverage`.

### Tests unitaires et d'intégration back-end JUnit et Mockito

Aller au répertoire du projet back-end et exécutez la commande `mvn clean test`.
