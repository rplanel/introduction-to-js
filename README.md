# introduction-to-js

(Inspiré de https://github.com/iliakan/javascript-tutorial-en et http://eloquentjavascript.net)
* Le javascript est incontournable pour le développement web.
  * Universelle : seul langage disponible sur tous les navigateurs et par conséquent sur toutes les plateformes.
  * Libre.
* Introduit en 1995 pour ajouter des programmes aux pages web afficher par Netscape.
* Un document standard a été écrit pour décrire comment ce langage doit fonctionner (ECMAScript).
* Rien à voir avec le Java (a juste voulu surfer sur la vague de Java pour bénéficier de sa popularité)
* Le javascript est une langage qui peut s'exécuter dans un navigateur mais aussi sur un serveur grâce à un moteur javascript (V8, SpiderMonkey).


Le but de cette formation est de vous donner les bases du langage javascript. Je ne vais pas vous parler (ou très peu) de développement web. Vous le verrez sûrement pendant la formation ou pendant celle que je vous ferai après.

## Ressources
  - https://developer.mozilla.org/en-US/docs/Web/JavaScript
  - http://eloquentjavascript.net/
  - https://javascript.info/

## Environement

Le javascript peut donc s'exécuter de beaucoup de manière différentes.
  * Dans un navigateur.
  * Console du navigateur.
  * En ligne de commande (Node).
  * REPL (Node).
  * Online (jsfiddle) (https://rawgit.com/eu81273/jsfiddle-console/master/console.js)

De nombreux éditeurs existent mais le seul qui vaille la peine est Emacs :D

## Type de données.

* String
  * **'** or **"**
  * Échapper caractère : **\\**
  * Concaténation : **+**
  * **\`** template literals : ``` \`half of 100 is ${100 / 2}\` ```
  * Parler de tout ce qu'on peut faire avec des Strings.
  * String comme des objets.
* Number: Infinity, NaN  : ``` (NaN == NaN ) // false ```
* Boolean
* Array
* Object
* Empty value: null, undefined

## Opérateur
  Les mêmes que pour python sauf : 
   - == vs ===
     - 1 == "1" => true
     - 1 === "1" => false
     - undefined == null => true
     - undefined === null => false

## Conversion automatique.
  Javascript est très tolérant et donc il ne prévient pas forcément quand on fait des bêtises.
  ```
  console.log(8 * null)
  // → 0
  console.log("5" - 1)
  // → 4
  console.log("5" + 1)
  // → 51
  console.log("five" * 2)
  // → NaN
  console.log(false == 0)
  // → true
  ```


## Les variables

Il existe 3 manières de déclarer des variable en javascript:
  * **var** (porté fonction).
  * **let** (block).
  * **const** (block)



## Structure de données

  * Map
  * Set

## Fonctions


## Promesses