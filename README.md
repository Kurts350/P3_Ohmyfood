# Projet 3 - Ohmyfood

Ce projet s’inscrit dans le cadre de la formation **Développeur d'application JavaScript React** chez OpenClassrooms. Il consiste à **intégrer un site mobile-first pour une startup de commande de menus gastronomiques**, avec une attention particulière portée sur les **animations CSS** et la **structure Sass**.

---

## 📱 Objectif

Développer l’interface du site **Ohmyfood**, une plateforme permettant de réserver des menus dans des restaurants gastronomiques.

### Contraintes techniques :

- Intégration à partir de **maquettes Figma mobile, tablette et desktop**
- Utilisation de **Sass** pour l’organisation CSS
- Mise en place d’**animations CSS avancées** (chargement, boutons, apparition d’éléments)
- Approche **mobile-first**
- Responsive design obligatoire

---

## 🛠️ Technologies utilisées

- HTML5  
- Sass (SCSS)  
- CSS3 (animations, keyframes, transitions)  
- Flexbox & Media Queries  
- IDE : Visual Studio Code  
- Outils : Live Server, Sass compiler, Chrome DevTools  

---

## 📁 Structure du projet

```
ohmyfood/
├── index.html
├── restaurants/
│   ├── la_palette_du_gout.html
│   ├── la_note_enchantee.html
│   ├── a_la_francaise.html
│   └── le_delice_des_sens.html
├── assets/
│   ├── images/
│   └── sass/
│       ├── base/
│       ├── layout/
│       ├── pages/
│       ├── utils/
│       └── main.scss
└── README.md
```

---

## ▶️ Lancer le projet

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/Kurts350/P3_Ohmyfood.git
   cd ohmyfood
   ```

2. Compiler Sass :
   ```bash
   sass --watch assets/sass/main.scss:assets/css/style.css
   ```

3. Ouvrir `index.html` avec un navigateur ou via **Live Server**

---

## ✨ Fonctionnalités attendues

- **Loader** animé au lancement de la page
- **Animations de transition** sur les éléments de menu (apparition des plats)
- **Effets d’interaction** sur les boutons (like, commander, etc.)
- Responsive sur **mobile, tablette et desktop**
- Utilisation **organisée du Sass** (7-1 pattern recommandé)

---

## ✅ Checklist de validation

- [x] Intégration fidèle des maquettes Figma  
- [x] Animations CSS présentes et fluides  
- [x] Code Sass bien structuré  
- [x] Site responsive (mobile-first)  
- [x] Accessibilité de base respectée  
- [x] Optimisation des images et du chargement  

---

## 📄 Licence

Projet réalisé dans un but pédagogique dans le cadre de la formation OpenClassrooms – Développeur d'application JavaScript React.

---

## 👤 Auteur

**NIAKATE Biaguy**  
Formation Développeur d'application JavaScript React – OpenClassrooms  
📅 Mai 2024
