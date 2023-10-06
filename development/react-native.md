# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les différences et points communs entre du code react et du code react native ✔️

 React Native est un framework de développement d'applications mobiles créé par Facebook. Il permet de créer des applications mobiles pour iOS et Android en utilisant principalement JavaScript et React.
 React Native se base sur des concepts propre à React comme les éléments JSX, le state et l'utilisation de hooks mais utilise des composants spécifiques qui seront transformés en code natif Android ou IOS. Par exemple le composant <View/> est spécifique à React Native et s'apparente à une <div> de React.
  
- ce que devient et comment est interprêté le code javascript dans une application react native ✔️
  
 Le code des composants React est transpilé (généralement par Babel) en un code JavaScript natif compatible avec le système d'exploitation cible (iOS ou Android). 
 React Native utilise des modules natifs pour accéder aux fonctionnalités mobile spécifiques (ex: l'accès à la caméra, géolocalisation...). Ces modules natifs sont écrits en Objective-C ou Swift pour iOS et  en Java ou Kotlin pour Android. Le code JavaScript communique avec ces modules natifs via un pont JavaScript-Natif.

- les avantages et inconvénients de react native  ✔️

  Les avantages de React Native sont multiples :
  1. Développement multi-plateforme => une seule base de code pour développer des applications iOS et Android.
  2. Réutilisation de composants React et moins de duplication de code.
  3. Facilité de développement : la connaissance de React suffit pour développer une application mobile.
  4. Accès facile aux modules natifs.
  5. La communauté est importante, ce qui permet de trouver facilement des solutions en cas de blocage et offre un large choix de bibliothèques tierces.

  Quelques inconvénients :
  1. La performance de l'application peut être réduite pour certaines tâches qui demandent des calculs intenses à cause du pont Javascript-natif.
  2. Les nouvelles fonctionnalités natives peuvent ne pas être immédiatement prises en charge par React Native.
  3. Selon la complexité du projet il vaudra peut être mieux utiliser du code natif pour améliorer l'expérience utilisateur.
     
- la différence entre react native et expo ✔️

  Expo est un framework open source construit autour de React Native pour simplifier le développement d'applications mobiles. L'expérience de développement sera plus rapide qu'avec React Native CLI grâce à un choix de bibliothèques, de fonctionnalités et d'API prêts à l'emploi mais aura une certaine limite quant à la personnalisation et l'accès à des fonctionnalités natives avancées.
  
- les principales briques qui composent react native (core components)  ✔️

  <View/> : un conteneur similaire à une <div>
  <Text/> : un composant pour afficher du texte
  <Image/>
  <TextInput/> : un composant qui permet à l'utilisateur de saisir du texte
  <Button/> : un bouton avec un évènement associé 'onPress'
  
- comment écrire du style en react native ✔️

  Un objet styles est créé avec l'utilisation de la méthode create sur le composant StyleSheet :
  const styles = StyleSheet.create({
  container: {
    flex: 1,
    padding: 24,
    backgroundColor: '#eaeaea',
  },
  title: {
    marginTop: 16,
    paddingVertical: 8,
    borderWidth: 4,
    borderColor: '#20232a',
    borderRadius: 6,
    backgroundColor: '#61dafb',
    color: '#20232a',
    textAlign: 'center',
    fontSize: 30,
    fontWeight: 'bold',
  },
});

Les propriétés de styles sont écrites en camel case et les noms de classe sont appelés depuis l'objet styles. 

Exemple :  <View style={styles.container}>
    <Text style={styles.title}>React Native</Text>
  </View>
  
- comment est géré le layout en react native ❌ / ✔️

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
