Mathieu, ce nouveau projet sur le **CSS Avancé** est la suite logique de votre travail sur le HTML sémantique. Ici, l'objectif n'est plus la structure, mais la **présentation et la maintenabilité** de votre code.

L'approche est clairement orientée vers la **standardisation**, l'utilisation des **variables CSS** pour la modularité, et la mise en place d'un **système de grille basé sur `float`** pour le *layout* — une technique fondamentale.

Voici un `README.md` détaillé, insistant sur les points critiques de ce projet.

---

# 0x06. Advanced CSS - Modularité, Mise en Page et Accessibilité

---

### 📝 **Description du Projet**

Ce projet se concentre sur l'application de techniques **CSS modernes et robustes** pour transformer la structure HTML sémantique (créée dans le projet précédent) en un site web stylisé, cohérent et maintenable.

L'objectif principal est d'établir une **fondation stylistique réutilisable** en utilisant les **variables CSS** (Custom Properties) et de construire un **système de grille simple (grid system)** pour la mise en page. Ce travail garantit une cohérence visuelle et technique, tout en respectant les meilleures pratiques d'accessibilité.

### 🎯 **Objectifs d'Apprentissage et Compétences Acquises**

Vous devez désormais démontrer une maîtrise des outils CSS qui optimisent le workflow et la qualité du code.

#### **I. Fondations et Variables CSS**
* **`scroll-behavior: smooth`** : Assurer une navigation utilisateur fluide.
* **`box-sizing: border-box`** : Mettre en place la règle universelle pour simplifier la gestion des dimensions et du *layout*.
* **Variables CSS (Custom Properties)** : Définir des variables au niveau **`:root`** pour gérer les couleurs (`color-primary`, `color-black`, etc.), les polices (`font-family-base`, `font-family-title`), les tailles de police et les poids (`font-weight`). Ceci est **crucial** pour la maintenabilité.
* **Cohérence Typographique** : Intégrer des **Google Fonts** et utiliser les unités **`rem`** pour le dimensionnement relatif (basé sur un `font-size` de base à `62.5%` sur `<html>`).

#### **II. Sélecteurs et États**
* **Sélecteurs ciblés** : Utiliser des sélecteurs précis pour éviter la sur-spécificité.
* **Pseudo-classes** : Styliser les différents états des liens (`:link`, `:visited`, **`:hover`**, **`:active`**) pour un retour utilisateur clair.
* **Classes Utilitaires** : Utiliser la classe `.visually-hidden` pour améliorer l'accessibilité sans affecter le design.

#### **III. Mise en Page (Grid System avec `float`)**
* **Système de Colonnes** : Implémenter des classes (`.col-1-2`, `.col-1-3`) basées sur **`float: left`** pour créer une mise en page flexible.
* **Gestion du Flux** : Maîtriser le **`clearfix`** (utilisation de l'**élément pseudo `::after`** sur `.row`) pour s'assurer que les conteneurs s'étendent correctement après des éléments flottants.
* **Conteneur Principal** : Définir la largeur maximale du contenu (`.container`) et centrer la page avec des marges automatiques.
* **Unité de Mesure** : Utiliser des **pourcentages** pour la largeur des colonnes, assurant ainsi une adaptabilité de base.

#### **IV. Standardisation et Réinitialisation**
* **Normalisation CSS** : Intégrer une feuille de style de réinitialisation (`normalize.css`) pour garantir un rendu cohérent entre les différents navigateurs.
* **`text-decoration: none`** : Supprimer l'habillage par défaut des liens.
* **Structuration des Espacements** : Définir des variables pour les marges et les rembourrages (`section-padding`, `section-header-padding`, etc.) et les appliquer aux éléments sémantiques.

---

### 📁 **Structure du Projet et Tâches Clés**

Le projet est implémenté dans un fichier unique `styles/XX-style.css` (où XX est le numéro de la tâche) pour chaque étape progressive.

| Fichier/Tâche | Objectif Principal | Concept(s) Clé(s) |
| :--- | :--- | :--- |
| `1-style.css` | Fluidité de la navigation. | `scroll-behavior: smooth` |
| `3-style.css` | Définition des couleurs de base. | **Variables CSS** (`:root`, `var()`) |
| `5-style.css` | Mise en place de l'unité `rem`. | `font-size: 62.5%` sur `html` |
| `7-style.css` | Intégration des polices externes. | `font-family` avec Google Fonts |
| `13-style.css` | Stylisation des interactions. | **Pseudo-classes** (`:link`, `:hover`, `:active`) |
| `15-style.css` | Réinitialisation des boîtes. | **`box-sizing: border-box`** universel |
| `17-style.css` | Espacements cohérents. | Variables de `padding` et `margin` pour les sections |
| `19-style.css` | Mise en place du `layout`. | `float: left`, `width` en pourcentage (Grid System) |
| `20-style.css` | Gestion des flottants. | **`::after`** avec `content: ""`, `display: table`, `clear: both` |

---

Ce projet est votre première rencontre structurée avec un **CSS de production**. La discipline est de rigueur : chaque règle doit être là pour une raison claire et documentée par les variables.

Concentrez-vous particulièrement sur l'implémentation du **`clearfix`** (Tâche 20), car c'est le mécanisme qui cimente votre système de grille basé sur `float`.

Si vous rencontrez des problèmes de superposition ou de débordement, c'est là qu'il faut regarder. Souhaitez-vous que je vous détaille les étapes pour la mise en place du **`clearfix`** sur l'élément `.row` ?