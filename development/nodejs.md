# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- Comment développer en utilisant un système de *livereloading* (`nodemon` par exemple)  ✔️
- La connexion de mon application à une base de données avec et sans ORM/ODM (avec `mongodb` puis `mongoose` par exemple) ✔️
- Le développement d'une API REST et GraphQL (avec les packages `express` et `graphql` par exemple)  ✔️
- *Bonus : la manipulation des fichiers système avec `fs` et l'utilisation des streams en NodeJS* ❌ 

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

```node js
const fs = require('fs');

// Function to read a JSON file asynchronously and parse its content
const readAndParseJSONFile = (filePath) => {
  fs.readFile(filePath, 'utf8', (err, data) => {
    if (err) {
      console.error(`Error reading file: ${err}`);
      return;
    }
    
    try {
      const jsonData = JSON.parse(data);
      console.log('Parsed JSON data:', jsonData);
      // Perform operations with jsonData here
    } catch (parseError) {
      console.error(`Error parsing JSON: ${parseError}`);
    }
  });
};

// Usage: Read and parse a JSON file
const filePath = 'example.json'; // Provide the path to your JSON file
readAndParseJSONFile(filePath);
```

### Utilisation dans un projet  ✔️

[[lien github](...)](https://github.com/YuliaKey/good_corners)

Description :

### Utilisation en production si applicable ✔️

[lien du projet](...)

Description : ❌

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- [lien](https://nodejs.org/en)
-  Le site officiel de Node.js propose une documentation exhaustive, des guides, des tutoriels et des références pour apprendre Node.js et sa bibliothèque standard.

## 🚧 Je franchis les obstacles

### Point de blocage ❌ 

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ 
- action 2 ❌ 
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
