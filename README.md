# cooperative-thimdrine
Site vitrine pour la coopérative Thimdrine de Nador (Produits locaux).
# 🌿 Coopérative Thimdrine — Site Vitrine & Catalogue Produits

Projet de développement web sur-mesure pour la **Coopérative Thimdrine** (Nador, Région du Rif, Maroc). 

Le site met en valeur le savoir-faire artisanal local et propose un catalogue clair pour la présentation de leurs produits naturels (miels sauvages, huile d'olive extra-vierge, confitures artisanales, etc.).

---

## 🎯 Objectifs du Projet

- **Identité Visuelle & Valorisation** : Refléter l'authenticité et le travail artisanal des femmes de la coopérative à travers un design épuré et moderne.
- **Maîtrise du Layout (CSS Flexbox & Grid)** : Conception entièrement réalisée en HTML5/CSS3 natif, sans frameworks CSS externes (Tailwind, Bootstrap), afin d'assurer un contrôle total sur l'alignement et la structure des cartes produits.
- **Design Responsive** : Adaptabilité complète aux écrans mobiles, tablettes et ordinateurs.

---

## 🎨 Charte Graphique

| Élément | Couleur / Valeur | Hex / CSS |
| :--- | :--- | :--- |
| **Vert Principal** | Feuiiles & Nature | `#2C4326` |
| **Bordeaux / Prix** | Mise en valeur du prix | `#8C2B3E` |
| **Fond Cartes** | Beige doux | `#FDFBF7` |
| **Texte Principal** | Marron / Gris foncé | `#5C4F42` |
| **Fond Général** | Blanc neutre | `#FFFFFF` |

---

## 🛠️ Technologies Utilisées

- **HTML5** : Structuration sémantique (`<header>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`).
- **CSS3** :
  - **CSS Grid** : Agencement à 3 colonnes sur la section d'accueil et structure 2 colonnes (`aside` + `main`) sur la page catalogue.
  - **Flexbox** : Alignement vertical des cartes, gestion de la hauteur uniforme (`height: 100%`) et alignement horizontal parfait des prix au bas des cartes (`flex-grow: 1`).
- **Git & GitHub** : Gestion de versions et suivi du projet.

---

## 📋 Structure des Pages & Fonctionnalités

### 1. Page d'Accueil (`index.html`)
- **Hero Section** : Présentation de l'histoire et des valeurs de la coopérative Thimdrine.
- **Section Produits Phares** : Mise en avant des 3 produits phares de Nador sous forme de cartes structurées.
- **Footer** : Coordonnées, liens vers les réseaux sociaux et mentions légales.

### 2. Page Catalogue (`produits.html`)
- **En-tête & Barre d'outils** :
  - Champ de recherche stylisé.
  - Menu déroulant de tri par popularité ou prix.
- **Sidebar des Filtres** :
  - Filtre par catégories (Miels, Huiles, Confitures).
  - Sélecteur de tranche de prix (Slider HTML).
- **Grille de Produits** :
  - Affichage en 2 colonnes avec alignement strict des images, descriptions, prix et formats (ex: *180 DH · pot de 500 g*).

---

## 📁 Structure du Projet

```text
cooperative-thimdrine/
├── index.html              
├── produits.html
├── Contact.html              
├── À_Propos.html            
├── css/
│   ├── style.css                     
├── img/                    
│   ├── 1.webp
│   ├── 2.webp
│   ├── 3.webp
│   ├── 4.webp
│   ├── 5.webp
│   ├── 7.webp
│   ├── cooperative.webp
│   ├── Gemini_Generated_Image_frqwx8frqwx8frqw.webp
│   ├── logo.svg
│   ├── product.webp
│   ├── product1.webp
│   ├── product2.webp
│   └── product.webp
└── README.md               # Documentation du projet
