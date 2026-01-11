

# 📱 Labs 3 – Conception d’un écran d’accueil défilant avec ScrollView

Ce travail pratique a été réalisé avec **React Native** et **Expo Router**.
Il vise à transformer un écran d’accueil statique en un écran **défilant** à l’aide du composant `ScrollView`.

---

## 🎯 Buts pédagogiques

* Maîtriser l’utilisation du composant `ScrollView`.
* Convertir un écran fixe en écran dynamique avec défilement.
* Gérer l’affichage de contenus longs dépassant la hauteur de l’écran.
* Appliquer un thème sombre avec personnalisation de la barre de défilement sur iOS.

---

## 🗂️ Organisation du projet

```
app/
 ├── index.tsx        → Écran principal
 ├── _layout.tsx     → Gestion de la navigation
components/          → Composants réutilisables
```

---

## ⚙️ Mise en place du projet

1. Clonage du dépôt :

```bash
git clone https://github.com/ton-compte/premier-componenr-rn.git
cd premier-componenr-rn
```

2. Installation des dépendances :

```bash
npm install
```

3. Exécution de l’application :

```bash
npx expo start
```

Ouverture possible via :

* Android Emulator
* iOS Simulator
* Application **Expo Go**

---

## 🧪 Démarche de réalisation

Dans le fichier `app/index.tsx` :

* Intégration du composant `ScrollView`.
* Affichage :

  * d’un **titre principal**,
  * d’un **texte long**.
* Activation du défilement vertical du contenu.

---

## 🖼️ Aperçu du rendu

L’écran d’accueil est désormais défilant et permet la consultation d’un contenu étendu.

<img width="1418" height="654" alt="image" src="https://github.com/user-attachments/assets/069022b2-42a4-4e7b-90ee-4aac7479c3fd" />

<img width="762" height="719" alt="image" src="https://github.com/user-attachments/assets/d86d697b-5147-4482-a2b9-c3054d1bd6f7" />

---

## ✅ Bilan du TP

* Écran d’accueil avec défilement fonctionnel
* Lecture fluide de contenus volumineux
* Interface respectant un thème sombre
* Barre de défilement blanche sur iOS

---

## 👩‍💻 Réalisation

* **Étudiante :** HASSAOUI Aya
* **Encadrant :** Pr. Mohammed Lechgar

---
