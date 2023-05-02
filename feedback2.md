Bonjour,

Premièrement, bravo pour ton travail !

Je te fais quelques retours concernant les quelques choses qui peuent être améliorées :

Dans le deck, il fallait afficher les informations suivantes : nom, élément de la carte, niveau de la carte, orientation (nord, sud, est, ouest). Tu as affiché le nom mais pas les autres informations. 
Et tu as utilisé la donnée card.price qui n’existe pas :

<img width="419" alt="Etudiant 2 - image 1" src="https://user-images.githubusercontent.com/103057760/235800850-4ac381cc-4ac2-44cc-863f-089f69c312fb.PNG">


Les données que tu peux utiliser sont celles qui sont dans le fichier cards.json, comme dans l’exemple de cette carte :

<img width="531" alt="Etudiant 2 image 3" src="https://user-images.githubusercontent.com/103057760/235800961-93b7a88a-75b3-47ed-8c50-b2f19cba36e0.PNG">


Tu peux utiliser les données : name, values, element, level, visual


Pour ton deck, il y a un petit problème d’affichage. 
Tu as voulu utiliser des tableaux, c’est bien ! mais tu n’utilises qu’une seule colonne pour l’image et le nom. L’espacement entre les éléments est également un peu petit, ce qui enlève de la clarté à l’affichage. Tu pourrais ajouter de l’espacement aux éléments de ton tableau, ou utiliser le même type d’affichage que la page d’accueil avec des dis (pour gagner du temps).

Tu as affiché les résultats de ta recherche par élément de la façon suivante :



<img width="253" alt="Etudiant 2 image 4" src="https://user-images.githubusercontent.com/103057760/235801095-01dcd40b-3b22-4f8e-8eec-b56d2da83fad.PNG">


C’est bien ! Petite amélioration : tu pourrais afficher les images et les informations des cartes directement dans la page de résultat.

Pour tes recherche par valeur, niveau et nom, tu n’as pas implémenté les fonctionnalités, ce qui n’est pas grave ! 
Mais pour la prochaine fois, tu peux afficher un message utilisateur quand on rentre sur ces pages, car actuellement le rendu est le suivant :


<img width="293" alt="Etudiant 2 image 5" src="https://user-images.githubusercontent.com/103057760/235801256-c2f4e19c-3254-4ee1-87e8-7d15d1f11a5b.PNG">

