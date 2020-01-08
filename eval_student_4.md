## Retour Student 4

Après un bon départ en réussissant les deux premiers exercices, il semblerait que tu aies eu quelques difficultés pour la suite...

Pour l'exercice 3, tu étais parti sur la bonne voie ! Je t'ai écrit quelques conseils pour t'aider dans la logique à suivre 😉

J'ai vu que les exercices 4 et 5 étaient vides. Est-ce que tu as jeté un oeil et tu ne savais pas comment t'y prendre ou est-ce que tu es resté focalisé sur l'exercice 3 ?

Si tu éprouves des difficultés, n'hésite pas à me contacter ou ton professeur référant sur slack. Le plus tôt sera le mieux, car plus tu attendras plus ce sera difficile de rattraper le vaisseau !! On est là pour ça 😉

**Exercice 3**

Ton idée d'utiliser `lastIndexOf` comme point de départ était bonne, mais quand tu reprends la doc tu peux voir que sa syntaxe d'utilisation est : `str.lastIndexOf(valeurRecherchée[, indiceDébut])`

On ne peut donc lui passer en paramètre qu'une seule valeur à chercher (dans ton cas soit "css", soit "js", soit "eslintrc")... mais d'ailleurs est-ce vraiment ce que tu recherches ?

Cela t'obligerait à rechercher toutes les extensions de fichier comme html, doc, docx, md, et autres pour que ton code fonctionne quelque soit le type de fichier (= code généralisable, transférable à d'autres applications)...

Par contre le point commun à toutes ces extensions est qu'elles sont............ toutes précédées d'un ".", et une fois que tu as récupéré l'index du dernier "." de ta string, tu n'as plus qu'à utiliser une méthode (🤔) pour récupérer la fin de ta string (=== l'extension)...

Tu peux repartir de là avant de regarder la correction 💪💪💪

`// Je récupère l'index du dernier . dans str`

`var lastPoint = str.lastIndexOf('.');`

# Retour équipe pédagogique Student 4

⚠️⚠️⚠️ Élève en difficulté

A réussi uniquement les deux premiers exercices et n'a rien fait dans les autres !!