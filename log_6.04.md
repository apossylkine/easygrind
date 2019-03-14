Revision: 918
Author: LeGuen
Date: vendredi 8 mars 2019 16:38:54
Message:
6.04

*Fraises
-New : CHANFREIN Dep Secondaire : le paramètre page travail Dep Prim Chanfrein est en plus du Dep. Sec Chanfrein
-New : CHANFREIN Dep Secondaire : Pente chanfrein en page travail

----
Revision: 917
Author: LeGuen
Date: vendredi 8 mars 2019 15:37:19
Message:
6.04
*Fraise Mere
-New : palpage de controle de l'hélice. Nouveau module. Chercher FnPalpage_Helice_Controle pour l'éactivation. 
Testé en simulation sur une seule dent. Fonctionne. Le palpage du multi dent fonctionne mais je rencontre des difficultés avec le stockage. 

*Fraises
-New : CHANFREIN Dep Secondaire : le paramètre page travail Dep Prim Chanfrein a été remplacé par le paramètre Dep. Sec Chanfrein
----
Revision: 916
Author: Possylkine
Date: mercredi 6 mars 2019 10:31:08
Message:
eSim :
- Improved : Detection de collisions (toujours pas en rapide though...)
----
Revision: 915
Author: LeGuen
Date: mardi 26 février 2019 17:21:35
Message:
6.04
*IoT
-New : le compteur _CN_Dernier_Travail (E30121) n'était jamais utilisé. Je l'ai transformé en _CN_Tot_Travail et initialisé comme il faut.
----
Revision: 914
Author: LeGuen
Date: mardi 26 février 2019 12:30:42
Message:
6.04
*Alésoirs
-New : suppression du nouveau palpage suite à demande ASP.
----
Revision: 913
Author: LeGuen
Date: mardi 26 février 2019 12:29:44
Message:
6.04
*Fraise mere
-New : palpage de contrôle de l'hélice : développement en cours

*Alésoirs
-New : activation du nouveau palpage suite à demande ASP. Cela sera supprimé dans le commit suivant.
----
Revision: 910
Author: LeGuen
Date: mercredi 20 février 2019 13:23:37
Message:
6.04
*Général
-Fixed #84 : chez BH, ils ont un message d'erreur récurrent, qui serait peut être dû à une mauvaise gestion des Gestures. Ces gestures ne servent à rien, je les ai supprimées
----
Revision: 908
Author: Possylkine
Date: jeudi 14 février 2019 17:12:06
Message:
Simulation 3D :
- New :
eSim 1.5!
MW 2019!!
Nouveau systeme de collisions
#67 => Nouvelle version MW
#10
#7 => a tester
#61 => a tester

----
Revision: 906
Author: Ferrari
Date: jeudi 14 février 2019 10:49:21
Message:
6.04 *BROCHE CONCAVE :
Travail "Face de COUPE" : Autorisation de l'option "Inverser Nb.Dents / Nb.Passes"

6.04 *BROCHE CONCAVE :
Travail de "Brise-Copeaux" : ajout d'un accostage lent de Y 1.5 mm 

6.04 *UTILITAIRE POUR TANGENTER LA FACE DE COUPE :
L'arroage a été ajouté
On comptait une passe de trop
On voit toutes les valeurs d'offset dans le sous-écran
Les signes de l'offset de départ ont été vérifiés = dans le même sens que le paramètre qui sera corrigé.

6.04 *BROCHE A RAYON : 
Lorsque le fichier était ouvert avec une version 6.15 ou supérieur, le rayon était décalé de 1 mm environ.
{P7_InvCycl} {TOUJOURS COCHÉ mais JAMAIS affiché !} a été forcé dans InitVar_Par_Travail

6.04 *eSIM :
Le menu "voir le parcourt outil" est disponible pour tous les utilisateurs.

======
6.04 *BROCHE RONDE, montage en OPPO-GEN : 
Mise au point des travaux suivants : 
- COUPE
- DEPOUILLE (Ext.Meu)
- DEPOUILLE (Bandeau)



----
Revision: 903
Author: LeGuen
Date: mercredi 13 février 2019 11:57:57
Message:
6.04
*Ecrans
-Fixed : La taille minimum qui peut être écrite dans le fichier de config pour l'écran principal est de 200x200
----
Revision: 901
Author: LeGuen
Date: mardi 12 février 2019 15:51:06
Message:
6.04
*Magasin de meules
-Improved : la mise à jour du magasin de meule ne fonctionne pas très bien. L'idéal serait de se brancher sur l'évenement CN lorsque la variable Meule_En_Broche change. Pour le moment, j'ai ajouté un bouton de mise à jour à coté du slider ON/OFF pour forcer la mise à jour
----
Revision: 897
Author: LeGuen
Date: vendredi 8 février 2019 10:31:28
Message:
6.04
*Plaquettes
-Fixed : Client A2C, Dépouille de forme : on peut maintenant choisir Y en axe de prise de passe. C'est la valeur par défaut. Attention pour les outils existant : il faut changer manuellement Z vers Y
----
Revision: 893
Author: LeGuen
Date: mercredi 30 janvier 2019 12:31:52
Message:
6.04
*Fraise 3T
-Fixed bug #78 : l'usinage de profil sur le 2e groupe de dents bouffait la fraise. Dans Deprof_Lire_H_Start_H_End on limite les points édités dans AxeProg à une borne mini/maxi pour rester dans la longueur utile. J'ai supprimé ce code dans le cas des nouvelles méthodes.
----
Revision: 889
Author: LeGuen
Date: mardi 29 janvier 2019 12:22:38
Message:
*Edition ISO
-Fixed #77: Sécurisation du diamètre meule remonté suite à bug #77. Attention : j'ai corrigé l'effet mais pas la cause...
----
Revision: 888
Author: LeGuen
Date: mardi 29 janvier 2019 12:16:43
Message:
*Edition ISO
-Fixed #77: Sécurisation du diamètre meule remonté suite à bug #77. Attention : j'ai corrigé l'effet mais pas la cause...
----
Revision: 887
Author: LeGuen
Date: vendredi 25 janvier 2019 15:55:22
Message:
6.04
*Transitique CA5
-Improved : mise à jour des %2001 et %2002 suite à déplacement chez SEFOC CA5 116
----
Revision: 885
Author: LeGuen
Date: mardi 22 janvier 2019 13:38:50
Message:
*6.04
*Edition ISO : n'édite pas certaines lignes
Github #76
Non testé : à valider
----
Revision: 884
Author: LeGuen
Date: mardi 22 janvier 2019 09:14:38
Message:
6.04
*Robot
-New : Lorsque le robot change les meules, on peut désormais vérifier si les meules utilisées peuvent toutes être mises dans le magasin interne. Si c'est le cas, on édite un cycle pour amener les trains de meule à l'intérieur.
non testé!

----
Revision: 883
Author: Possylkine
Date: jeudi 10 janvier 2019 15:37:01
Message:
eSim :
New : Ajout de la possibilité de charger un code ISO (Issue #74)
En test chez maxime
----
Revision: 880
Author: Ferrari
Date: vendredi 21 décembre 2018 11:26:43
Message:
6.04
*BROCHE PLATE, Travail "DOS Dent" & "FOND dent" :
-Fixed : en fonction de la valeur du paramètre "Angle Calage face 1", si la face de coupe positionne le plateau vers +180°, le fond de dent peut se retrouver vers +180° (OK) ou vers -180° (pas OK).
Client : ZID Galika
----
Revision: 879
Author: Ferrari
Date: jeudi 20 décembre 2018 16:36:44
Message:
6.04
*BROCHE RONDE, Travail "COUPE" :
-Fixed : quand on met une valeur non nulle, et plus petite que 0.25 dans le paramètre "COUPE : Dégagement", le dégagement en fin de travail dégage en Z- et collisionne dans la broche.
Client : CRENCENTE
----
Revision: 877
Author: LeGuen
Date: jeudi 20 décembre 2018 13:42:25
Message:
6.04
*Fraise : bug #64
-Fixed : de facon aléatoire, chez Raffin, la méthode du travail passe de G à D et la meule collisionne 
J'ai mis un message bloquant lorsque deux travaux de dépouille en périphérie ont des méthodes qui divergent. 
Dans la version 5.14 de Raffin, je vais en plus supprimer la méthode D des dépouilles en périphérie.
----
Revision: 876
Author: Possylkine
Date: mardi 18 décembre 2018 11:08:21
Message:
6.04 Simulation3D :
Fix : #59 Crash bascule rapide/precis
----
Revision: 875
Author: Possylkine
Date: mardi 18 décembre 2018 10:44:45
Message:
6.04 Simulation3D : Retour en arrière pour la version MW du 04/2018 (toujours version eSim 1.41)
PS : J'ai recompilé la 1.41 avec la 04 de MW
----
Revision: 874
Author: LeGuen
Date: lundi 17 décembre 2018 11:36:54
Message:
*6.04
*Redressage de meule
-New : début d'un code pour permettre le redressage sur une meule placée en dehors du générateur (sur une table par exemple). Le besoin s'est avéré nul en cours de développement, donc j'ai tout mis en commentaire. 
----
Revision: 873
Author: LeGuen
Date: vendredi 14 décembre 2018 16:12:05
Message:
*6.04
*Redressage de meule
-New : début d'un code pour permettre le redressage sur une meule placée en dehors du générateur (sur une table par exemple). Le besoin s'est avéré nul en cours de développement, donc j'ai tout mis en commentaire. 
----
Revision: 872
Author: Ferrari
Date: jeudi 13 décembre 2018 17:05:16
Message:
6.04
*BROCHES A CANNELURE HELICOIDALE : Ajout du dépincement + option Inverser B

*OUTIL PIGNON : 
-Fixed : on ne pouvait pas éditer plus de 9 travaux (TCaled redimensionné)
-Improved : création des 2 travaux "Brossage Face" et "Brossage Ext". On a ajouté le palpage du calage sur les outils droits
création d'un travail unique "Face de coupe" qui permet de choisir soit l'usinage avec le diamètre (péri.Cyl.), soit avec la face (avant.Boisseau), et d'empiler les travaux en ébauche / finition
Divers améliorations dans la présentation des paramètres
----
Revision: 871
Author: Possylkine
Date: jeudi 13 décembre 2018 14:44:20
Message:
6.04 Simulation3D:
New : Possibilité d'afficher un plan de coupe horizontal en plus du plan transversal d'avant.
Issue #66
----
