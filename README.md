Le programme présenté est un jeu de calcul mental interactif développé en langage C. Il a pour objectif d’aider les utilisateurs, en particulier les élèves, à s’entraîner sur des opérations mathématiques de base tout en suivant leur progression grâce à un système de score enregistré.

Lorsque le programme démarre, il demande à l’utilisateur de saisir son nom. À partir de ce nom, il recherche dans un fichier texte (scores.txt) si un score précédent a déjà été enregistré. Si un score est trouvé, il l’affiche ; sinon, il commence avec un score de 0.

L’utilisateur accède ensuite à un menu qui lui propose différents types d’exercices :
	•	Addition
	•	Soustraction
	•	Multiplication
	•	Tables de multiplication
	•	Division
	•	Complément à 100
	•	Double ou moitié
	•	Suite logique
	•	Quitter le jeu

Chaque exercice est généré de manière aléatoire à l’aide de la fonction rand(). Pour chaque question, l’utilisateur a trois tentatives pour répondre correctement. Le système de notation est basé sur la rapidité de la bonne réponse : 10 points pour une réponse juste du premier coup, 5 points au deuxième essai, et 1 point au troisième. Si l’utilisateur ne trouve pas la réponse après trois essais, la solution correcte est affichée.

Après chaque exercice, le score est automatiquement mis à jour et sauvegardé dans le fichier scores.txt avec la date et l’heure. Cela permet de conserver un historique des performances de l’utilisateur. Le programme utilise des fonctions dédiées pour gérer la lecture et l’écriture dans le fichier, ce qui rend le code plus structuré et plus lisible.

Ce programme met en pratique plusieurs notions fondamentales du langage C, telles que :
	•	La manipulation des chaînes de caractères
	•	Les boucles while et for
	•	Les conditions if, else et switch
	•	L’utilisation de fichiers (fopen, fclose, fprintf, fscanf)
	•	La gestion du temps (time.h)
	•	La génération de nombres aléatoires (rand, srand)

En résumé, ce projet allie de manière efficace programmation en C et apprentissage des mathématiques. Il représente une application utile et ludique, et constitue un bon exemple d’initiation à la programmation structurée.
