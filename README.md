# 📰 accessWeb

Mini-site de presse (type [Next.ink](https://next.ink)) réalisé dans le cadre d'un projet pédagogique axé sur l'accessibilité web et la qualité numérique.

> Projet réalisé en binôme — Durée : 16h — Intervenant : Camille Bouvat

---

## 📋 Description

Ce projet consiste en la création d'un mini-site de presse statique comprenant trois pages : une page d'accueil, une page article et une page de login. L'accent est mis sur la **sémantique HTML5**, l'**accessibilité** (WCAG, RGAA, ARIA) et la **qualité web** (Opquast).

---

## 📄 Pages

### 🏠 Page d'accueil
- Liste de 5 articles fictifs avec photo, titre et liens
- Lien vers chaque article
- Lien vers les commentaires de chaque article

### 📝 Page article
- Contenu réaliste (titres et images inspirés de l'actualité tech)
- Un tableau avec minimum 3 colonnes et 4 lignes (avec `<thead>` et `<tfoot>`)
- Au minimum 2 commentaires par article (auteur, texte, date)

### 🔐 Page login
- Champ email et champ mot de passe
- Redirection vers la page d'accueil après connexion
- Pas de page d'inscription

---

## 🛠️ Technologies utilisées

- HTML5 sémantique
- CSS3 (feuille de style unique pour l'ensemble du projet)

---

## ♿ Accessibilité

### Attributs ARIA utilisés
- `aria-label` — labellisation des éléments sans texte visible
- `aria-labelledby` — association d'un titre à une région
- `aria-describedby` — description complémentaire d'un élément
- `aria-hidden` — masquage des éléments décoratifs aux lecteurs d'écran
- `aria-current` — indication de la page active dans la navigation

### HTML sémantique
- Utilisation des balises de structure : `<header>`, `<nav>`, `<main>`, `<footer>`, `<article>`, `<section>`
- Hiérarchie des titres respectée (`<h1>` → `<h2>` → `<h3>`…)
- Tableaux accessibles avec `<thead>`, `<tbody>`, `<tfoot>` et attributs `scope`

### Lecteur d'écran
- Site testé et utilisable avec **VoiceOver** (macOS) et **Narrateur** (Windows)
- Validation via l'outil [WAVE](https://wave.webaim.org/) (zéro erreur)
- Tous les éléments principaux sont labellisés

---

## ✅ Qualité web (Opquast)

Les règles Opquast suivantes ont été intégrées au projet :

| Règle | Description |
|-------|-------------|
| #6 | Le site propose un mécanisme de navigation de contournement |
| #76 | Les images ont un attribut `alt` pertinent |
| #164 | Les formulaires ont des labels explicites |
| #171 | Les liens sont explicites hors contexte |
| #191 | La langue principale de chaque page est définie |
| #219 | Les tableaux de données ont des en-têtes |
| #231 | Les erreurs de saisie sont identifiées et décrites |

---

## 🚀 Lancer le projet

```bash
git clone https://github.com/alexis-orga/accessWeb.git
cd accessWeb
```

Ouvrez `index.html` dans votre navigateur, ou utilisez l'extension **Live Server** sur VS Code.

Le site est également hébergé sur **GitHub Pages** : [alexis-orga.github.io/accessWeb](https://alexis-orga.github.io/accessWeb)

---

## 📚 Ressources

- [MDN — HTML accessible](https://developer.mozilla.org/fr/docs/Learn/Accessibility/HTML)
- [WCAG 2.1 — W3C](https://www.w3.org/WAI/standards-guidelines/wcag/fr)
- [RGAA — accessibilite.numerique.gouv.fr](https://accessibilite.numerique.gouv.fr/)
- [Comprendre ARIA — web.dev](https://web.dev/learn/accessibility/aria-html?hl=fr)
- [Checklist Opquast](https://checklists.opquast.com/fr/qualite-numerique/)
- [Validateur W3C](https://validator.w3.org)
- [WAVE — testeur d'accessibilité](https://wave.webaim.org/)

---

## 👤 Auteur

**Alexis** — [@alexis-orga](https://github.com/alexis-orga)
