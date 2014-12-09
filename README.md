Picasa2Piwigo²
==============

Picasa2Piwigo² reprendre les grandes lignes de son précurseur (de Picasa2Piwigo de KenL, merci à lui), tout en l'améliorant avec de nouvelles fonctions. Grâce à la lecture de la base de données de Picasa, il est possible d'uploader quasi toutes les informations disponibles. En contrepartie, l'application doit lire à chaque démarrage la base de données de Picasa (moins de 15s pour la lire tout de même).

Fonctionne de 3 façons :
- Directement depuis Picasa (création d'un bouton d'upload pour l'album en cours)
- En appelant des albums de Picasa (permet d'uploader plusieurs album à la suite sans ouvrir Picasa)
- En mode libre (upload de n'importe quel répertoire contenant des images)

Fonctionnalités :
- Plus de limitation de 120 images à partir de Picasa
- Gestion des doublons dans Piwigo (pas d'upload si l'image existe déjà)
- Lecture des données XMP/IPTC (avec l'utilitaire ExifTool.exe en ligne de commande)
- Gestion des facetags de Picasa (XMP ou base de données)
- Système de permission automatique en fonction des mots-clés/facetag (si un mot-clés/facetag est présent, on accorde l'accès à un/des users/groupes)
- Ajout des images par chunk (permet d'éviter les erreurs PHP de temporisation)

Testé avec Piwigo 2.7.2 et Exiftool 9.76
En espérant qu'elle vous apporte satisfaction.

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

Picasa2Piwigo² resume outline its precursor (from Picasa2Piwigo of KenL, thanks to him), while improving it with new features. Through reading the Picasa database, it's possible to upload almost all available information. In return, the application must read each time you start Picasa database (under 15s to read anyway).

Works in 3 ways:
- Directly from Picasa (by creating a button to upload album)
- Calling Picasa albums (allows upload multiple albums in a row without open Picasa)
- In free mode (upload any folder containing pictures)

Features:
- No more 120 pictures limitation from Picasa
- Management duplicates in Piwigo (no upload if the picture already exists)
- Reading data XMP / IPTC (with ExifTool.exe command line utility)
- Management facetags Picasa (XMP or database)
- Automatic permission system based on keywords / facetag (if a keyword/facetag is present, it grants access to users/groups)
- Added pictures per chunk (avoids PHP timeout errors)

Tested with Piwigo 2.7.2 and ExifTool 9.76
Hoping it brings you satisfaction.
