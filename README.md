#TaggedTwitter 

##Concept
TaggedTwitter est fortement inspiré de Twitter, à l'exception que la communauté ne peut publier des messages portant que sur un seul sujet à la fois. 

Ce sujet (tag) est déterminé automiquement, et est modifié toutes les 10 minutes. 

##Différents modules requis, *a minima*, pour la V1

###Utilisateurs
Il doit évidemment être possible de s'inscrire sur le site. Il d'ailleurs nécessaire de le faire avant de pouvoir poster ou consulter des messages.

Au moment de l'inscription, seuls l'email, le pseudo et le mot de passe sont demandés. 

Une fois l'inscription complétée, l'utilisateur est amené à compléter son profil, en y ajoutant, au minimum, un court descriptif de qui il est, et une photo. 

###Tags
Les tags sont donc choisis parmi une base de tags, et le tag du moment est renouvelé à toutes les 10 minutes. 

Les messages postés pendant ces 10 minutes sont donc nécessairement reliés au tag actuel. 

###Messages
####Création
Un message doit avoir au maximum 140 caractères. Il est possible d'y adjoindre, en plus, une url et/ou une image et/ou une vidéo youtube. 

####Lecture
Les messages sont affichés du plus récent au plus ancien, et le tag sur lequel ils portaient doit graphiquement être mis en évidence.

L'auteur (nom et pic), la date, le message, l'image, l'url et/ou la vidéo doivent être affichés, de même que le bouton "étoile", auprès duquel s'affiche le nombre d'étoiles reçues.

Il doit être possible de n'afficher que les messages portant sur un tag précis. 

Il doit être possible de n'afficher que les messages d'un utilisateur, en se rendant sur la page de celui-ci. 

####Modification/Suppresion
Une fois publié, un message ne peut plus être modifié. Il peut toutefois être supprimé par son auteur. 

###Back-office
Les administrateurs du site ont évidemment besoin d'un back-office. Dans celui-ci, ils doivent pouvoir réaliser les actions suivantes : 

- Gérer les tags (ajout, suppresion, modification, consultation)
- Bannir des utilisateurs


##Méthodologie
Quelques conseils afin de bien démarrer : 

1. Faire une liste précise des tâches à accomplir (pages et fonctionnalités)
2. Entendez-vous sur la structure des dossiers, nommage des fichiers
3. Faites la structure de la base de données ensemble (grandes lignes au moins)
4. Faites une maquette sur papier ensemble  (grandes lignes au moins) 
5. Créer un dépôt git sur le github.com de l'un d'entre vous
6. Cloner tous ce dépôt en local
7. Distribuez-vous les tâches
8. Go

##Équipes

#####FreTo
- Tony
- Frédéric

#####JuNi
- Julien
- Nicolas

#####AlSe
- Ali
- Sébastien

#####JeAl
- Alexandre
- Jérôme

#####FloJo
- Florian
- Joël

#####DeNaMy
- My-Dao
- Nadia
- Denis