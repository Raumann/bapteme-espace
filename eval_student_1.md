# Retour Student 1

Bravo pour ton travail !! Tout fonctionne parfaitement 💪👏 et tu n'es pas passé loin de réussir entièrement le bonus 🙌

Globalement tu as très bien assimilé la logique js et ses principes de fonctionnement ! J'ai noté quelques fioritures au passage pour t'aider à aller toujours plus loin, plus fort, plus vite 🎵🎵🎵

Exercice 1
- Possible de factoriser un peu plus ton code en retournant directement le résultat `return int * 2`

Exercice 2
- Tu testes une condition (avec if) et ensuite tu retournes un boolean...
- Tu peux donc ici faire d'une pierre deux coups `return int%2 === 0`

Exercice 3
- Parfait

Exercice 4
- Tu aurais pu vérifier en amont le type de données contenu dans ton tableau (`typeof arr[index]`) car `arr[index].length` te renvoie "undefined" lorsqu'il s'agit d'un nombre. Cela n'empêche pas ton code de fonctionner mais c'est un peu plus propre

Exercice 5
- Bel effort avec 3 conditions de test passées sur 4, on n'était pas loin du perfect, félicitations !! Tu veux savoir ce qui t'a empêché d'y parvenir ? Regarde du côté de `isNaN`
- `isNaN` retourne false si la valeur est de type number sinon isNaN retourne true. Dans le dernier test, ta condition `if (isNaN(arr[i]))` est true lorsque la boucle tombe sur une valeur de type object, qui sera donc ignorée dans ton calcul... or, toi tu veux rentrer dedans et récupérer les valeurs qui s'y trouvent !!
- Pour palier à ton soucis essaie plutôt d'utiliser `typeof` que isNaN... selon le type que tu récupères tu fais tel ou tel traitement...

Global
- Un petit conseil pour l'avenir quand tu metteras des sites en production, pense à retirer les `console.log` 😉


# Retour équipe pédagogique Student 1

⭐️ A réussi tous les exercices + quasi le bonus

- Compréhension+++
- Logique+++