# Approche de la modération sur Corneill.es

Comme la modération est un sujet de débat régulier sur le Fédivers, et que c'est une composante non négligeable dans le choix d'une instance, je me suis dit qu'il était peut-être temps de récapituler l'approche générale sur un document.

### Une approche évolutive

Déjà je pense qu'il est important de préciser que les choses peuvent être amenées à évoluer, et que j'aimerais qu'à terme que Corneilles soit un projet plus collectif qui pourra éventuellement prendre d'autres décisions. Par ailleurs, il n'y pas de solutions parfaites, mais des choix, qui sont toujours discutables.

Pour finir, il y a un écart entre la solution idéale qu'on pourrait vouloir appliquer et la solution concrète qu'on peut mettre en place avec les solutions techniques existant à un instant T.

### Le cap : un équilibre entre ouverture et protection

L'idée globale c'est que, sur le spectre de la modération sur le Fédivers, Corneill.es se situe à mi-chemin entre des instances qui veulent être très larges (comme Mastodon.social) et ne modèrent que dans les cas les plus extrêmes, et des instances qui se veulent plutôt être un *safe space*.

Pour le contenu hébergé sur Corneill.es (donc les posts de ses utilisateur·ices), cela se traduit concètement par une **intransigeance vis à vis de tout contenu potentiellement nocif** en estimant que tout contenu publié sur cette instance engage, si ce n'est légalement, au moins moralement, la responsabilité de celleux qui l'héberge. En revanche, l'idée est (hors exceptions type nazis/trolls/...) de permettre aux personnes qui n'auraient plus leur place sur Corneill.es de pouvoir migrer sur une autre instance.

Pour la fédération vis à vis d'autres instances, et la suspension de comptes distants, le principe global est de trouver un équilibre pour essayer de permettre aux membres de Corneill.es de ne pas être (trop) confronté·e·s à du contenu nocif, tout en évitant au maximum de couper des liens sans qu'un·e utilisateur·ice de Corneill.es ne puisse rien y faire.

### Ce que ça implique concrètement au niveau suspension d'instances

**Idéalement**, pour un ensemble d'instances qui peuvent avoir une modération défectueuse mais héberger aussi des comptes intéressants, ou pour certains comptes, la solution appliquée par Corneill.es serait de ne pas appliquer un blocage complet, mais à minima de prévenir les personnes lorsqu'elles accèdent à certains contenus, ou appliquer un blocage par défaut que chaque utilisateur·ice pourrait choisir de court-circuiter si cela est nécessaire.

Ce n'est malheureusement pas possible techniquement actuellement : la seule solution intermédiaire est la silenciation d'instance, qui en pratique ne permet pas forcément d'être prévenu·e qu'un contenu est potentiellement *à risque*.

**En pratique**, dans ces cas-là, Corneill.es pratique la **silenciation** (limit), même si ce n'est pas entièrement satisfaisant, mais est actuellement la seule solution pour éviter de couper entièrement toute connexion.

En complément, il est possible pour chaque utilisat·eur·ice de bloquer des comptes, mais également des instances dans leur ensemble. Il est également possible d'importer une blocklist de comptes ou d'instances à bloquer. En attendant mieux, je réféchis à comment proposer un moyen simple de bloquer tous ces comptes ou instances uniquement *silenciée*. 

Toute cette approche est évidemment amenée à évoluer, et n'hésitez donc pas à donner votre avis, surtout si vous êtes membre de Corneill.es !
