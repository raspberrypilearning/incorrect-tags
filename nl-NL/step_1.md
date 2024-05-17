Controleer zorgvuldig de spelling van je HTML tags, attributen en classes.

Onjuiste tags kunnen ertoe leiden dat de tagtekst op je webpagina wordt weergegeven in plaats van dat je de lay-out bepaalt.

In dit voorbeeld wordt ten onrechte 'image' gebruikt in plaats van 'img'! `<img>` is de juiste HTML-tag.

## --- code ---

language: HTML
filename: index.html
line_numbers: false
--------------------------------------------------------

```
<image class="bordered-box" src="happy.png" alt="An outline of an anime style girl with a happy facial expression."/>
```

\--- /code ---

Het is ook onjuist om spaties in tags te gebruiken, dus het onderstaande voorbeeld is onjuist.

## --- code ---

language: HTML
filename: index.html
line_numbers: false
--------------------------------------------------------

< h1>Lorem ipsum</h1>

\--- /code ---
