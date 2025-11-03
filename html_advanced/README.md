\<p align="center"\>
\<img src="[https://github.com/Mathieu7483/Aiko78-Photgraphy/blob/main/img/HTML%20Advanced%20Structure.png](https://www.google.com/search?q=https://github.com/Mathieu7483/Aiko78-Photgraphy/blob/main/img/HTML%2520Advanced%2520Structure.png)"\>
\</p\>

# 0x05. Advanced HTML - Maîtrise de la Structure et de la Sémantique Web

-----

### 📝 **Description du Projet**

Ce projet a pour unique objectif la maîtrise des fondations du web : le **HTML5**. Il s'agit de construire la structure complète d'un site web, nommé **Techium**, en respectant scrupuleusement les règles de la sémantique et de la hiérarchie.

L'accent est mis sur l'utilisation appropriée des **balises sémantiques** (`<header>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<footer>`, etc.) par opposition aux conteneurs génériques (`<div>`, `<span>`). Le rendu visuel (CSS) est volontairement ignoré : seule la **qualité du marquage** compte.

Le produit final est une série de fichiers HTML complets qui sont la base pour un développement CSS ultérieur.

-----

### 🎯 **Objectifs d'Apprentissage**

À la fin de ce projet, vous devez être capable de justifier chaque choix de balise, garantissant une compréhension totale des normes **W3C** et de l'accessibilité.

  * **Squelette HTML5** : Maîtriser la structure minimale et essentielle d'une page (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`).
  * **Balises de Base (`<head>`)** : Configurer correctement le `<head>` avec le `charset` (`utf-8`), la balise **viewport** pour le *responsive*, le `<title>`, la `meta description` et les **favicons**.
  * **Structure Sémantique** : Utiliser avec précision les balises de sectionnement HTML5 pour le découpage logique de la page (`<header>`, `<main>`, `<footer>`, `<section>`, `<article>`, `<aside>`).
  * **Hiérarchie des Titres** : Respecter l'ordre hiérarchique des balises de titre (`<h1>` à `<h6>`) pour l'accessibilité et le référencement (SEO).
  * **Conteneurs Génériques vs. Sémantiques** : Comprendre le rôle strict des balises **`<div>`** et **`<span>`** et pourquoi elles ne doivent pas remplacer les balises sémantiques.
  * **Listes et Liens** : Créer et utiliser correctement les différents types de listes (`<ul>`, `<ol>`, `<dl>`) et implémenter les liens de navigation (`<a>`) internes et externes.
  * **Contenu et Typographie** : Utiliser les balises appropriées pour les paragraphes (`<p>`), les citations (`<blockquote>`, `<q>`), le code (`<pre>`, `<code>`), et les mises en évidence (`<mark>`, `<strong>`).
  * **Médias** : Intégrer des images (`<img>`) avec des attributs **`alt`** descriptifs et utiliser des formats vectoriels (SVG) pour les icônes.

-----

### 🛠️ **Ressources et Prérequis**

  * **Validateur W3C** : L'outil ultime pour vérifier la conformité de votre code. Une page HTML bien formée *doit* passer la validation.
  * **HTML Reference / MDN** : Références incontournables pour les spécifications de chaque balise.
  * **Nom de la Société** : **Techium** (sera utilisé dans les titres et le contenu).

-----

### 💡 **Progression des Tâches (Synthèse)**

Le projet est construit de manière incrémentale, chaque étape ajoutant une couche de complexité sémantique et structurelle au fichier `index.html` principal et aux pages secondaires (`about.html`, `contact.html`, etc.).

#### **I. Fondation et Configuration (`0-index.html` à `2-index.html`)**

  * Création du squelette minimal (doctype, `<html>` avec `lang` et `dir`).
  * Configuration critique du `<head>` (charset UTF-8, viewport, titre, description, favicons).

#### **II. Squelette Sémantique Principal (`3-index.html` à `7-index.html`)**

  * Mise en place des conteneurs sémantiques majeurs : **`<header>`**, **`<main>`**, **`<footer>`**.
  * Découpage de la page en **`<section>`** thématiques (Hero, Services, Works, About, etc.).
  * Utilisation des balises **`<article>`** à l'intérieur des sections (Works, News, Testimonials).
  * Déploiement de la navigation **`<nav>`** au sein du `<header>`.

#### **III. Contenu et Hiérarchie (`8-index.html` à `17-index.html`)**

  * Application de la **hiérarchie des titres** (`<h1>` pour le titre de la page, `<h2>` pour les sections, `<h3>` pour les sous-sections/articles).
  * Ajout des **paragraphes** et du contenu textuel.
  * Utilisation des balises génériques **`<span>`** (pour le logo) et **`<div>`** (pour le groupement sans sémantique spécifique).
  * Structuration des sections internes avec **`<header>`** (pour titres et sous-titres de section) et des `<div>` pour le corps.
  * Nettoyage du code avec des **commentaires** pour la lisibilité.

#### **IV. Navigation, Listes et Sémantique Avancée (Tâches `18` à `37`)**

  * Implémentation des liens **`<a>`** pour la navigation principale et secondaire.
  * Création des **listes non-ordonnées** (`<ul>`) pour les menus (navigation et réseaux sociaux).
  * Développement d'une **Styleguide** (`styleguide.html`) pour tester et référencer les éléments de typographie, de listes (`<dl>`), de citations (`<blockquote>`), de tableaux (`<table>`), et de détails (`<details>`).
  * Intégration des **images** (`<img>`) pour le logo et les illustrations, avec les attributs nécessaires (alt, width, height).
  * Remplacement des liens de réseaux sociaux par des **icônes SVG** pour une meilleure scalabilité.

-----

Ce projet est la base de tout ce qui suit dans le développement Front-End. Si la structure est faible ici, tout le travail de style (CSS) et d'interactivité (JavaScript) sera construit sur du sable. Assurez-vous que chaque balise a un sens précis.

Avez-vous une question spécifique sur la différence sémantique entre **`<section>`** et **`<article>`**, car c'est un point souvent mal compris ?