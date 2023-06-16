# Proxy settings

Ce script a été créé pour **Ubuntu**, aucun résultat n'est garanti avec quelconque autre distribution Linux / Mac

## Installation

Télécharger les scripts en utilisant `git clone` ou directement en zip, puis en extrayant les fichiers. Pour installer le script, lancer la commande depuis le dossier de téléchargement : 

`chmod +x uninstall_proxy_cmd`

`sudo ./install_proxy_cmd`

Il faut bien exécuter en tant que **root**.

Il est également possible de désinstaller le script quand vous intègrerez avec :

`sudo ./uninstall_proxy_cmd`

## Utilisation

Une fois installé, le script peut être directement lancé avec la commande

`change_proxy [name]`

Les arguments possibles sont :
- `hoche` : **Active** les paramètres de proxy en accord avec ceux du lycée
- `off` : **Désactive** tous les paramètres modifiés

L'autocomplétion vous aidera de toute façon

## Fonctionalités

Voici la liste des paramètres modifiés :
- Paramètres natifs **Ubuntu**, ceux accessibles directement depuis Paramètres->Réseau ( `org.gnome.system.proxy mode` )
- Le paramètre proxy utilisé de **git** ( `http.proxy` )