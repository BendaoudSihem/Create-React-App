# Create-React-App
Create-React-App est un outil pour faciliter le développement d’applications web fondées sur React. L’idée est de générer automatiquement un squelette applicatif et de masquer la complexité potentielle de configuration des briques techniques associées : gestion de JavaScript moderne (ES2015+), bundling de notre application (avec Webpack), serveur de développement, génération de fichiers de production optimisés, etc.

# Installations
CRA est écrit en Node et nécessite Node 6+. Node.js est un environnement d'exécution JavaScript installable partout, qui permet d'écrire n'importe quel type de programme en JavaScript : outil en ligne de commande, serveur, application desktop, internet des objets (IoT),la version stable de Node est la 8.6.0. Assurez-vous d'avoir une version suffisamment récente.
# Create-React-App
 Sur l'invite de Commandes,  cmd.exe tapez la commande :
 npm install --global create-react-app
 
# Créer notre premier squelette d’application
Demandons à CRA de créer le squelette de notre application, qui s’appellera Memory. Ouvrez (si ce n'est déjà fait) un terminal, placez-vous si besoin dans un dossier de votre choix ( commande  cd ), puis saisissez la commande  : 
create-react-app memory

# Les fichiers produits
En examinant le contenu du dossier memory ainsi créé, nous voyons qu’en dehors du gros dossier node_modules, où toutes les dépendances ont été installées, on trouve déjà pas mal de choses.
On y trouve le point d’entrée de l’application ( src/index.js ), un premier composant (src/App.js ) avec ses styles à part et ses tests, ainsi qu'une page de support pour le tout (  public/index.html ). On y aperçoit également des éléments plus avancés qui sortent largement du cadre de ce cours (le service worker, le manifeste applicatif PWA…).

# Les commandes disponibles
Le message de fin de génération nous propose diverses commandes, dont  start  ,  test  et  build . On y trouve également la commande  yarn, qui est une alternative à la commande officielle  npm . Yarn est un client alternatif, mais ses avantages se sont considérablement réduits depuis la sortie de npm 5, qui a quant à elle d'autres forces uniques. Dans ce cours, nous resterons avec le npm officiel.

Voyons ce que donne notre squelette au démarrage.  Pour cela, il faudra lancer la commande: npm start  au sein d'une ligne de commande, depuis le répertoire dans lequel a été créé l'application.
