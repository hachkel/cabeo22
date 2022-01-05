# MyCabeo
CRM pour les cabinets des experts comptables.

Réalisé avec Symfony 4 et VueJS

Base de données : MySQL/MariaDB

Bundles: FOSUserBundle, GOSWebSocketBundle

Packages Yarn: webpack-encore, node-sass, sass-loader, vue, vue-router, vuex, momentjs, favico.js, lodash, webpack-bundle-analyzer

Steps:  
    - composer install  
    - yarn install  
    - yarn run encore production  
    - php bin/console gos:websocket:server  
    - php bin/console server:run  
