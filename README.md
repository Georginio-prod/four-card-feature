# Four card feature section (Frontend Mentor)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-SCSS-CC6699?logo=sass&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5-646CFF?logo=vite&logoColor=white)
![Frontend Mentor](https://img.shields.io/badge/Frontend_Mentor-Challenge-3F54A3)

🔗 **Démo en ligne** : <https://georginio-prod.github.io/four-card-feature/> (GitHub Pages) · Vercel : <https://four-card-feature-gray.vercel.app>
📦 **Code source** : <https://github.com/Georginio-prod/four-card-feature>
🎯 **Défi** : [Four card feature section](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK) (niveau *Newbie*)

---

## 📌 Présentation

Section de **quatre cartes de fonctionnalités** (Supervisor, Team Builder, Karma, Calculator) disposées en losange sur desktop : une carte à gauche, deux au centre empilées, une à droite. Chaque carte a une bordure supérieure colorée et une icône.

Réalisé en **HTML sémantique + Sass**, servi par **Vite** (rechargement à chaud et build optimisé),
sans framework JavaScript : l'objectif est la maîtrise du CSS et du responsive.

## ✨ Fonctionnalités

- Disposition en losange via CSS Grid (3 colonnes, cartes centrales décalées).
- Bordure supérieure colorée par carte (cyan, rouge, orange, bleu).
- Empilement vertical sur mobile.
- Déploiement automatique sur GitHub Pages via GitHub Actions (`.github/workflows/gh-page.yml`).

## 🛠️ Stack

| Élément | Détail |
|---|---|
| Structure | HTML5 sémantique |
| Styles | Sass / SCSS compilé par Vite |
| Outils | Vite 5 (dev server + build) |
| Maquette | Frontend Mentor — mobile 375px / desktop 1440px |

## 📁 Structure

```
four-card-feature/
├── index.html              # Toute la structure de la page
├── sass/style.scss         # Feuille de style SCSS (variables, imbrication, media queries)
├── main.js                 # Importe le SCSS (point d'entrée Vite)
├── public/                 # Images, icônes, fonds de la maquette
└── package.json
```

## 🚀 Installation & lancement

```bash
git clone https://github.com/Georginio-prod/four-card-feature.git
cd four-card-feature
npm install
npm run dev          # http://localhost:5173
```

`npm run build` génère le site statique dans `dist/` ; `npm run preview` le prévisualise.

## 🌐 Déploiement

Déployé sur **Vercel** (framework Vite, sortie `dist/`) : <https://four-card-feature-gray.vercel.app>. Aucune variable d'environnement.
Également publié sur **GitHub Pages** par le workflow GitHub Actions du dépôt.

## 🎓 Ce que ce projet démontre

CSS Grid pour des layouts non rectangulaires, ombres douces, mise en place d'un workflow CI de déploiement.

---

## 👤 Auteur

**Komla Etonam Georges EKLOU** (Georginio) — Développeur Full Stack Web & Web3

[![GitHub](https://img.shields.io/badge/GitHub-Georginio--prod-181717?logo=github)](https://github.com/Georginio-prod)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profil-0A66C2?logo=linkedin)](https://www.linkedin.com/in/komla-etonam-georges-eklou-68518b23b)
[![Portfolio](https://img.shields.io/badge/Portfolio-georginio.w3frame.com-6C63FF)](https://georginio.w3frame.com/)

> 📚 Tous mes projets sont listés et documentés sur mon [profil GitHub](https://github.com/Georginio-prod).
