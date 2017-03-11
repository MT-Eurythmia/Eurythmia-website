---
layout: default
title: Les FAQ de Mynetest
---

# Les FAQ de Mynetest

Pour jouer à Minetest, il faut surtout bien connaître les différentes icônes en bas de l'inventaire. Celui-ci s'ouvre avec la touche I. En voici une capture d'écran (les numéros sous les icônes serviront dans les explications.)

![Icônes inventaire](images/inventaire_numeros.png "Icônes inventaire")

Plus d'explications sur ces icônes sur la page [premiers pas](premiers_pas.html "Premiers pas").

Voyez également [le lexique](lexique.html "Lexique") pour avoir l'explication des mots anglais et du jargon du jeu en ligne.

<!--Certains liens internes ne marchent pas : que faire des lettre accentuées, des apostrophes et des traits d'unions ?-->

## Sommaire

* [Comment parler aux autres joueurs ?](#comment-parler-aux-autres-joueurs-)
* [Comment téléporter un joueur ?](#comment-téléporter-un-joueur-)
* [Comment protéger ses créations ?](#comment-protéger-ses-créations-)
* [Comment ajouter quelqu'un à une area ?](#comment-ajouter-quelqu-un-à-une-area-)
* [Comment pêcher ?](#comment-pêcher-)
* [Comment apprivoiser les animaux ?](#comment-apprivoiser-les-animaux-)
* [Comment protéger les animaux ?](#comment-protéger-les-animaux-)
* [Comment réparer les outils ?](#comment-réparer-les-outils-)
* [Comment on fait pousser des plantes ?](#comment-on-fait-pousser-des-plantes-)

--------------------------------------------

* [À quelle profondeur trouve-t-on du mithril ?](#a-quelle-profondeur-trouve-t-on-du-mithril-)
* [À quelle profondeur trouve-t-on du nyan ?](#a-quelle-profondeur-trouve-t-on-du-nyan-)
* [Pourquoi mon travelnet ne marche pas ?](#pourquoi-mon-travelnet-ne-marche-pas-)
* [T'as pas… ?](#t-as-pas-)
* [Qui veut être mon ami ?](#qui-veut-etre-mon-ami-?)
* [T'as quel âge ?](#t-as-quel-age ?)
* [Je peux avoir le "fly" ?](#je-peux-avoir-le-fly-)
* [Je peux être modo ?](#je-peux-etre-modo-)
* [C'est quoi une commande ?](#c-est-quoi-une-commande-)
* [Client ? Serveur ? On n'est pas au bistrot !](#client-serveur-on-n-est-pas-au-bistrot-)

----------------------------------------------

## Comment parler aux autres joueurs ?

Pour "dire" quelques-chose qui sera lu par tous les joueurs connectés au serveur, tapez la Touche T (comme "Talk", le mot anglais pour parler", puis tapez votre message. Faites un effort pour écrire clairement, et évitez les messages tout en majuscules : c'est interprété comme un comportement agressif. Tout le monde n'est pas une "bête" en orthographe et certains joueurs sont très jeunes, ou d'origine étrangère ce n'est donc pas très gentil de se moquer de leurs fautes.

Si vous voulez envoyez un message secret à une personne qui est connectée, il va falloir utiliser une comande (une commande c'est un message spécial, destiné au serveur, ce qu'on signale en le faisant débuter par le caractère "/", le "slash"). Pour dire "bonjour à Toto, Tapez T puis `/msg Toto Bonjour` (la commande /msg, demande au serveur de transmettre votre message à un joueur et un seul).

Si vous voulez envoyer un message à un joueur qui n'est pas connecté, utilisez la commande /mail qui marche exactement comme /msg : `/mail Toto Bonjour !`

Voici deux petites astuces pour gagner du temps avec ces commandes :
* si vous tapez directement sur / pour commencer un message, le chat s'ouvrira avec le / déjà en place pour une commande ;
* si vous tapez les trois ou quatre premières lettres du nom d'un joueur *connecté* puis la touche TAB, le nom du joueur se complètera automatiquement (c'est ce qu'on appelle l'autocomplétion).

## Comment téléporter un joueur ?

Vous avez la possibilité d'inviter un autre joueur à vous rejoindre en le téléportant vers vous. Pour cela, cliquez sur l'icône n°3 de l'inventaire : une nouvelle fenêtre s'ouvre.

![tp_screen](images/tp_screen.png "tp_screen")

choisissez le nom du joueur dans le menu déroulant de la dernière ligne et cliquez sur *Send To* pour envoyer l'invitation. Si votre invité vient juste de se connecter, il n'apparaît peut-être pas dans la liste. Pour remettre cette liste à jour, cliquez sur *Refresh*.

Quand vous êtes invité par un autre joueur, vous êtes prévenu par un bruit de sonnette. Dans ce cas, retournez à la même fenêtre (troisième icône de l'inventaire) et acceptez l'invitation en cliquant sur *To Player*. Vous êtes bien sûr libre de refuser l'invitation, mais dans ce cas, prenez au moins le temps d'expliquer gentiment pourquoi ("Désolé, je n'ai pas le temps"…)

## Comment protéger ses créations ?

Pour protéger sa maison ou une autre construction, il faut la placer dans une *Area*, c'est-à-dire une zone qui vous appartient et où personne d'autre ne peut ajouter ou supprimer des blocs.

Pour créer une area, il faut commencer par crafter (fabriquer) des *Markers* :

![Markers](images/markers.png "markers")

Ensuite, vous devez placer deux markers au extrémités d'une des diagonales de la zone à protéger :

![Diagonale](images/diagonale.png "Diagonale")

Faites un clic droit sur un des deux markers, donnez un nom à votre area (Name) et validez. Et voilà ! Votre area est créée. Si vous vous baladez dedans, vous verrez son nom et son ID (son numéro) s'afficher en bas à gauche de votre écran. Vous pouvez récupérer vos markers pour les utiliser plus tard.

**Si vous obtenez un message d'erreur qui vous dit que l'area ne peux pas être créée, c'est sans doute qu'elle est trop grande, ou qu'elle chevauche une area d'un autre joueur. Dans ce cas, rapprochez un peu vos deux markers pour réduire la surface de votre area et essayez à nouveau.**

## Comment ajouter quelqu'un à une area ?

Il faut commencer par crafter unn *Boundary Marker* :

![Boundary marker](images/boundary.png "Boundary marker")

Placez le n'importe où *à l'intérieur de votre area* et faites un clic droit dessus. Dans la case "Add", ajoutez le nom du joueur que vous voulez ajouter et validez. L'autre joueur peut maintenant agir dans l'area exactement de la même manière que vous.

**Si votre area est importante, ajoutez-y seulement des personnes de confiance, autrement c'est une source de chamailleires. Vous pouvez "tester" un joueur en travaillant avec lui sur une area moins "sensible".**

## Comment pêcher ?

Pour pêcher, il vous faudra deux choses : une canne à pêche (*Fishing Pole*) et des appâts :

![Canne à pêche](images/fishing_pole.png "Canne à pêche")

![Appâts](images/bait_corn.png "Appâts")

Comme appâts, vous pourrez aussi utiliser les vers de terre que vous trouverez en labourant vos champs.

Quand vous serez équipé, trouvez un point d'eau suffisamment profond (au moins quatre ou cinq blocs).

Pour que la pêche fonctionne, il faut placer les appâts juste à droite de la canne à pêche dans la première ligne de votre inventaire :

![Pêche](images/peche.png "Pêche")

Prenez la canne à pêche en main comme n'importe quel autre outil et faites un clic gauche pour lancer votre ligne. Vous pouvez lancer une deuxième ligne en faisant un autre clic gauche.

À partir de maintenant, vous devez bien surveiller vos deux bouchons. Quand vous avez une touche, vous en verrez un s'enfoncer et vous entendrez un bruit d'éclaboussement : faites vite un clic droit sur le bouchon pour remonter votre prise. Si vous êtes trop lent, le poisson s'échappe ; si vous êtes assez rapide, un message vous indiquera ce que vous avez pris.

## Comment apprivoiser les animaux ?

Vous croiserez différents animaux dans le monde de Minetest. Il est possible de les apprivoiser pour en tirer des œufs, du lait de la laine et beaucoup d'autres choses.

Pour apprivoiser les animaux, le principe est toujours le même : il faut d'abord des nourrir avec leut aliment favori, jusqu'à ce qu'un message s'affiche, par exemple "Rabbit tamed" si vous avez apprivoisé un lapin.

Ensuite il faut attraper l'animal : pour les plus petits (lapins, poules…) il suffit de faire un clic droit dessus *en ayant les mains vides*. Plusirus clics seront nécessaires, mais attention ! *Si vous faites un clic de trop après avoir capturé l'animal, vous relâcherez celui-ci !*

Pour les gros animaux, il va vous falloir un outil, le *Magic Lasso* que vous utiliserez aussi avec un clic droit :

![Lasso](images/magic_lasso.png "Lasso")

Voici un tableau qui vous explique comment capturer les différents animaux :

| Animal       | Nourriture                | Lasso |
|--------------|---------------------------|:-----:|
| Chat         | Rat                       | Non   |
| Cheval       | Blé (wheat)               | Oui   |
| Lapin        | Carotte (carrot)          | Non   |
| Manchot      | Poisson cru               | Non   |
| Mouton       | Blé (wheat)               | Oui   |
| Personnages  | Diamant (diamond)         | Oui   |
| Poule        | Grain de blé (wheat seed) | Non   |
| Rat          | Rien                      | Non   |
| Sanglier     | Pommes (apple)            | Oui   |
| Vache        | Blé (wheat)               | Oui   |

## Comment protéger les animaux ?

## Comment réparer les outils ?

## Comment on fait pousser des plantes ?

----------------------------------------

## À quelle profondeur trouve-t-on du mithril ?

## À quelle profondeur trouve-t-on du nyan ?

## Pourquoi mon travelnet ne pas ?

## T'as pas… ?

## Qui veut être mon ami ?

## T'as quel âge ?

## Je peux avoir le "fly" ?

## Je peux être modo ?

## C'est quoi une commande ?

## Client ? Serveur ? On n'est pas au bistrot !
