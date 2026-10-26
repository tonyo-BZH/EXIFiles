# EXIFiles
<img src="https://github.com/tonyo-BZH/EXIFiles/blob/main/logos/titre.png" alt="logo" width="400">  

**EXIFiles** est une application web permettant d’examiner les métadonnées contenues dans des fichiers, notamment les photographies, les vidéos et les fichiers audio.

La particularité de cette application est qu'elle propose une géolocalisation et la génération de parcours dans une carte intégrée. De plus elle fonctionne localement dans un navigateur sans installation ni compte.

L’application aide à comprendre quelles informations un fichier peut révéler : date de prise de vue, caractéristiques du média, coordonnées GPS, informations IPTC/XMP ou encore tags audio. Elle peut notamment servir à l’analyse de fichiers, à la sensibilisation à la vie privée numérique et à des activités pédagogiques autour des métadonnées.  

<img src="https://github.com/tonyo-BZH/EXIFiles/blob/main/logos/icone.png" alt="icone" width="100">  

Visitez le [WIKI](https://github.com/tonyo-BZH/EXIFiles/wiki)pour plus de détails.



## Captures d'écran

<img src="https://github.com/tonyo-BZH/EXIFiles/blob/main/captures/clair.jpg" alt="logo" width="300"> <img src="https://github.com/tonyo-BZH/EXIFiles/blob/main/captures/sombre.jpg" alt="logo" width="300"> <img src="https://github.com/tonyo-BZH/EXIFiles/blob/main/captures/g%C3%A9olocalisation.jpg" alt="logo" width="300"> <img src="https://github.com/tonyo-BZH/EXIFiles/blob/main/captures/parcours.jpg" alt="logo" width="300">

## Fonctionnalités

- **Analyse de fichiers en local** : déposer des fichiers ou un dossier dans l’application.
- **Vue d’ensemble** : consulter le nom, le type, la taille, la date de modification et, selon le format, les dimensions ou la durée.
- **Exploration des métadonnées** : afficher les informations disponibles dans des catégories telles que :
  - EXIF et informations générales de l’image ;
  - coordonnées GPS ;
  - IPTC, XMP et profil ICC ;
  - tags audio et informations ID3.
- **Filtrage et tri** : retrouver plus facilement un fichier dans la liste.
- **Géolocalisation** : afficher les coordonnées GPS associées à une image et ouvrir une carte.
- **Parcours** : visualiser un itinéraire à partir de plusieurs fichiers contenant des coordonnées GPS.
- **Export de données et de cartes** : selon la vue utilisée, exporter les informations ou les cartes dans les formats proposés par l’application, notamment CSV, JPG ou PDF.
- **Interface en français** : application accessible directement dans un navigateur web moderne.

> Les informations affichées dépendent des métadonnées réellement présentes dans chaque fichier. Tous les fichiers ne contiennent pas de données EXIF ou GPS.

## Utilisation

1. Téléchargez le fichier `EXIFiles.html` en allant dans [Release](https://github.com/tonyo-BZH/EXIFiles/releases/latest) et en téléchargeant le fichier compressé de la dernière version, décompressez-le sur votre ordinateur, placer le fichier .html où vous voulez sur votre ordinateur.
2. Ouvrez le fichier `EXIFiles.html` dans un navigateur web moderne.
3. Déposez un ou plusieurs fichiers / ou un dossier dans la zone prévue.
4. Cliquez sur le nom d’un fichier pour consulter les métadonnées disponibles.
5. Utilisez les commandes de filtrage, de géolocalisation et d’export selon vos besoins.

Aucune installation n’est nécessaire. Certaines fonctionnalités, notamment l’affichage des cartes et l’ouverture de services cartographiques externes, peuvent nécessiter une connexion Internet.



## Confidentialité et données personnelles

Les métadonnées peuvent révéler des informations sensibles : lieu et heure de prise de vue, appareil utilisé, logiciel employé ou informations descriptives.

EXIFiles analyse les fichiers sélectionnés dans le navigateur, localement. **Le contenu des fichiers analysés n’est pas envoyé à un serveur par l’application pour effectuer cette analyse.**

Quelques précautions restent nécessaires :

- Les cartes et services externes peuvent nécessiter une connexion Internet. Leur utilisation peut entraîner des échanges avec le service concerné.
- L’ouverture d’un lien vers une carte externe transmet au service cartographique les informations présentes dans l’URL, par exemple des coordonnées GPS.
- Les résultats d’analyse peuvent contenir des données privées : évitez de les publier sans vérification.


## Technologies / Bibliothèques tierces

Le projet est constitué d’une page HTML intégrant du CSS et du JavaScript. Il s’appuie notamment sur des bibliothèques JavaScript pour lire les métadonnées et afficher les cartes :

- EXIFR : lecture des métadonnées d’images ;
- jsmediatags : lecture des tags de médias ;
- Leaflet : affichage de cartes interactives.

Les mentions de licence des composants intégrés sont indiquées dans le code source.

## Limites & contraintes

- Les métadonnées disponibles varient selon le format de fichier et les logiciels ou appareils qui l’ont créé.
- Un fichier peut avoir été modifié, privé de ses métadonnées ou contenir des informations inexactes.
- Un navigateur ne donne pas nécessairement accès à toutes les dates du système de fichiers. La date de prise de vue EXIF, lorsqu’elle existe, est distincte de la date de modification du fichier.
- L’affichage des fonds de carte et leur inclusion dans les exports dépendent des services cartographiques utilisés et de leurs conditions techniques.


## Mises à jour

Visitez le WIKI pour plus de détails : [Historique des mises à jour](https://github.com/tonyo-BZH/EXIFiles/wiki/Historique)



## Licence

Le dépôt indique une licence ......


<img src="https://github.com/tonyo-BZH/EXIFiles/blob/main/logos/bandeau_slogan.jpg" alt="Bandeau" width="800">  

