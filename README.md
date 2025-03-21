# 🧠 Gilded Rose Kata - Refactoring Challenge (C#)

Bienvenue ! Ce test a été conçu pour évaluer ton **raisonnement**, ta **capacité à refactorer du code legacy**, écrire des **tests fiables**, et travailler de façon **propre et professionnelle** sur un projet existant.

> Ce kata est inspiré d’un vrai projet legacy : il n’est pas là pour te piéger, mais pour voir comment tu penses, comment tu structures ton code et comment tu gères une situation qui peut arriver en entreprise.

## 🎯 Objectif

Tu reçois un code C# existant qui gère des objets d’une boutique (objets qui vieillissent, perdent ou gagnent en qualité, etc.).  
Le code est **fonctionnel mais illisible et non testé**.

**Ta mission :**
1. Comprendre ce que fait le code.
2. Écrire des **tests unitaires** pour figer son comportement actuel.
3. Refactorer ce code en toute sécurité (sans casser le comportement).
4. Ajouter tes **explications, ton organisation, tes choix techniques.**

## 🧪 Étapes à suivre

### Étape 1 – Préparation
- Cloner le repo et créer une nouvelle branche `refacto/ton-nom`.
- Lire attentivement la classe `GildedRose.cs`.

### Étape 2 – Tests
- Écris des **tests unitaires** (`xUnit`, `NUnit`, ou ton framework favori).
- Couvre tous les cas importants :
  - objets classiques,
  - objets spéciaux (`Aged Brie`, `Sulfuras`, `Backstage passes`),
  - qualité limite à 0 ou 50,
  - etc.

### Étape 3 – Refactorisation
- Améliore la structure du code.
- Utilise les bonnes pratiques (SRP, SOLID si pertinent).
- Ne casse pas le comportement existant (les tests doivent rester au vert).
- Extrais des méthodes, classes, règles métier si nécessaire.

### Étape 4 – Explication
- Crée un fichier `NOTES.md` où tu expliques :
  - Ce que tu as compris du code initial.
  - Les changements que tu as faits et pourquoi.
  - Les choix que tu ferais si tu devais réécrire cette logique from scratch.

## 🧑‍💻 Contraintes & Attentes

✅ **Fais des petits commits clairs** (pas tout d’un coup)  
✅ Utilise des noms explicites  
✅ Garde un code lisible, cohérent et testable  
✅ Organise ton code comme dans un vrai projet pro  
✅ Commente seulement si ça apporte de la clarté

## 🤖 À propos de l’IA

Tu peux utiliser l’IA **comme assistant**, mais ce test vise à évaluer **ton raisonnement personnel**.  
💡 On le verra dans la structure, les commits, les noms de variables, les choix de refacto…

**Donc :**
- Pas de gros copier-coller IA sans justification.
- Si tu t’aides d’une IA, **note-le dans le fichier `NOTES.md`**.

## 🏁 Comment rendre ton travail

1. Pousse ton code sur GitHub dans une branche dédiée.
2. Vérifie que les tests passent (`dotnet test`).
3. Partage-nous ton lien GitHub (en public ou accès restreint).
4. Ton travail sera relu commit par commit, avec attention 👀

Merci 🙌 et amuse-toi bien !
