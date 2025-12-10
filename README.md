# 🎬 Anime Requester

> **Projet de Groupe - JavaScript**
> Application de recherche d'animes utilisant l'API Anime DB via RapidAPI.

[![Statut du projet](https://img.shields.io/badge/Statut-Terminé-success)]()
[![Langage](https://img.shields.io/badge/Langage-JavaScript%20(ES6)-yellow)]()
[![Style](https://img.shields.io/badge/Style-CSS3%20%2F%20Responsive-blue)]()

## 🔗 Démo en ligne
**[Voir le projet sur GitHub Pages](https://nutella9775.github.io/animerequester/)**
*(Clé API pour tester : df5fe52db4msh6559a929065c42fp1446b6jsn3b2b1e0a9759)*

---

## 📝 Description

**Anime Requester** est une application web dynamique (SPA) permettant aux utilisateurs de rechercher des informations détaillées sur des animes. Ce projet a été réalisé dans le cadre de notre formation JavaScript pour maîtriser les interactions asynchrones (`fetch`), la manipulation du DOM et l'architecture modulaire.

Le projet a été développé en deux phases :
1.  **V1 (MVP) :** Recherche basique et affichage de cartes.
2.  **V2 (Avancée) :** Filtres par genres, gestion de clé API utilisateur, et mode Sombre/Clair.

---

## ✨ Fonctionnalités

### Version de Base (V1)
* 🔍 **Recherche flexible :** Par nom, par ID ou par classement (Ranking).
* 🃏 **Affichage en cartes :** Résultats limités à 10 items, présentant :
    * Titre et image de couverture.
    * Synopsis complet.
    * Genres et catégories.
    * Classement et nombre d'épisodes.
* 🔄 **Réinitialisation** facile du formulaire.

### Version Avancée (V2) - *Actuelle*
* 🏷️ **Recherche par Genre :** Sélection intuitive via des filtres/tags.
* 🔐 **Gestion de Clé API :** L'utilisateur peut saisir sa propre clé API RapidAPI (stockée temporairement en `sessionStorage` pour la sécurité).
* 🌓 **Mode Sombre / Clair :** Thème basculable avec persistance du choix utilisateur (`sessionStorage`).
* 📱 **Responsive Design :** Interface adaptée aux mobiles, tablettes et ordinateurs.

---

## 🛠️ Stack Technique

* **HTML5** : Structure sémantique et respect des normes W3C.
* **CSS3** : Flexbox/Grid pour la mise en page, Variables CSS pour le thème Dark/Light.
* **JavaScript (Vanilla)** :
    * **Modules ES6** : Séparation des responsabilités (Logique API, Gestion UI, Utilitaires).
    * **Fetch API** : Requêtes asynchrones vers Anime DB.
    * **DOM Manipulation** : Génération dynamique des cartes de résultats.
    * **Storage API** : Utilisation de `sessionStorage`.
* **Accessibilité** : Respect des normes WCAG AA 2.0 (contrastes, navigation clavier).
