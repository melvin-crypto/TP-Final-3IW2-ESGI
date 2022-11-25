# Projet réalisé par Melvin PIERRE et Paul BECUE

On peut retrouver les 2 services php, nginx ainsi que la base de données dans le docker-compose.
Les 2 .env des deux serveurs nginx sont relié à la meme base de données.

Dans le docker-compose on peut également retrouver l'automatisation du composer et des installations mais il est important de faire quand meme les npm install et npm run dev dans chacun des dossiers blog sinon l'affichage css ne marche pas correctement.

Dans le dockerfile on peut retrouver la librairie, l'activation du mysql et le composer.

Pour finir on peut retrouver l'intégralité des users crée dans la base de données mysql accessible par phpmyadmin sous le port 3000 avec le serveur db, le user melvin et le mot de passe maloss.
