# project-I-releases

Installeurs et manifestes de mise à jour de **project-I**, un hub personnel *local-first* pour
Windows : il regroupe, surveille et pilote vos activités numériques (automatisations, réseau,
applications, projets de dev, jeux) sur un tableau de bord. Vos données restent sur votre
machine, dans une base chiffrée.

Ce dépôt ne contient aucun code : seulement les installeurs, leurs signatures et les manifestes
lus par les applications installées pour se mettre à jour.

## Télécharger

Dernière version stable : <https://github.com/Ikki454/project-I-releases/releases/latest>

1. Téléchargez `project-I_<version>_x64-setup.exe`.
2. Lancez-le. L'installeur n'est pas signé par un certificat de code : Windows affiche
   « Windows a protégé votre ordinateur ». Cliquez sur **Informations complémentaires**, puis
   sur **Exécuter quand même**.
3. project-I s'installe pour votre compte, sans droits administrateur, dans
   `%LOCALAPPDATA%\project-I`.

Les versions suivantes s'installent depuis l'application (**Paramètres → Mises à jour**), qui
vérifie leur signature avant de les installer.

## Canaux

- **Stable** : releases `vX.Y.Z`, marquées « Latest ».
- **Développement** : prerelease `dev`, remplacée à chaque build.
