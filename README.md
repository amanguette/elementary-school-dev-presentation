# 🎓 Présentation CM1-CM2 – Le métier de développeur
**Durée : ~20 minutes**

> Objectif : faire découvrir le métier de développeur de manière ludique, concrète et interactive.

---

## 🟡 1. Introduction : Qu’est-ce qu’un développeur ? (2–3 min)

- Poser la question : “Selon vous, qu’est-ce qu’un développeur ?”
- Expliquer simplement : une personne qui donne des instructions à un ordinateur.
- Métaphore : comme une recette de cuisine → le développeur est le chef, l’ordi suit la recette.

---

## 🔴 2. Le code est partout – même dans la rue (3 min)

- Question : “Avez-vous déjà vu un écran en panne dans un magasin ?”
- Montrer des exemples d’écrans d’erreurs dans des lieux publics :

Voici quelques cas réels où des écrans publics affichent des messages d'erreur. Cela montre que le **code est partout**, même là où on ne l’imagine pas !

[Écrans erreurs](https://cheezburger.com/11502341/very-public-computer-errors)

---

## 🟠 3. L’anecdote : l’erreur "I’m a teapot" (2 min)

- Expliquer ce que sont les **codes d’erreur HTTP** (les réponses des serveurs quand quelque chose ne va pas).
- 📖 [Wikipédia – Liste des codes HTTP](https://fr.wikipedia.org/wiki/Liste_des_codes_HTTP)
- 📖 [Wikipédia – Erreur 418](https://fr.wikipedia.org/wiki/Erreur_HTTP_418)
- Anecdote : `418 I'm a teapot` = “Je suis une théière”  
  ➜ Une blague à l’origine (RFC 2324), mais aujourd’hui une vraie théière connectée pourrait vraiment l’utiliser 😄

---

## 🟢 4. Exemple complet : le site Porsche (6 min)

### 💡 Objectif : montrer qu’un site est le résultat de plusieurs métiers

1. 👀 **Le site web Porsche – ce que les utilisateurs voient**  
   [https://www.porsche.com/france/](https://www.porsche.com/france/)

2. 🎨 **Le fichier Figma – l’outil des designers**  
   [https://www.figma.com/@porsche](https://www.figma.com/@porsche)

3. 🧱 **Le Design System – les composants visuels**  
   [https://designsystem.porsche.com/v3/](https://designsystem.porsche.com/v3/)

4. 💻 **Le GitHub – le code des développeurs**  
   [https://github.com/porsche-design-system/porsche-design-system](https://github.com/porsche-design-system/porsche-design-system)

> 🧩 **Message :** Tous les éléments visibles (boutons, menus, titres) sont créés **en équipe** puis codés pour devenir interactifs.

---

## 🔵 5. Démo interactive : petit code JavaScript (5 min)

### 🎯 Objectif : montrer que coder, c’est faire agir la machine

### 1. Changer l’arrière-plan et le contenu de la page (dans la console navigateur)

```js
document.body.style.backgroundColor = "lightgoldenrodyellow";
document.body.innerHTML = "<h1>Bienvenue les CM1-CM2 ! 🎉</h1>";
```

---

### 2. Exercice logique – dire bonjour à chaque élève

```js
let nombreEleves = 5;
for (let i = 1; i <= nombreEleves; i++) {
  document.body.innerHTML += `<p>👋 Bonjour élève n°${i}</p>`;
}
```

### 3. afficher les prénoms dans la console

```js
let eleves = ["Lina", "Adam", "Inès", "Tom", "Maya"];
console.log("👋 Bonjour " + eleves[2] + " !");
```

```js
let eleves = ["Lina", "Adam", "Inès", "Tom", "Maya"];

for (let i = 0; i < eleves.length; i++) {
  console.log("👋 Bonjour " + eleves[i] + " !");
}
```

```js
let eleves = ["Lina", "Adam", "Inès", "Tom", "Maya"];

for (let i = 0; i < eleves.length; i++) {
  document.body.innerHTML += `<p>👋 Bonjour ${eleves[i]} !</p>`;
}
```

---

## 🟣 6. Discussion et conclusion (2–3 min)

- Expliquer que c’est un métier parfois long, technique, mais aussi très créatif.
- Ouvrir la question :  
  **“Pensez-vous que les développeurs existeront encore quand vous serez grands ?”**
- Aborder **les intelligences artificielles** :
  - Elles peuvent coder, mais il faudra toujours des **humains pour expliquer ce qu’il faut faire**
  - Il sera toujours important de **comprendre comment ça marche**

---

## 📌 Ressources complémentaires

- 🧰 Porsche Design System :  
  [https://designsystem.porsche.com/v3/](https://designsystem.porsche.com/v3/)

- 💾 GitHub Porsche Design System :  
  [https://github.com/porsche-design-system/porsche-design-system](https://github.com/porsche-design-system/porsche-design-system)

- 🎨 Figma Porsche :  
  [https://www.figma.com/@porsche](https://www.figma.com/@porsche)

- 🌐 Site officiel Porsche :  
  [https://www.porsche.com/france/](https://www.porsche.com/france/)

- 📖 Liste des codes d’erreur HTTP :  
  [https://fr.wikipedia.org/wiki/Liste_des_codes_HTTP](https://fr.wikipedia.org/wiki/Liste_des_codes_HTTP)

- 📖 Code 418 "I'm a teapot" :  
  [https://fr.wikipedia.org/wiki/Erreur_HTTP_418](https://fr.wikipedia.org/wiki/Erreur_HTTP_418)
