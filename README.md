## test_symfony_dev

Les prérequis pour ce test sont :

 - d'avoir un environnement serveur Apache correctement configuré avec mysql.
 - Composer doit être installé
 - lancer un composer update pour installer les libs du projet
 - créer la database avec  php app/console doctrine:database:create 
 - importer le schema existant avec la commande  php app/console doctrine:schema:update
