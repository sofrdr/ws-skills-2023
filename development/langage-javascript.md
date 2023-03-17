# Langage Javascript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les `structures` de base du langage ✔️
- les normes `ecmascript` ✔️
- l'utilisation de l'`asynchrone` ✔️

On utilise l'asynchrone pour des fonctions dont l'exécution prend du temps et qui renvoient une promesse. Afin de ne pas bloquer le reste du script, elles sont exécutées en parallèle.  C'est par exemple le cas pour les fonctions utilisant l'API Fetch qui permet de récupérer ou envoyer de la donnée à une API.
On peut utiliser les mots-clés then et catch ou bien une syntaxe plus récente avec les mots-clés async et await.

Par exemple : 

    // Function to get all skills from BDD
    
    const  getSkills = async () => {
    
    try {
    
    const  response = await  fetch(url);
    
    const  data = await  response.json();
    
    return data;
    
    } catch (error) {
    
    console.log(error);
    
    }};
- les spécifités du mot-clef `this` ❌ / ✔️

## 💻 Je code en Javascript
### Un exemple de code commenté  ✔️

  Fonction qui convertit un nom en initiales :
       
     function abbrevName(name){
        
          const nameArray = name.split(" ")
          return nameArray.map((name, i) => i === 0 ? name.charAt(0).toUpperCase() + "." : name.charAt(0).toUpperCase()).join("")
        }


Fonction pour obtenir la valeur minimale d'une liste : 

    class SmallestIntegerFinder {
      findSmallestInt(args) {
        args.sort((a,b) => a-b)
        return args[0]
        }
    }


### Utilisation dans un projet  ✔️

 - [Projet Kanap](https://github.com/sofrdr/P5--Kanap)
   
   Description : Projet de formation Openclassrooms. Développement de la
   partie front-end d'un site e-commerce de canapés en Javascript.
   Manipulation du DOM, ajouts d'évènements, contrôle des données avec
   Regex, gestion d'un panier.

### J'ai utilisé ce langage en production ❌ / ✔️

[lien du projet](...)

Description :

### J'ai utilisé ce langage en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description: Programmation Orientée Objet

Plan d'action : (à valider par le formateur)

- action 1 : Pratiquer les classes


Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️

