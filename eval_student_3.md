# Retour Student 3

Toutes mes féliciations, tu as parfaitement réussi ce challenge 💪👏⭐️💥

J'ai noté quelques pistes d'amélioration de ton code 😉

Exercice 1
- Parfait

Exercice 2
- Tu testes une condition (avec if) et ensuite tu retournes un boolean...
- Tu peux donc ici faire d'une pierre deux coups `return int%2 === 0`
- Tu peux même pousser vers une === égalité stricte (valeur + type de donnée)

Exercice 3
- Tu aurais pu te faciliter la vie avec l'utilisation de la méthode `split` qui te permet de diviser une string à partir d'un séparateur... plutôt que de rechercher un "." avec une boucle for 😉
https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/String/split

Exercice 4
- Amélioration possible : plutôt que de stocker la string la plus longue et sa longueur dans deux variables séparées, tu aurais pu juste stocker la string et quand tu as besoin d'utiliser sa taille alors tu fais un .length

Exercice 5
- Fonctionnel dans ce cas là... mais que se passe-t-il si on ajoute un tableau dans un tableau dans un tableau dans un tableau (tu m'as compris)... il faudra que tu rajoutes une dimension supplémentaire à ton `sum1+=arr[i][j][p][q][...][z];`
- Tu as utilisé typeof number et typeof string... pour palier à ton problème pourquoi ne pas utiliser... à tout hasard... typeof object (tu retrouves ce type quand tu fais console.log(typeof arr[i]);) ??
- Le nom de variable `sum1` n'est pas forcément le plus approprié étant donné qu'il est très proche du nom de la fonction dans laquelle tu te trouves... je t'encourage à trouver un autre nom pour t'éviter toute confusion
- Attention au "code mort" avec `else if (typeof(arr[i])=="string")` qui ne fait rien...
- Attention à ton indentation

# Retour équipe pédagogique Student 3

⭐️⭐️⭐️ Tout est fonctionnel, bonus compris