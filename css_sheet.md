# Flexbox vs. Gridgrid

## Flexbox 
```sh
body {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

footer {
  margin-top: auto;
}

/* Optional */
main {
  margin: 0 auto;
  /* or: align-self: center */
  max-width: 80ch;
}
```

## Grid
```sh
body {
  min-height: 100vh;
  display: grid;
  grid-template-rows: auto 1fr auto;
}

/* Optional */
main {
  margin: 0 auto;
  max-width: 80ch;
}
```

# Buttons
Damit Buttons nicht nur durch HTML Code als Barrierefrei eingestuft werden, sondern auch visuell als fokusiert betrachtet werden können, kann mithilfe von 
```sh
:focus{
  outline: max(1px, 0.1em) solid purple;
  outline-offset: 0.25em;
}
```
den Button hervorheben.

## Beispiel
<div style="display: flex">
     <button type="button" class="button_config as_link">As Link</button>
    <button type="button" class="button_config as_button">As Button</button>
    <button type="button" class="button_config keyboard">Only Focus on Keyboard</button>

<style>
.button_config {
  background-color: initial;
  border: initial;
  border-radius: initial;
  color: white;
  font-family: system-ui, sans-serif;
  font-size: 1.2rem;
  line-height: 1.5;
  margin: 0;
  max-height: none;
  padding: initial;
  text-decoration-color: initial;
  text-decoration-thickness: auto;
}

.as_link:focus {
  outline: max(1px, 0.1em) solid purple;
  outline-offset: 0.25em;
}

.as_button {
  background-color: purple;
  color: white;
  border-radius: 8px;
  margin: 1rem;
  padding: 1rem 2rem;
}
.as_button:focus {
  outline: max(1px, 0.1em) dashed currentColor;
  outline-offset: -0.25em;
}

.keyboard {
  background-color: purple;
  color: white;
  border-radius: 8px;
  margin: 1rem;
  padding: 1rem 2rem;
}
.keyboard:focus-visible {
  outline: max(1px, 0.1em) dashed currentColor;
  outline-offset: -0.25em;
}



</style>
</div>

## Weitere Tips
```sh
:focus
```
Durch die Verwendung von Pseudo-Klassen wie ":focus" kann die Sichtbarkeit von Links und Formularelementen verbessert werden, insbesondere für Menschen mit motorischen Behinderungen.

```sh
:hover
```
Durch die Verwendung von Pseudo-Klassen wie ":hover" können zusätzliche Informationen zu Links und anderen Elementen angezeigt werden, was Menschen mit kognitiven Behinderungen helfen kann, den Inhalt der Seite besser zu verstehen.

```sh
outline
```
Die Verwendung von Umrissen um Links und Formularelemente kann die Sichtbarkeit und Bedienbarkeit dieser Elemente verbessern, insbesondere für Menschen mit motorischen Behinderungen.
# Safe-Colors für Farbenblinde Menschen

Farbe | RGB | CMYK 
-------- | -------- | -------- |
Schwarz | (0,0,0) | (0,0,0,100)
Orange | (230,159,0) | (0,50,100,0)
Blau | (86,190,233) | (80,0,0,0)
Grün | (0,158,115) | (97,0,75,0)
Gelb | (240,228,66) | (10,5,90,0)
Dunkel-Blau | (0,114,178) | (100, 50, 0, 0)
Dunkel-Orange | (213,94,0) | (0,80,100,0)
Pink? | (204,121,167) | (10,70,0,0)
<span>Quelle: https://www.extensis.com/de-de/blog/so-gestalten-sie-designs-f%C3%BCr-farbenblinde</span>


# Tools
[Check My Colours aktuell offline](https://www.giovanniscala.com/checkmycolours/bye.html) 

[WebAim’s color contrast checker](https://webaim.org/resources/contrastchecker/)

[I Want To See Like The Color Blind](https://chrome.google.com/webstore/detail/lets-get-color-blind/bkdgdianpkfahpkmphgehigalpighjck)

[Color Oracle](https://colororacle.org/)