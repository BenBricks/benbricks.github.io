<!DOCTYPE html> <!--déclaration du type de document-->

<!--html : hypertext markup language-->
<!--css : cascading style sheet>

<html lang="francais"> <!--tag : balise ou etiquette html-->
    <head> <!--balise pour les meta-informations : nom de l'onglet, paramètres de la page etc ...-->
        <title> test_html </title>
        <meta charset="UTF-8">
    </head>

    <body> <!--balise pour le corp de la page-->
        <img src="images/logo_benbricks.png" alt="image du logo logo benbricks"  width = "500px">
        <!--alt = alternative text : texte affiché si l'image ne chage pas-->

        <h1>Ceci est un grand titre</h1> <!--heading ou titre-->
        <h2>Ceci est un petit titre</h2>

        <p style="font-family:calibri;">ceci est un long paragraphe argumenté <br> avec un retour à la ligne</p> <!--paragraphe-->

        <a href="https://www.eurobricks.com/forum/">ceci est un hyperlien vers le forum eurobricks</a><br>
        <!--href est un attribut de balise-->
        
        <br><!--ce tag est un élement vide-->

        <button style="background-color:red;">appuyer sur le boutton</button>
        <!--la propriété css background-color défini l'arrière plan d'un élement HTML-->

        <br/>

        <ul title="titre de liste"> <!--unorderd list-->
            <li> premier élément </li>
            <li> deuxième élément </li>
            <li> troisième élément </li>
        </ul>

        <hr/>

        <ol> <!--orderd list-->
            <li> premier élément </li>
            <li> deuxième élément </li>
            <li> troisième élément </li>
        </ol>

        <p style="color:rgb(180, 5, 5); font-size:30px;" title="titre de paragrahe"> ceci est un paragraphe en couleur </p>
        <p id="paragraphe 01"> ceci est un paragraphe muni d'un identifiant </p>

        <p style="font-size:30px; color:blue;"> ceci est un paragrahe avec une taille défini dans un style</p>
        <!--les valeurs possibles de l'attribut style sont des paramètres css-->

        <pre style="background-color:antiquewhite;"> <!--preformated text-->
                Un texte écrit
            avec les balises "pre"
            n'a pas besoin de balises "br"
        </pre>

        <p style="text-align:center;">  <!--permet de la position horizontal du texte-->
            un paragraphe centré
        </p>

        <b> texte en gras </b>
        <br/>
        <strong> texte fort </strong>
        <!--l'effet gras est identique dans le navigateur-->
        <br/>

        <i> texte en italique </i>
        <br/>        
        <em> texte mis en exergue </em>
        <!--l'effet italique est identique dans le navigateur-->
        <br/>

        <small> petit texte </small>
        <br/>

        <mark> texte surligné</mark>
        <!--comment changer la couleur du surlignage ?-->
        <br/>

        <del> texte barré </del>
        <br/>

        <p> un paragraphe avec <p> du texte </p> inséré par les balises "p" </p>
        <!--un paragraphe laisse des espaces blancs autour de lui : "br" n'est pas utile-->

        <p> un paragraphe avec <ins>du texte</ins> inséré par les balises "ins"</p>

        <p>texte avec<sub>du texte</sub>en dessous</p>

        <p>texte avec<sup>du texte</sup>en dessus</p>

        <q>ceci est une citation d'une source sûr</q> 

        <blockquote cite="https://www.eurobricks.com/forum/">
            ceci est une autre citation d'une autre 
            source sûr
        </blockquote>

        <t><abbr>ONU</abbr> est une abbréviation</t>
        <br/>

        <adress>
            ce script est écrit par benoit sahli, habitant à villers sur there
        </adress>

        <p><cite>Harry Potter</cite> est un oeuvre de JK.Rowling</p>
    </body> 

    <h1 style="border:2px solid tomato; text-align:center">Lamborghini SIAN fkp37</h1>

    <h1 style="background-color:rgb(10, 117, 10, 0.5);">couleur de fond transparente</h1>
    <!--il existe 3 methode pour définir une couleur : rgb, hsl et hex-->

    <a href="https://www.hothbricks.com/" target=_blank> 
        <!--d'autre options existent pour target comme _self, _parent ou _top-->
        <img src="images/logo_hothbricks.png" alt="logo du site hothbricks">
    </a> <!--un hyperlien peut être positionné sur n'importe quel élément-->
    <br/>

    <a href="https://www.hothbricks.com/" target=_blank> 
        <button>bouton lien</button>
    </a>
    <!--le bouton lien ci-dessus fonctionne mais ce n'est pas la meilleur méthode : il faut utiliser javascript-->
    <br>
</html>