# Cycle Éco-Planétaire

## Par Keven Malric

### Idée derrière l'oeuvre

Le principe de l'oeuvre: **Cycle Éco-Planétaire** est de critiquer un manque de sens de la routine industrielle/humaine. Par l'immersion, de la réalité augmentée, **Cycle Éco-Planétaire** plonge ses participants dans un univers désertique ou il n'y a aucune végétation et ou le seul moyen d'avancer est de creuser vainement les sables pour des richesses temporaires. L'oeuvre en réalité virtuelle cherche à choquer par manque de progrès du point de vue de l'histoire afin de démontrer la futilité des actions commises par l'avarice et l'envie humaine qui détruit notre environnement.

### Expérience recherchée

l'utilisateurs entre dans la pièce ou une musique désolante joue. Il est entouré d'écrans qui joue en boucle le paysage d'un désert. La victime met le casque VR et prend les manettes. Lorsqu'elle joue, elle vit des sensations de non-sens et de désespoir.
Une fois que l'expérience est terminée, l'utilisateur est (*idéalement*) pris du sentiment d'insignifiance et réfléchit à ses actions écologiques.

### scénarimage

```mermaid
graph TD; 
    personnage[le joueur apparait dans le désert, il est pauvre]-->apprenti?;
    apprenti?[le joueur rencontre un vieillard riche qui lui propose de lui apprendre son métier]-->oui;
    apprenti?[le joueur rencontre un vieillard riche qui lui propose de lui apprendre son métier]-->non;
    oui-->creuse[le joueur peut creuser et ammasser des gains];
    non-->décès[le joueur meurt de faim];
    décès-->personnage
    creuse-->adulte[le joueur devient adulte et très avide de richesses]-->visiteur[Une belle journée, le joueur se fait visiter par un étranger qui lui demande de l'écouter.];
    visiteur-->parle?[tu accepte de l'écouter?];
    parle?-->salut[tu lui dis bonjours et tu l'écoutes. Il t'apprend la position d'un trésor de valeur inestimable.];
    parle?-->non2[Tu l'envoie se promener et tu continue de travailler.];
    salut-->trésort[tu suis les indications qui te mènent à une boîte enterré.];
    trésort-->argent[La boîte contient 999 999 999$ faque tu est riche, alors tu donnes tes 2 semaines.];
    argent-->catastrophe[le trou que le joueur a creusé est si profond qu'il s'écroule et étouffe le personnage.];
    catastrophe-->meurt[Il n'a plus d'air, donc tu meurs!!!];
    meurt-->personnage;
    non2-->continue[Ton travail se poursuit pendant plusieurs années];
    continue-->enfant[quelques années plus tard, tu croise un enfant et tu es frappé par une nostalgie lointaine];
    enfant-->vieux[le joueur vieillit]
    vieux-->trou[le joueur, une fois vieux, à tellement creusé que le trou fait plus de dix kilomètres de rayon et huit kilomètres de profond.];
    trou-->mort[le joueur tombe dans le trou et meurt!]
    mort-->personnage;
```

### Ambiance
![moodboard](/img/Moodboard.png)

https://github.com/user-attachments/assets/1ee875f3-ed10-4cb8-8650-370bab4d0c9c

https://github.com/user-attachments/assets/10e00f20-fe9d-447b-b1cc-1e9c92df50e0


### Les technologies utilisées

systhème suround sound logithèque Z906 5.1 Speaker System. 4 projecteurs laser 4k Dangbei DBOX02 (Mars Pro 2), Meta Quest 3, Unity.

