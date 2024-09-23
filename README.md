# Cycle Éco-Planétaire


## Par Keven Malric

### Idée derrière l'oeuvre
Le principe de l'oeuvre: **Cycle Éco-Planétaire** est de critiquer un manque de sens de la routine industrielle/humaine. Par l'immersion, de la réalité augmentée, **Cycle Éco-Planétaire** plonge ses participant dans un univers desertique ou il n'y a aucune végétation et ou le seul moyen d'avancer est de creusé vainment les sables pour des richesses temporaires. L'oeuvre en réalité virtuelle cherche à choquer par manque de progrès du point de vue de l'histoire afin de démontré la futilité des actions commises par l'avarice et l'envie humaine qui détruit notre environnement.

### Expérience recherchée

l'utilisateurs entre dans la pièce ou un musique désolante joue. il des entouré d'écran qui joue en boucle le paysage d'un désert. La victime met le casque VR et prend les manette. lorsqu'elle joue elle vit des sensation de non-sens et de désespoir.
Une fois que l'expérience est terminé, l'utilisateur est (*idéalement*) pris du sentiment d'insignifiance et réfléchit à ses actions écologiques.

### Les patentes qu'on a utilisés
systhème suround sound logithèque Z906 5.1 Speaker System. 4 projecteur lazer 4k Dangbei DBOX02 (Mars Pro 2), Meta Quest 3.


```mermaid
graph TD;
    personnage[le joueur apparait dans le désert]-->apprenti?;
    apprenti?[après un temps, le joueur rencontre un veillard qui lui propose de lui apprendre à utliliser une pelle pour creuser et trouver des objets de valeur]-->oui;
    apprenti?[après un temps, le joueur rencontre un veillard qui lui propose de lui apprendre à utliliser une pelle pour creuser et trouver des objets de valeur]-->non;
    oui-->creuse[le joueur peut creuser et ammaser des gains];
    non-->décès[le joueur meurt de faim];
    décès-->personnage
    creuse-->visiteur[Une belle journée, le joueur se fait visiter par un étranger qui lui demande de l'écouter.];
    visiteur-->parle?[tu accepte de l'écouter?];
    parle?-->salut[tu lui dit bonjours et tu l'écoute. Il t'apprend la position d'un trésort de valeur inestimable.];
    parle?-->non2[Tu l'envoi se promener et tu continue de travailler.];
    salut-->trésort[tu suit les indications qui te mènent à une boîte enterré.];
    trésort-->argent[La boîte contient 999 999 999$ faque t'est riche, alors tu donne ton 2 semaine.];
    argent-->village[tu te rend en ville pour la première fois];
    village-->fête[Tu fête.];
    fête-->dors[t'est fatigué après la fête alors tu dors pendant 4 jours.];
    dors-->creuse3[À ton réveil tu te rend pour la dernière fois à ton site de travail et tu creuse.];
    creuse3-->serpent[quand tu creuse, tu trouve un serpent!!!!];
    serpent-->mord[Il te mord!];
    mord-->meurt[Il était venimeux, donc tu meurt!!!];
    meurt-->personnage;
    non2-->continue[Ton travail se poursuit pendat plusieurs années];
    continue-->enfant[quelques années plus tard tu croise un enfant et tu est frappé par une nostalgie lointaine];
    enfant-->tutel[tu propose à l'enfant de lui apprendre à creuser à la pelle et l'enfant accepte.];
    tutel-->vieux[tu viellit et l'enfant grandit...];
    vieux-->choix[une fois vieux  le personnage arrêt et le joueur doit faire un choix entre le vieux et le jeune.]
    choix-->vieillard;
    choix-->jeune;
    vieillard-->mort[le joueur continue avec son vieux personnage. Le vieux personnage fini par mourrir.];
    mort-->personnage;
    jeune-->personnage2[Le joueur prend le personnage numéro 2];
    personnage2-->loop[boucle infini de la vie]-->creuse;
    

```


