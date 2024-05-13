Vérifie bien l'orthographe de tes balises, attributs et classes HTML.

Des balises incorrectes peuvent signifier que le texte de la balise s'affiche sur ta page web au lieu de contrôler la mise en page.

Cet exemple utilise incorrectement 'image' au lieu de 'img' ! `<img>` est la balise HTML correcte.

## --- code ---

language: HTML
filename: index.html
line_numbers: false
--------------------------------------------------------

```
<image class="bordered-box" src="happy.png" alt="An outline of an anime style girl with a happy facial expression."/>
```

\--- /code ---

Il est également incorrect d'avoir des espaces dans les balises, l'exemple ci-dessous est donc incorrect.

## --- code ---

language: HTML
filename: index.html
line_numbers: false
--------------------------------------------------------

< h1>Lorem ipsum</h1>

\--- /code ---
