THP - Projets : Data scientist

Dans le cadre de la formation The Hacking Project, voici les problèmes que nous avions à résoudre :
  
*Big data*
Avec ton groupe, vous avez entendu parler d'un concept qui marche bien nommé le Big Data. Vous vous êtes chauffés pour vous lancer dedans et proposer des prestations de conseil facturées à des prix indécents. Grâce à vos super compétences en réalisation de Landing Pages, vous avez déjà votre premier client : une entreprise de Growth Hacking. Cette dernière a obtenu une liste de plusieurs centaines de comptes Twitter qu'ils voudraient analyser.

Voici un array de handle Twitter (l'équivalent d'un nom de login chez Twitter) de journalistes (pour info, c'est des vrais !):
À partir de cette array, code un programme ruby qui répondra aux questions suivantes :

 - Combien y a-t-il de handle dans cette array ?
 - Quel est le handle le plus court de cette liste ?
 - Combien y-a-t'il de handle contenant 5 caractères (le @ ne compte pas pour un caractère)
 - Combien commencent par une majuscule (première lettre juste après le @) ?
 - Trie la liste de handle par ordre alphabétique.
 - Trie la liste de handle par taille des handle (les plus petits en premiers, les plus grands après)
 - Quelle est la position dans l'array de la personne @epenser ?
 - Sors-moi une répartition des handle par taille de ces derniers (nombre de handle avec 1 caractère, nombre de handle avec 2 caractères, nombre de handle avec 3 caractères, etc)

Si tu as bien compris, quand tu lances le script, les réponses aux questions s'affichent sur ton écran de Terminal via des puts. N'hésite pas à ajouter un peu de pep’s à ton programme en écrivant des phrases, en ajoutant des blagues, voir en faisant un menu (pour les plus chauds) où l'utilisateur peut choisir, dans une liste, la question à laquelle le programme va répondre.

*Blockchain*
Après le succès de votre firme, vous vous êtes dits que vous pourriez mélanger deux fois plus de buzzwords et faire une firme qui fait de la big data sur de la blockchain. Votre idée est en train de disrupter le consulting et tous les grands groupes en quête de digitalisation veulent faire appel à vos services. Vous venez de signer un contrat pour Carrefour.io et vous allez devoir analyser des données de cryptomonnaies.

Maintenant on va travailler avec des hash, à partir de deux arrays : devises et prix.

Une fois cette association réalisée, code un programme Ruby pour donner :

La ou les crypto qui ont la plus grosse valeur.
La ou les crypto qui ont la plus petite valeur.
Les devises dont le cours est inférieur à 6000
La devise la plus chère parmi celles dont le cours est inférieur à 6000.