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

 - [Kanap](https://github.com/sofrdr/P5--Kanap)   
   Projet de formation Openclassrooms. Développement de la
   partie front-end d'un site e-commerce de canapés en Javascript.
   Manipulation du DOM, ajouts d'évènements, contrôle des données avec
   Regex, gestion d'un panier.
   
 - [ Hot Takes - Application d'avis gastronomiques](https://github.com/sofrdr/P6-Piiquante) 
Projet de formation Openclassrooms qui consistait à créer une API sécurisée pour une application web de critique de sauces piquantes. Les utilisateurs devaient pouvoir ajouter leurs sauces préférées et liker/disliker les sauces ajoutées par les autres. Développement avec Node.js/Express/MongoDB.

- [ Groupomania - Réseau social d'entreprise](https://github.com/sofrdr/P7-Groupomania)
Projet de formation Openclassrooms qui consistait à créer un réseau social interne aux employés de l'entreprise Groupomania. Utilisation de Node.js/Express/SQLite pour la partie back et de React pour la partie front. Création de compte et authentification de l'utilisateur, gestions des droits pour la modification et suppression de posts, possibilité de créer un post avec une image. 

- [ Tennis Game](https://github.com/sofrdr/WeCount-tennis-project)
Test technique qui consistait à créer un mini-site qui simule le déroulé d'un match de tennis. Le backend devait renvoyer le score et le nom du gagnant selon les règles du tennis.

- [ WildersBook](https://github.com/sofrdr/wilders-book)
Projet de formation Wild Code School. Création d'une API avec Node.js/Express/SQLite et typeorm. Développement de la partie front avec React. Affichage d'une liste de wilders, création d'un nouveau wilder, ajout et suppression de compétences. 

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

