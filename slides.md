---
marp: true
theme: uncover
class:
  - invert
---

<style>
  section::before {
    left: 30px;
    color: #fff;
    bottom: 20px;
    font-size: 16px;
    font-weight: bold;
    position: absolute;
    content: "Pierre Fourny";
  }
</style>

## **Bootstrap & Tailwind**

# Introduction

---

## Bootstrap a été créé par **Twitter**

## En **2011**

---

## Problèmes que résout **Bootstrap**

- Créer une UI cohérente et réactive est complexe et prend du temps.
- Les développeurs doivent pouvoir itérer rapidement au démarrage d'un projet.
- Les développeurs orientés "back-end" ont besoin de simplicité côté "front-end".

---

## Solution de **Bootstrap**

##### Fournir un ensemble de **composants** et de grilles **réutilisables** pour créer des interfaces rapidement et efficacement.

---

## Tailwind a été créé par **Adam Wathan**

## En **2017**

---

## Problèmes que résout **Tailwind**

- Écrire du CSS est complexe et fastidieux.
- Les frameworks de composants comme **Bootstrap** n'offrent pas assez de flexibilité.
- Les frameworks actuels sont parfois trop lourds par rapport aux besoins.

---

## Solution de **Tailwind**

##### Fournir un ensemble de **classes utilitaires** pour créer des interfaces rapidement et avec efficacité.

---

![w:900](https://i.ibb.co/HnQn37k/DALL-E-Tailwind-VS-Bootstrap.png)

---

## 3 TP à réaliser

Clonez le dépôt Git suivant :

```
git clone https://github.com/FournyP/Tailwind-Bootstrap-course.git
```

###### Documentation de Tailwind : https://tailwindcss.com/docs

###### Documentation de Bootstrap : https://getbootstrap.com/docs

---

# Exemple

### **Bootstrap**

---

![w:600](https://i.ibb.co/48Y8X28/bootstrap-tp-example.png)

---

# Exemple

### **Tailwind**

---

![w:800](https://i.ibb.co/WF6M5Th/tailwind-tp-example.png)

---

## TP 1

##### Créez avec **Bootstrap** puis avec **Tailwind** une carte de profil :

- Une image de profil
- Un nom
- Une brève description

`💡 Voir la classe "card" dans Bootstrap`

---

## TP 1 - Résultat attendu

![w:350](https://i.ibb.co/CJsnH9y/tp1.png)

---

## TP 2

##### Créez avec **Bootstrap** puis avec **Tailwind** un formulaire de connexion :

- Un identifiant (login)
- Un mot de passe
- Un bouton de connexion

`💡 Consultez la documentation sur les "forms" dans Bootstrap`

---

## TP 2 - Résultat attendu

![w:800](https://i.ibb.co/JdgwxRn/tp2.png)

---

## TP 3

##### Créez avec **Bootstrap** puis avec **Tailwind** une barre de navigation :

- Un logo
- Un menu
- Un bouton de connexion

`💡 Consultez la documentation sur les "navbars" dans Bootstrap`

---

## TP 3 - Résultat attendu

![w:1100](https://i.ibb.co/RyCCnvx/tp3.png)

---

## Pour aller plus loin

### **Bootstrap**

---

- Evénements **JavaScript** (ex : ouverture d'une modale).
- Basée sur **SASS** (personnalisation avancée).
- **Compatibilité** avec tous les navigateurs modernes.
- **Communauté vaste**, support, ressources abondantes.

---

## Pour aller plus loin

### **Tailwind**

---

- Approche **Mobile-First** et responsive design facilité.
- Intègre PurgeCSS (supprime le CSS inutilisé)
- **Compatibilité** avec tous les navigateurs modernes.
- Extensions comme **Tailwind UI**, et d'autres bibliothèques "Bootstrap like".
- **Communauté** dynamique, support, ressources abondantes.
