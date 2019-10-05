# Balises
- [Aide mémoire](https://htmlcheatsheet.com/), les balises de bases
- Structure de base, voir [ici](https://github.com/TahiriNadia/ElleCode-ACM/blob/master/exemple/struct.html)

## Quelques exemples
### Les paragraphes 
- \<p> \</p>

### Sauter une ligne
- \<br />

### Les titres : 
- \<h1> \</h1> :  signifie « titre très important ». En général, on s'en sert pour afficher le titre de la page au début de celle-ci.
- \<h2> \</h2> : signifie « titre important »
- \<h3> \</h3> : pareil, c'est un titre un peu moins important (on peut dire un « sous-titre » si vous voulez)
- \<h4> \</h4> : titre encore moins important
- \<h5> \</h5> : titre pas important
- \<h6> \</h6> : titre vraiment, mais alors là vraiment pas important du tout

### La mise en valeur
- \<em> \</em> : mettre en italique
- \<strong> \<\strong> : mettre en gras
- \<em> \<strong>\<\strong> \</em> : mettre en italique et en gras
- \<mark> \<\mark> : pour surligner texte
    
## Les listes
#### Liste non ordonnée
- \<ul> \</ul> : pour une liste d'éléments sans notion d'ordre <br>
        __Exemple__ : 
>            <ul>
>                <li>Fraises</li>
>                <li>Framboises</li>
>                <li>Cerises</li>
>            </ul>

Note :
- \<ul> \</ul>délimite toute la liste
- \<li> \</li>délimite un élément de la liste (une puce)
    
#### Liste ordonnée
- Remplacer \<ul> \</ul> par \<ol> \</ol> <br>
        __Exemple__ : 
>            <ol>
>                <li>Je me lève.</li>
>                <li>Je mange et je bois.</li>
>                <li>Je retourne me coucher.</li>
>            </ol>   
  
### Un lien vers un autre site ou sur le site
- \<a href="https://openclassrooms.com">OpenClassrooms\</a>

### Un lien vers une ancre
- Avant placer l'ancre, par exemple \<h2 id="mon_ancre">Titre\</h2>
- Puis, \<a href="#mon_ancre">Aller vers l'ancre\</a>
- Voir [__exemple__](https://github.com/TahiriNadia/ElleCode-ACM/blob/master/exemple/ancre.html)

## Images
Il existe un format adapté à chaque image <br>
Si on résume, voici quel format adopter en fonction de l'image que vous avez :
- Une photo : utilisez un __JPEG__.
- N'importe quel graphique avec peu de couleurs (moins de 256) : utilisez un __PNG 8 bits__ ou éventuellement un GIF.
- N'importe quel graphique avec beaucoup de couleurs : utilisez un __PNG 24 bits__.
- Une image animée : utilisez un __GIF__ animé.

Note :
- \<img src="..." alt="..." />
- \<figure> et \<figcaption>


>            <figure> 
>                <img src="images/blocnotes.png" alt="Bloc-Notes" /> 
>                <figcaption>Le logiciel Bloc-Notes\</figcaption> 
>            </figure> 

__Exercice du CV__ : voir [ici](https://github.com/TahiriNadia/ElleCode-ACM/tree/master/exemple/exercice)

## Mise en forme du texte
- Mettre le texte par exemple en rouge <br>
\<p style="color:#FF0000";>Red paragraph text\</p>
- Aligner, centrer le texte <br>
\<center> Ce texte sera mis au centre.<br>
\<p>un paragraphe.\</p>\</center>

## Tables

>            <TABLE BORDER>
>                <TR><TD>ligne 1, colonne1</TD><TD>ligne1, colonne2</TD></TR>
>                <TR><TD>ligne 2, colonne1</TD><TD>ligne 2, colonne2</TD></TR>
>                <TR><TD>ligne 3, colonne1</TD><TD>ligne 3, colonne2</TD></TR>
>            </TABLE>


