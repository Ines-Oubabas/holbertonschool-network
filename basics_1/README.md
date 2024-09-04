# Networking Basics Project

## Introduction
Ce projet fait partie du programme Holberton School et vise à enseigner les bases du réseau. Vous apprendrez à utiliser des outils comme `ifconfig`, `nc`, et à comprendre comment fonctionnent les fichiers de configuration réseau comme `/etc/hosts`.

## Objectifs
À la fin de ce projet, vous serez capable d'expliquer à quelqu'un, sans utiliser Google, les concepts suivants :
- Ce qu'est `localhost` et l'adresse IP `127.0.0.1`
- Ce qu'est `0.0.0.0`
- Ce qu'est le fichier `/etc/hosts`
- Comment afficher les interfaces réseau actives de votre machine

## Fichiers
- `0-change_your_home_IP`: Ce script modifie la résolution de `localhost` pour `127.0.0.2` et celle de `facebook.com` pour `8.8.8.8`.
- `1-show_attached_IPs`: Ce script affiche toutes les adresses IP actives sur la machine.
- `2-port_listening_on_localhost`: Ce script écoute sur le port 98 de `localhost`.

## Utilisation des scripts

### 0. Change Your Home IP
Ce script modifie le fichier `/etc/hosts` pour que `localhost` se résolve à `127.0.0.2` et `facebook.com` à `8.8.8.8`.
```bash
sudo ./0-change_your_home_IP
