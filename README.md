# Titre du jeu

Projet conçu en équipe avec : [Vencia Bozieux]

## Le public cible

- Type de joueur visé (fonceur ou explorateur) : explorateur (tu dois explorer le monde pour trouver les joueurs et les tuer)
- Catégorie et genre : Action, tir et combat
- Le concept en une phrase (un personnage, un objectif, un obstacle) :
  Objectif: C'est la fin du monde et il reste x de personnes sur Terre. Les joueurs doivent s'entretuer pour qu'il y aille un dernier survivant qui renouvelle le monde.
  Obstacle: trouver des objets pour traquer les joueurs et s'affronter contre eux selon leur niveau de difficulté.
  Personnage: Le personnage principale est mysterieux, on ne sait pas à quoi il ressemble sous ses habits. One ne sais pas si il est vraiment humain. Il n'a pas de noms et possède des habilités spéciales. 

## Les mécaniques

- Objectif du jeu : tuer les joueurs, renouveler la Terre
- Condition de victoire : que tous tes ennemis soient morts.
- Condition de défaite : il faut qu'on te tue.
- Mécanique cœur :
  Le joueur utilise une carte pour choisir le prochain niveau. Les niveaux sont linéaires et à la fin ont y trouve un indice vers un autre boss. Le repère de l'Étranger sert d'intermédiaire entre les niveaux. On peut y améliorer ses armes et son équipement et intéragir avec le faucon et d'autres personnages. L'Étranger utilise des armes à feu comme armes principales. Les envirronements utilisent un style platformer pour les combats. les ennemis sont divisés en classe et chaque boss est différent. Après avoir tuer des boss ou des mini boss, le joueur peut développer des habilités spéciales. La difficulté augmente au fur et à mesure
- Mécanique secondaire : dossiers et texts cachés à travers les niveaux qui raconte l'histoire de l'Apocalypse. Skins (armes et appenrences) légendaires à trouvé. Objets de collection pour personnaliser le repère
- Structure (progressif ou émergent, expliquez en quelques mots) : progressif. Au fur et à mesure qu'on avance dans le jeu, le joueur déverouille de nouvelles abilités
- Prototype Scratch (facultatif) : [lien du projet](lien)

## Les phases de jeu

- La boucle de jeu (action → rétroaction → récompense) : choisi un niveau -> exploration -> combat -> amélioration
- Phase 1 : choix de niveau. Le joueur clique sur la carte pour l'afficher. Seul le curseur peut être bougé. Lorsqu'on le positionne au niveau d'un endroit, une court description apparait. Le joueur doit confirmer son choix pour y avoir accès.
    - Transition vers la phase 2 : fade-out
- Phase 2 : exploration. le joueur se retrouve dans un environnement linéaire où il peut seulement aller de droite à gauche. Il peut sauter et grimper sur des bâtiments et platformes. Il y a quelques ennemis ici et là. Le joueur doit s'aligner avec eux pour leur tirer dessus. Il est aussi possible pour le joueur d'aller dans d'autres zones en cliquant sur des passages et des portes ouvertes.
    - Transition vers la phase suivante: musique qui change
- Phase 3 : combat. Le joueur se retrouve dans un endroit ou on ne peut pas aller trop loin ni reculer. Il n'y a aussi plus aucun passage pour s'échapper. Il est encore possible de faire du parkour et les mécaniques de tirs sont les mêmes. les ennemis sont plus difficiles à battre que ceux dans les phases d'exploration. Les ennemis dropent des munitions et des trousses de soin une fois bâtus
    - Transition vers la phase suivante: musique redevient normal, le sang qui a giclé partout disparaît
- Phase 4 : retour au bercail. Lorsqu'un niveau normal est terminé, il y a une petite cinématique suivi par un fade-out. Après, on est de retour à notre base. Là, on peut améliorer notre équipement, lire les documents qu'on a trouvé et reskinner notre personnage et nos armes
    - Transition vers la phase 1: on clique sur la carte qui s'affiche par la suite
- Phase 5 : mini-boss fight: avant d'arriver au boss finale, on doit battre un mini boss. On sait qu'on s'apprête à se battre contre un mini boss lorsque la caméra bouge vers lui lorsqu'on entre dans une zone, le boss nous attend aussi. Les mini boss sont plus dûr à battre que des ennemis régulier. Leurs arènes sont plus petite. Les tuer nous donne de l'EXP et un indice sur l'emplacement du boss
    - Transition vers la phase suivante: récompenses
- Phase 6 : boss fight: lorsqu'on arrive au boss final, il y a une cinématique où ce dernier parle à l'Étranger. Les boss sont difficiles à battre car ils sont dans un endroit clos et ont plusieurs habilités avancé. Lorsqu'on bat un boss, on obtient beaucoup de points pour améliorer notre équipement, de l'EXP et de nouvelles armes et armures
    - Transition vers la phase suivante: cinématique

## Le fun et le flow

- La source du fun pour le type de joueur visé (sans utiliser le mot *fun*) : découvrir tous les secrets et bonus cachés, combattre des ennemis cachés, dévérouiller des compétences et de l'équipement, progresser dans l'histoire
- Le flow (équilibre défi / capacités) : plus le joueur devient bon, plus les ennemis et les boss sont difficiles à battre et plus il obtient de récompenses pour s'améliorer
- La rétroaction (son, lumière, animation) : Lorsque le joueur gagne un combat normal, la musique redevient calme et les cadavres disparaissent. Lorsqu'il gagne un mini boss fight, le mini boss s'écroule à terre et le joueur peut le looter. Lorsque le joueur gagne un boss fight, il y a une cinématique de l'Étranger en train d'achever le boss. Lorsque l'on fini le niveau, il y une petite cinématique, Lorsque le joueur perd au combat, une image sur fond noir du masque de l'Étranger à terrer apparait à l'écran avec les mots "Game Over". Lorsque l'on meurt lors d'un mini boss fight, il y a une animation de l'Étranger en train de de se faire massacrer. Lorsqu'on meurt lors d'un boss fight, il y a une cinématique que l'Étranger se fesant achevé
- La rejouabilité (pourquoi recommencer) : Découvrire tous les secrets manqués, jouer l'Étranger sous un autre angle

## L'histoire

- Le personnage principal (description, désir, besoin, habiletés spéciales) : ...
- Le début (phase de jeu ou transition associée) : ...
- Le milieu (phase de jeu ou transition associée) : ...
- Le revirement (phase de jeu ou transition associée) : ...
- La fin (phase de jeu ou transition associée) : ...
- L'univers (où, quand, un élément de folklore) : ...
- Comment la mécanique cœur exprime le désir du personnage : ...

## L'esthétique et l'interface

- Le style visuel (et pourquoi il convient à votre jeu) : ...
- La palette de couleurs : ...
- Trois images de référence : [image 1](lien), [image 2](lien), [image 3](lien)
- L'ambiance sonore : ...
- Les objets jouables : ...
- Croquis de l'interface :

![Interface](interface.jpg)

## Les ressources

![Image de référence](ressource.jpg)

- Son d'ambiance : [titre du son](lien)
- Crédits :
    - « Titre de l'image », par ..., [Source](lien), [Licence](lien)
    - « Titre du son », par ..., [Source](lien), [Licence](lien)
