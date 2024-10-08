# TP #2 : Intégration `React`/`Firebase`
## Bande quotidienne *Jean-Sébastien et Éric*
### Environnement nuagique `Firebase` à intégrer : `Firestore`, `Authentication`, `Storage`, et `Hosting`

## Objectif/exigences généraux
* Vous créez une application `React` monopage nommée *Jean-Sébastien & Eric* (sigle : `jse`) dont les fonctionnalités minimales sont énumérées dans ce document (*démo* à la fin de ce devis)

>SVP prendre note que les *bandes quotidiennes* sont la propriété intellectuelle de `Dominic Gibeau`, et votre droit d'utilisation des images de ces bandes est limité à ce travail académique.

* Vous devez créer votre application avec les fonctionnalités exigées et illustrées dans la *démo*, mais la conception graphique, et l'interactivité sont entièrement libres (faites preuve de créativité et d'originalité !)

* L'interface utilisateur (UI) de votre application doit être adaptative (fonctionnelle, utilisable et conviviable sur toutes tailles d'écrans raisonnables : ça va être un défi d'afficher la *bande quotidienne* sur un appareil mobile... j'ai ma propre idée, mais avez-vous la vôtre ?) De plus, votre application doit être visuellement attrayante et bien sûr *réactive* et animée

* Les images utilisées dans l'application sont stockées dans `Firebase Storage`

* La gestion des utilisateurs est faite avec `Firebase Authentication` (uniquement `Google Provider` est demandé, mais si vous voulez implémenter plus de modes d'authentification, vous êtes bien sûr libre de le faire)

* Les données utilisateurs de l'application sont stockées et gérées dans `Firebase Firestore` ; certaines données doivent être gérées en temps réel (par exemple, le *plébiscite*, les *commentaires*, et les *votes* sur les commentaires)

* Votre application doit être hébergée sur `Firebase Hosting`, mais attention, les fichiers de déploiement doivent être obfusqués et compressés, et produits sans fichiers `sourcemap` (autrement dit attendez mes instructions en classe avant de déployer !)

* Utilisez `Sass` pour produire votre code `CSS` : un fichier par composant SVP ! 

* Les composants `React` doivent utiliser la syntaxe *fonctionnelle* (la seule que nous avons vu en classe)

* Préférez le code *déclaratif* (ou *fonctionnel*, ou *expressif*) au lieu du code *impératif* partout où c'est possible : on en a parlé en classe, mais sinon me demander des explications additionnelles au besoin