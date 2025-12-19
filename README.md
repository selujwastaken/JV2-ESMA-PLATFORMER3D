# Duc_Jul_Plat
Platformer 3D

# Description du jeu : 

Space Show est un jeu qui se passe dans l’espace. Le joueur se retrouve dans une sorte d’émission, sur un plateau télé, mais dans l’espace. 
Le plateau est observé par des spectateurs, et des robots sont présents pour filmer et diffuser le show. Ces robots servent de caméras et font partie intégrante du décor et du gameplay.

Le joueur doit avancer dans un parcours en poussant des caisses dans des sortes de tapis afin d’ouvrir des portes et continuer à progresser dans le niveau. 
Le but est d’avancer jusqu’à la fin du parcours. Cependant, les robots peuvent parfois se faire hacker et essayer de renverser la situation en poussant le joueur dans le vide.

La vie du joueur est représentée par les spectateurs qui le regardent. Tant qu’il y a du public, le joueur peut continuer. 
Si le nombre de spectateurs tombe à zéro, la partie est perdue. Le joueur doit donc réussir le parcours tout en gardant l’audience et en donnant une bonne performance.

# Difficultés rencontrées : 

Une des difficultés principales a été la création du Space Bot, car il arrivait parfois qu’il se bloque ou qu’il se cogne contre certains éléments. 
Il a fallu mettre en place des bouts de code pour faire de la prévention, afin qu’il évite certains objets et ne se bloque pas partout.

La difficulté la plus importante a été la mise en place de la prédiction de trajectoire (Predict Path Trajectory). 
Il fallait prendre en compte la distance entre le cube et le joueur, la vélocité actuelle du cube, la vélocité que le cube va prendre avec le radial impulse, la gravité, ainsi que plusieurs autres facteurs.

Le système fonctionne à environ 60 à 70 %. Il montre correctement la direction et donne une idée de l’endroit où l’objet va arriver, mais la courbe et le point d’arrivée ne sont pas toujours exacts.

# Inputs :

Déplacement : ZQSD ou WASD

Menu secondaire : TAB, ECHAP

Radial impulse vers l’extérieur : R

Radial impulse vers l’intérieur : Shift + R

Saut : ESPACE

Augmentation de la force de saut (maintenu) : ESPACE

Saut avec la force accumulée (relâchement) : ESPACE

Interaction avec les objets : E

Lévitation des objets dans un certain rayon : Clic droit

Gestion de l’intensité de la vélocité de la lévitation : Molette de la souris

# Autres Infos : 

## TV Space Bot

Le TV Space Bot est généralement inoffensif.

Il possède un pourcentage de chance de se faire hacker.

En état de hack, il fonce vers le joueur.

En touchant le joueur, le joueur se fait propulse.

Fait perdre un peu de public au joueur.

Un radial impulse à bonne portée arrête l’état de hack.

Arrêter le hack fait regagner un peu de public.

Il y a une petite probabilité de lâcher une canette énergisante quand le joueur arrête l’état de hack.

## Canettes énergisantes

Les canettes énergisantes sont ramassées en marchant dessus.

+25 de stamina maximale

+25 de stamina sur la stamina actuelle

+0,10 au taux de gain de stamina

+10 de public (effet publicité)
