# Projet Portfolio

## Cours de Design Web

Je suis élève à la HEPL de Seraing en création de pages web. Nous avons comme projet de faire un portfolio d'après les consignes suivantes : 

https://github.com/hepl-dw/projet-portfolio.git

# Stratégie

###Page de chargement
- Lorsqu’on arrive sur le site, on tombe sur une page de chargement animée (un logo qui change d’opacité). La page est blanche et le logo noir.
- Une fois le chargement complet, la page prend la couleur du background du site (un bleu foncé) et le logo devient blanc. 
- Une fois sur la page d’accueil, le logo se déplace vers le haut à gauche de la page et y reste (non-sticky).

###Page d’accueil
- La page d’accueil contient un logo, une navigation, deux textes, une illustration et une ou deux icônes.
- Le logo est en haut à gauche du site, il reste là.
- La navigation comprend les différentes sections à savoir : Accueil, Sur moi, Tableau des compétences/Logiciels/Projets et Contact. Le texte est à une opacité faible quand on n’est pas dessus avec le curseur, une animation se fait dessus avec les bordures inférieures et supérieures et l’opacité augmente. La section courante a les bordures inférieures et supérieures affichées et n’a pas d’opacité. Quand on passe le curseur sur une section qui n’est pas la courante, le texte de la section courante a l’animation inverse pour laisser le focus sur là où le curseur est. La navigation est située au milieu de la page (horizontalement) et vers le haut.
- Un texte sert de phrase d’accroche pour m’annoncer tandis que l’autre est une petite description du site et de ce que l’on y trouvera. Les deux textes ont des styles différents.
- L’illustration est un dessin vectoriel me représentant avec des formes simples remplies de couleurs.
- Les icônes sont des sortes de flèches (ou dans le même style) pour indiquer que la suite du site se trouve sur la droite (scroll horizontal). Les icônes subissent une rotation de 180° pour aller se placer dans la section suivante et dans l’autre sens pour le retour en arrière. (Ou alors elles disparaissent pour laisser que celles qui indiquent la suite du site et quand on arrive à la fin, à ce moment-là, elles subissent la rotation).

###Sur moi
- La section « Sur moi » contient la navigation, une zone de texte, une zone d’illustration, une ou deux icônes et un background.
- La navigation a le même style que sur la page d’accueil.
- La zone de texte est scrollable est les bords inférieurs et supérieurs sont en dégradé d’opacité pour indiquer qu’il y a une suite et un retour. (Peut-être que le scroll de la souris peut scroller le texte avant de passer sur l’autre section).
- La zone d’illustration contient de petites illustrations vectorielles qui changeront en fonction du scroll de la zone de texte. Pour changer d’illustrations, un fade-in fade-out est appliqué.
- Les icônes ont le même style que sur la page d’accueil.
- Le background est une illustration légère pour représenter une texture, rajouter un petit quelque chose. SI on n’est pas sur la section, le background ne fait pas la taille de la section, quand on arrive à la section le background est animé pour faire la taille de la section.

###Tableau des compétences/Logiciels/Projets
- Cette page contient une navigation, des cadres et une ou deux icônes.
- La navigation a le même style que sur la page d’accueil.
- Les cadres contiennent les différents codes et applications maîtrisées. Si le cadre est derrière un autre il est animé pour passer devant. Tous les cadres lorsqu'on les survole sont animés au niveau de l’opacité (ceux qui ne sont pas survolés ont moins d'opacité et sont plus petits) et le survolé est plus grand. On retrouve dans les cadres de code les applications utilisées ainsi qu’une petite phrase exprimant mon avis dessus. Dans les cadres Photoshop et Illustrator on retrouve aussi une phrase et peut-être un projet réalisé.

###Contact
- La page de contact contient une navigation, un formulaire de contact, une illustration et un background. (Peut-être un rappel du logo aussi).
- La navigation a le même style que sur la page d’accueil.
- Le formulaire de contact sert à m’envoyer un mail avec une question/offre/message. Il contient un champ obligatoire pour : Nom et Prénom, adresse mail, le message. Il y a aussi un champ optionnel pour la compagnie/agence/entreprise dont fait partie l’utilisateur. Il y a à la fin du champ un bouton pour envoyer stylisé.
- Le background a le même style que dans la section « sur moi ».