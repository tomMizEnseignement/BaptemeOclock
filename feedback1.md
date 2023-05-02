Bonjour,

Premièrement, bravo pour ton code ! Tu as bien compris ce qui a été demandé !
Je te fais quelques retours concernant les quelques choses qui peuvent être améliorées :

Dans ton searchController, tu as utilisé une expression ternaire pour factoriser ton if, ce qui est super. 
Cependant, après le : tu as inclus un opérateur +. 


<img width="528" alt="Etudiant 1 - Image 1" src="https://user-images.githubusercontent.com/103057760/235800367-3a75bd7d-baf8-4fb2-b3aa-c1dc4b28e991.PNG">


Cet opérateur est interprété comme une addition, car ton précédant + est une concaténation de chaînes de caractères. 
Cette addition essaye d’utiliser ta chaîne de caractères searchedElement comme un nombre, or cette chaîne n’est pas un nombre. 

Ce qui te donne une erreur de type NaN, c'est un peu dommage vu que ton application marche très bien ;)

Tu as laissé du code commenté dans quelques endroits de ton application. 
Ce n’est pas grave en soi, mais si un autre développeur veut continuer ton application, 
il ne saura pas si ce code sert à quelque chose ou pas :) Hésite pas à enlever ces bouts de code, ou à les utiliser :) 


<img width="528" alt="Etudiant 1 image 3" src="https://user-images.githubusercontent.com/103057760/235800393-44db216a-a982-413d-a6ba-7bb1972041bc.PNG">



Tu as bien commenté la plupart de ton code, bravo ! Tu peux faire de même pour le reste du code qui n’a pas été commenté ;)

Dans ta recherche par nom, lorsque la recherche ne retourne pas de résultat, tu affiche un message empty dans le corps de ta page. 
Un développeur va comprendre, mais pour un utilisateur ce serait mieux que tu affiches un message plus explicite du type « le résultat 
de la recherche est vide »



<img width="218" alt="Etudiant 1 image 4" src="https://user-images.githubusercontent.com/103057760/235800412-6fedf429-72eb-4462-b0c2-78cb4ca3a153.PNG">


