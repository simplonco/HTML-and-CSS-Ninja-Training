# HTML and CSS Ninja Training

**Prerequisites HTML**
------------------

* Understand [CSS selectors](http://discourse.simplon.co/t/selecteurs-css/32/1)

* Understand width height padding border margin


**Course**
---------

<http://fr.learnlayout.com/>

Page 1 to 6: mostly, it’s better that the width and height integrate padding and border. This section tells you how to do that. 

Pages 7 to 13: explanations of the positioning of elements. 

Page 14: explanation on how to make a responsive website. Skip this page for the moment.

Page 16: description of `display: inline-block` to horizontally align elements that usually line up vertically. 

Page 17: Skip this page for the moment. 

After all this, you understand the essentials of CSS and can confidently move on!  

**Attributs utilisés**
----------------------

```css
    \* pour définir à la main la largeur des éléments *\
    display: inline-block;
    
    \* indispensable avec inline-block *\
    vertical-align: top;
    box-sizing: border-box; \* cf. cours pour comprendre *\
    width: 100%;
    min-height: 100px;
    border: 1px #000 solid;
    margin: 0; \* marge externe *\
    padding: 0; \* marge interne *\
```
------------------------------------------------------------

EXERCICE 1 - HTML
-----------------

**Test 1 :**

Créer deux paragraphes d'une hauteur de 300 pixels et d'une largeur de
700 pixels. Y inclure un texte très long et gérer son débordement afin
qu'il soit entièrement lisible.

**Test 2 :**

Créer cinq titres de niveau 2 et les afficher sous forme de liste (voir
la propriété `display`).

**Test 3 :**

Dans un élément `<div>`, inclure un élément `<span>` contenant
du texte et lui donner le style bloc.

**Test 4 :**

Créer un menu vertical dont les éléments sont des liens `<a>`.

**Test 5 :**

Créer une image contenant un paragraphe incluant du texte et deux
éléments `<img />` qui se suivent. Faire flotter les images, la
première à gauche et la seconde à droite.

**Test 6 :**

Placer trois images de tailles initiales différentes dans une page.
Écrire les styles pour qu’elles s’affichent avec la même taille.
Ensuite, positionner afin d’obtenir un effet de cascade avec un décalage
horizontal et vertical constant pour chaque image par rapport à la
précédente. L’utilisateur doit pouvoir mettre chacune d’elles au premier
plan en cliquant dessus (voir la propriété `z-index`).

**Test 7 :**

Créer une mise en page à trois colonnes de largeurs respectives 20%, 65%
et 15%. La première et la troisième doivent contenir respectivement un
menu et une liste de liens crées à partir d'images. La colonne centrale
doit posséder un contenu éditorial.

**Test 8 :**

Créer une mise en page selon le modèle de la figure ci-dessous:

![](media/image01.png)

[exohtml.png](http://discourse.simplon.co/uploads/default/original/1X/56fb84ccace7ac3435101813835f602df2cd3425.png)[715x282
3.14
KB](http://discourse.simplon.co/uploads/default/original/1X/56fb84ccace7ac3435101813835f602df2cd3425.png)

[](http://discourse.simplon.co/uploads/default/original/1X/56fb84ccace7ac3435101813835f602df2cd3425.png)

La colonne de gauche (repère 1) a une largeur de 200 pixels et le
bandeau (repère 2) une hauteur de 150 pixels. Le bandeau contient le
titre du site, la colonne de gauche un menu de la zone principale
(repère 3) du texte et des images au choix. Le premier lien du menu doit
afficher une page ayant la même structure et le même contenu dans les
zones 1 et 2, mais un contenu éditorial différent dans la zone 3.

RESSOURCE HTML
--------------

<https://developer.mozilla.org/fr/docs/Web/HTML/Element>

EXERCICE 2 - CSS
----------------

<http://flukeout.github.io/>

EXERCICE 3 - GABARITS
---------------------

Réaliser progressivement cette page, idéalement sans regarder le CSS.

<http://chatchan.us/gabarits.html>

Les plus téméraires peuvent directement s'attaquer à la reproduction des
gabarits de ce site :

<http://www.alsacreations.com/static/gabarits/liste.html>

Attention, il ne s'agit pas de reproduire l'icone mais bien toute la
page du gabarit !
