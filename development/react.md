# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'état (_state_) pour contrôler l'affichage d'un composant  ✔️
- les composants enfants et les _props_ qu'on leur passe ✔️
- le déclenchement d'instructions en fonction des actions de l'utilisateur ✔️
- le déclenchement d'instructions en fonction de l'étape du cycle de vie du composant ou du changement de valeur de ses props ✔️
- l'usage d'un reducer (_useReducer_) pour gérer un état composé dans un composant ❌
- l'état stocké dans un composant avec un _context provider_ et accessible dans ses descendants via `useContext` ✔️

## 💻 J'utilise

### Un exemple personnel commenté  ✔️

import React, { useState } from 'react';

// Component: Counter
const Counter = () => {
  // State hook to manage the counter value
  const [count, setCount] = useState(0);

  // Function to increment the counter
  const increment = () => {
    setCount(count + 1);
  };

  // Function to decrement the counter
  const decrement = () => {
    setCount(count - 1);
  };

  return (
    <div>
      <h2>Counter</h2>
      <p>Count: {count}</p>
      <button onClick={increment}>Increment</button>
      <button onClick={decrement}>Decrement</button>
    </div>
  );
};

// Component: App
const App = () => {
  return (
    <div>
      <h1>React Counter App</h1>
      <Counter /> {/* Render the Counter component */}
    </div>
  );
};

export default App;

### Utilisation dans un projet  ✔️

[lien github](...)

Description :

### Utilisation en production si applicable❌ / ✔️

[[lien du projet](...)](https://github.com/YuliaKey/good_corners)

Description : ❌

### Utilisation en environement professionnel  ✔️

J'utilise React en entreprise où je travaille sur le projet e-commerce React mobile

Description :  ❌

## 🌐 J'utilise des ressources

### Titre

- [lien](https://react.dev/)
- La documentation officielle de React offre des guides, des concepts fondamentaux, des tutoriels, et des références sur toutes les fonctionnalités de React.

## 🚧 Je franchis les obstacles

### Point de blocage ❌ 

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌
- action 2 ❌ 
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ 
- J'ai fait une [présentation](...) ❌ 
