# TypeScript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

 - l'intéret de TypeScript dans l'IDE  ✔️
Typescript permet de décrire les variables, fonctions et autres éléments du code, cela est utile pour éviter des erreurs de type et améliore la lisibilité du code. Par exemple avec Typescript si on déclare une variable de type number , on ne pourra pas ensuite lui attribuer une valeur de type string sans déclencher une erreur. 

 - les types de bases ✔️
	
 1. **number** : pour les valeurs numériques (flottants et entiers) 	
 2. **string** : les chaînes de caractères 	
 3. **boolean** : les booléens (true ou false) 	
 4.  **array** : un tableau de valeurs, par exemple  `string []` représente un tableau de chaînes de caractères
 5. **any** :    un type flexible qui permet à un élément de prendre n'importe quelle valeur
 6. **null**
 7. **undefined** 
 8. **void** : défini l'absence de type, souvent utilisé pour les fonctions qui ne retournent aucune valeur

 - comment et pourquoi étendre une interface  ✔️
L'extension d'une interface permet à l'interface enfant d'hériter des propriétés de l'interface parent tout en ajoutant de nouvelles propriétés, ce qui est pratique pour éviter la duplication de code. Pour étendre une interface on utilise le mot-clé **extends**

     interface ParentInterface {
     prop1 : string,
     prop2 : number,
     }
    
    interface ChildInterface extends ParentInterface {
    prop3 : boolean
    }
    
    const object : ChildInterface = {
    prop1 : "hello",
    prop2: 25, 
    prop3: true
    } 
    

 - les classes et les decorators ❌ / ✔️

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

### Utilisation dans un projet ❌ / ✔️

[lien github](...)

Description :

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
