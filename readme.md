## Installation du projet
### Installation DB
- Télécharger mongoDB depuis www.mongodb.com
- Créer un répertoire db en local
- ouvrir un CMD et entrer

´´´
"C:\PATH_TO_BIN_FOLDER_MONGODB\mongod.exe" --dbpath (created db repo)

´´´

- MongoDB est maintenant installé et opérationnel

- Pour lancer le client :

´´´
"C:\PATH_TO_BIN_FOLDER_MONGODB\mongo.exe"
´´´

- Importer la base de données NoSQL du projet 
´´´

´´´

### Installation infrastructure JS
- Télécharger et installer la dernière version de node.js
- Installer cordova en local
´´´
sudo npm install -g cordova
´´´
- Créer l'application
´´´
cordova create pureRNG pureRNG 
´´´

- Ajouter les plateformes désirées
´´´
cordova platform add android
´´´
(possible avec ios et browser mais besoin d'une licence pour ios)

- Lancer un build de l'application
´´´
cordova build
´´´

- Si l'on veux build uniquement sur une certaine plateforme : 
´´´
cordova build android
´´´

- Si l'on plug un periphérique android via USB on peut alors lancer note app sur celui-ci
´´´
cordova run android
´´´

- Si l'on doit ajouter quelconque plugin à l'application 
´´´
cordova plugin add http://wwwleplugintrèschouette.com
´´´

- Créer un fichier Package.json
- Installer express
´´´
npm install express
´´´

- Installer Radium (pour le style)
´´´
npm install radium --save
´´´

- Installer ReactJS pour le front-end
´´´
npm install react --save
´´´

- Installer Redux 
´´´
npm install redux --save
´´´

- Installer React-redux 
´´´
npm install react-redux --save
´´´
