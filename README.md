# PROJET 7 — Kasa

Application front-end React pour le site de location immobilière **Kasa**.  
Le projet met en place la navigation, l’affichage dynamique des logements, ainsi que des pages dédiées (Accueil, À propos, Fiche logement, Erreur 404).

---

## Aperçu

### Pages principales
- **Accueil** : liste des logements (cards) avec navigation vers la fiche
- **Fiche logement** : galerie, infos, tags, hôte, note, description, équipements
- **À propos** : sections informatives (collapse)
- **404** : page d’erreur si la route n’existe pas ou si l’ID logement est invalide

---

## Fonctionnalités

- Routing avec **React Router**
- Pages dynamiques via paramètre d’URL (`/logement/:id`)
- Composants réutilisables (cards, collapse, slider, rating, etc.)
- Gestion d’erreurs (route inconnue, logement introuvable)
- Style en **SCSS** (structure modulaire)

---

## Stack technique

- **React**
- **React Router**
- **SCSS**
- Données logements en local (ex : `logements.js` / `logements.json` selon ton projet)

---

## Compétences développées

- Création d'une SPA avec React
- Mise en place du routage avec React Router
- Gestion des composants réutilisables
- Gestion des props et du state
- Création d'une architecture de projet maintenable
- Développement responsive
- Gestion des erreurs et page 404

---

## Prérequis

- Node.js (recommandé : version LTS)
- npm (ou yarn)

---

## Installation

1. Cloner le dépôt :
   ```bash
     git clone <url-du-repo>
     cd <nom-du-projet>

2. Installer les dépendances :
   ```bash
    npm install
   
---

## Lancer le projet en local
    npm run dev

---

## Build (production)
    npm run build

---

## Créer une version de production :
    npm run build

---

## Prévisualiser le build :
    npm run preview

---

## KASA/
    ```bash
    ├─ public/
    ├─ src/
    │  ├─ assets/
    │  ├─ components/
    │  │  ├─ Banner/
    │  │  ├─ Card/
    │  │  ├─ Collapse/
    │  │  ├─ Footer/
    │  │  ├─ Header/
    │  │  ├─ Layout/
    │  │  ├─ Rating/
    │  │  └─ Slideshow/
    │  ├─ pages/
    │  │  ├─ About/
    │  │  ├─ Error/
    │  │  ├─ Home/
    │  │  └─ Housing/
    │  ├─ router/
    │  │  └─ Router.jsx
    │  ├─ styles/
    │  ├─ App.jsx
    │  ├─ main.jsx
    │  └─ logements.json
    ├─ index.html
    ├─ package.json
    ├─ vite.config.js
    └─ README.md

---

Routes
- / : Page d’accueil
- /about : Page À propos
- /logement/:id : Fiche logement dynamique
- '*' : Page 404

---

## Données logements
src/logements.json

---

## Captures
<img width="1060" height="890" alt="image" src="https://github.com/user-attachments/assets/aff5ff1b-cd2a-4f01-bdb5-903a89fffca7" />
<img width="1136" height="1071" alt="image" src="https://github.com/user-attachments/assets/e6dde465-5c9b-4821-9cc1-5fc17c42c802" />
<img width="1096" height="1067" alt="image" src="https://github.com/user-attachments/assets/2991faac-55a5-4af6-bfad-4a14cdef3421" />
<img width="1224" height="1064" alt="image" src="https://github.com/user-attachments/assets/1bd08257-8c06-4a34-908e-293568d2c47b" />
<img width="392" height="971" alt="image" src="https://github.com/user-attachments/assets/35b504b0-7d30-43c3-a8f2-94e675cc791a" />
<img width="948" height="711" alt="image" src="https://github.com/user-attachments/assets/ecafd7a7-bbaa-4635-8943-00e033175da5" />







## Auteur
Projet réalisé dans le cadre de la formation
OpenClassrooms – Intégrateur Web.
