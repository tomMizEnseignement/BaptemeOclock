Bonjour,

Premièrement, bravo pour ton travail !

Je te fais quelques retours concernant les quelques choses qui peuvent être améliorées :




<img width="356" alt="Etudiant 3 image 1" src="https://user-images.githubusercontent.com/103057760/235801573-e74fd881-3735-4644-8f57-d383b7ee6702.PNG">



Dans ta page de détail de carte, tu affiches les informations de la carte avec une boucle. Or l’objet carte n’est pas un tableau, c’est un objet qui contient plusieurs propriétés. Il faut donc y accéder sans boucle, ou transformer l’objet en un tableau pour pouvoir boucler dessus. 
De plus, tu utilises une variable card, qui n’est définie nulle part. En effet, la carte est transmise depuis ton mainController, mais sous le nom de oneCard et pas de card :


<img width="380" alt="Etudiant 3 image 2" src="https://user-images.githubusercontent.com/103057760/235801600-552ee12d-815b-40d6-8b0b-73f295d601fe.PNG">



Il faudrait donc utiliser la variable avec le nom oneCard dans cardDetails.ejs.

Une fois que t’auras résolu ce problème, l’affichage de l’image de la carte ne marche pas parce que tu as rajouté une extension .jpg, or elle est déjà présente dans l’image dans le fichier json.


<img width="529" alt="Etudiant 3 image 3" src="https://user-images.githubusercontent.com/103057760/235801638-0d4e4dd4-a1a4-4c4f-a707-4b0e019c1c5e.PNG">


Tu n’as donc pas besoin d’extension :)
