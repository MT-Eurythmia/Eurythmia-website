---
layout: default
title: Les FAQ de Mynetest
---

# Les FAQ de Mynetest

Pour jouer à Minetest, il faut surtout bien connaître les différentes icônes en bas de l'inventaire. Celui-ci s'ouvre avec la touche I. En voici une capture d'écran (les numéros sous les icônes serviront dans les explications.)

![Icônes inventaire](images/inventaire_numeros.png "Icônes inventaire")

Plus d'explications sur ces icônes sur la page [premiers pas](premiers_pas.html "Premiers pas").

Voyez également [le lexique](lexique.html "Lexique") pour avoir l'explication des mots anglais et du jargon du jeu en ligne.

<!--TODO : certains liens internes ne marchent pas : que faire des lettre accentuées, des apostrophes et des traits d'unions ?-->

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
* [Comment enchanter un objet ?](#comment-enchanter-un-objet-)
* [Comment vendre des objets ?](#comment-vendre-des-objets-)
* [Comment utiliser le Travelnet ?](#comment-utiliser-le-travelnet-)

![sep](images/sep.png "sep")

* [À quelle profondeur trouve-t-on du mithril ?](#a-quelle-profondeur-trouve-t-on-du-mithril-)
* [À quelle profondeur trouve-t-on du nyan ?](#a-quelle-profondeur-trouve-t-on-du-nyan-)
* [T'as pas… ?](#t-as-pas-)
* [Qui veut être mon ami ?](#qui-veut-etre-mon-ami-?)
* [T'as quel âge ?](#t-as-quel-age ?)
* [Je peux avoir le "fly" ?](#je-peux-avoir-le-fly-)
* [Je peux être modo ?](#je-peux-etre-modo-)
* [C'est quoi une commande ?](#c-est-quoi-une-commande-)
* [Client ? Serveur ? On n'est pas au bistrot !](#client-serveur-on-n-est-pas-au-bistrot-)

![sep](images/sep.png "sep")

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

Faites un clic droit sur un des deux markers, dans la dernière ligne donnez un nom à votre area et validez en cliquant sur *Protect area*. Et voilà ! Votre area est créée. Si vous vous baladez dedans, vous verrez son nom et son ID (son numéro) s'afficher en bas à gauche de votre écran. Vous pouvez récupérer vos markers pour les utiliser plus tard.

![menu_markers](images/menu_markers.png "menu_markers")

**Si vous obtenez un message d'erreur qui vous dit que l'area ne peux pas être créée, c'est sans doute qu'elle est trop grande, ou qu'elle chevauche une area d'un autre joueur. Dans ce cas, rapprochez un peu vos deux markers pour réduire la surface de votre area et essayez à nouveau.**

## Comment ajouter quelqu'un à une area ?

Il faut commencer par crafter unn *Boundary Marker* :

![Boundary marker](images/boundary.png "Boundary marker")

Placez le n'importe où *à l'intérieur de votre area* et faites un clic droit dessus. Cliquez su le bouton *Add*, et entrez le nom du joueur dans la petite fenêtre qui s'ouvre ; validez. L'autre joueur peut maintenant agir dans l'area exactement de la même manière que vous.

![menu_boundary](images/menu_boundary.png "menu_boundary")

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

Si vous voulez empêcher les autres joueurs de tuer vos animaux, il faut d'abord les garder sur l'une de vos area en les enferment sans un enclos ou dans un bâtiment. *Attention !* les animaux peuvent se faufiler entre deux blocs disposés en diagonale et certains sont capables de sauteer très haut.

Ensuite, vous aurez besoin d'une rune de protection :

![mp_rune](images/mp_rune.png "mp_rune")

Prenez-là en main, et faites un clic droit sur l'animal que vous voulez protéger. La rune disparaît de votre inventaire et un message vous indique que l'opération a réussi : l'animal est protégé *tant qu'il reste sur votre area* ; s'il en sort, les autres joueurs (ou les autres mob) peuvent le tuer.

Vous pouvez aussi donner un nom à vos animaux à l'aide d'un *nametag* :

![nametag](images/nametag.png "nametag")

Prenez-le en main et faite un clic droit sur l'animal. Dans la petite fenêtre qui s'ouvre tapez le nom qui s'affichera au-dessus de lui par la suite. Si l'animal est en bonne santé, le nom sera écrit en vert. Dans le cas contraire il sera en orange ou en rouge. Vous pouvez régénérer les points de vie d'un animal en lui donnant sa nourriture favorite.

## Comment réparer les outils ?

Quand vous utilisez un outil, il s'use petit à petit. Sous son icône, une barre raccourcit et change de couleur pour vous indiquer son état. Quand la barre est rouge et très courte, il est temps de réparer votre outil sous peine de le perdre définitivement.

Pour cela il va vous falloir un établi (*Workbench*) et un marteau (*Hammer*) :

![workbench](images/workbench.png "workbench")

![hammer](images/hammer.png "hammmer")

Placez l'établi comme un bloc normal, faites un clic droit et placer l'outil et le marteau comme sur cette image :

![repair](images/repair.png "repair")

Une barre d'usure va apparaître sous le marteau et diminuer progressivement pendant que celle de l'outil se rallonge. C'est un peu long, mais vous aurez bientôt un outil tout neuf. *Note* : cela ne marche que si vous restez à proximité de l'établi, mais vous pouvez fermer la fenêtre et faire autre chose en attendant.

*La case Cut est prévue pour recevoir des blocs que vous pourrez découper en pièces plus fines : planchettes, marches d'escalier…*

## Comment on fait pousser des plantes ?

C'est un peu compliqué et je vous conseille de lire ce qui concerne l'agriculture sur la page [premiers pas](premiers_pas.html "Premiers pas". En règle générale vous devez labourer la terre à l'aide d'une houe (*hoe*) et vous assurer que vous êtes assez près de l'eau (trois cases).

![hoe](images/hoe.png "hoe")

## Comment enchanter un objet ?

Vous pouvez enchaner certains objets pour les rendre plus efficaces. Les armes et les pioche pourront devenir plus efficaces ou plus durables, les pièces d'armure debviendront plus solides et les bottes enchantées vous permettront de vous déplacer plus vite.

Pour enchanter un objet, il vous faudra des cristaux de mese et une table d'enchantement :

![enchantment_table](images/enchantment_table.png "enchantment_table")

Faites un clic droit sur votre table d'enchantement, placez le mese et l'objet à enchanter comme sur la capture, et choisissez à droite l'enchantement que vous voulez appliquer.

![enchantment](images/enchantment.png "enchantment")

*Vous ne pouvez pas enchanter certains objets, notamment ceux en nyan et en mithril.*

## Comment vendre des objets ?

Depuis peu, le serveur intégre un mod qui permet de créer une sorte de distributeur automatique à l'aide des *Vending Machines*. Pour commencer, il vous faudra un coffre verrouillé (*Locked_Chest*) et une machine (*Vending Machine*) :

![locked_chest](images/locked_chest.png "locked_chest")

![vending_machine](images/vending_machine.png "vending_machine")

Posez le coffre au sol et posez la machine par-dessus (pour poser un objet sur un coffre, sans ouvrir le coffre, maintenez la touche Maj et faites un clic droit) :

![vending](images/vending.png "vending")

En faisant un clic droit sur la machine, vous accédez à sa fenêtre de configuration :

![menu_vending](images/menu_vending.png "menu_vending")

Dans la case *Offered Item*, faites glisser l'objet que vous voules vendre. Vous pouvez vendre pas lot en modifiant le chiffre dans la case d'à côté. Le prix est toujours payé en lingots d'or ; la case permet d'entrer le nombre de lingots que coûtera un lot d'objets (dans notre exemple, un "lot" d'un cristal de mese coûte un lingot d'or).

Vous remarquerez enfin un petit point rouge en haut à droite : il indique que votre machine n'est pas prête à fonctionner : elle utilise le coffre placé en dessous d'elle comme un réservoir dans lequel elle va "pomper" les objets à vendre. Mettez des cristaux de mese dans ce coffre et revenez au menu de configuration de la machine : le rond doit maintenant être vert.

**Pour acheter dans une machine qui appartient à quelqu'un d'autre, cliquez sur le bouton Buy.**

## Comment utiliser le Travelnet ?

Vous pouvez poser des cabines *Travelnet* où vous le souhaitez pour avoir ensuite la possibilité de vous téléporter de l'une à l'autre. Pour commencer, fabriquez un petit réseau de test avec deux cabines cabines :

![travelnet](images/travelnet.png "travelnet")

Une fois vos cabines en place, il faudra les configurer toutes les deux (clic droit) :

![menu_travelnet](menu_travelnet.png "menu_travelnet")

Dans la première ligne, tapez le nom de la cabine (un nom qui rappelle l'endroit ou elle se trouve : "Maison", "Mine", "Magasin"…).

Dans la deuxième ligne, entrez le nom du réseau auquel appartient la cabien. Chaque joueur peut se créer plusieurs réseaux, et une cabine permet de voyager uniquement sur le réseau auquel elle appartient.

**Faites bien attention à l'orthographe en remplissant cette case : la moindre faute crée un nouveau réseau et vos cabines, sur des réseaux, différents ne pourront pas communiquer.**

La troisième ligne sert simplement à taper votre nom.

Pout utiliser votre réseau, faites un clic droit sur une cabine configurée et choisissez votre destination parmi celles qui vous sont proposées. Si vous ne voyez pas votre deuxième cabine sur ce réseau, vous avez peut-être fait une faute de frappe en la configurant : vérifiez !

Pour reconfigurer une cabine, il faut d'abord la détruire, puis la remettre en place. *On ne paut pas détruire une cabine qui n'a pas encore été configurée*

**Quand vous ajoutez une cabine à un réseau, celle-ci n'est pas automatiquement détectée par les autres cabines de ce réseau.** La nouvelle cabine n'apparaîtra donc pas dans la liste des destinations porposées par les autre cabines. Il faut donc mettre à jour ces autres cabines : pour cela, frappez-les en faisant un clic gauche. Comme avec les machines à café, il faut taper sur les travelnets pour les faire marcher :-)

![sep](images/sep.png "sep")

## À quelle profondeur trouve-t-on du mithril ?

## À quelle profondeur trouve-t-on du nyan ?

## T'as pas… ?

## Qui veut être mon ami ?

## T'as quel âge ?

## Je peux avoir le "fly" ?

## Je peux être modo ?

## C'est quoi une commande ?

## Client ? Serveur ? On n'est pas au bistrot !
