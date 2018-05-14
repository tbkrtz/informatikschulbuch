# Elemente in HTML

In diesem Abschnitt lernst du, wie du in HTML als Auszeichnungssprache einzelne Bereiche der Webseite auszeichnest:

Mithilfe von HTML kannst du etwa Text in verschiedene Teilbereiche (auch Elemente genannt) zerlegen, um diese dann individuell darzustellen.

Um einen Bereich von einen anderen Abzugrenzen, verwendest du sogenannte Tags: 

```html
<h1>Überschrift 1</h1>
```

In obigen Beispiel hast du eine Überschrift ausgezeichnet. Dabei markiert `<h1>` den Beginn der Überschrift und wird somit Starttag genannt. `</h1>` markiert das Ende des Tags und ist somit der Endtag.

Sicher ist dir aufgefallen, dass sich Start- und Endtag nur durch den `/` unterscheiden. Dadurch behälst du ganz leicht den Überblick.  Die spitzen Klammern `<>` mit allen was darin steht werden nicht im Browser zu sehen sein und dienen nur als Orientierung für den Browser.

t> [Aufgabe](https://apps.wi-wissen.de/html-css-js-editor/0JnZu)

Es gibt einzelne Fälle, da möchte man zwar ein durch Start- und Endtag markiertes Element aufschreiben, hat aber keinen Text der ausgeben werden soll. In diesem Fall könntest du folgendes schreiben:

```html
<br></br>
```

Das geht zwar, ist aber den Entwicklern zu lang. Daher gibt es hier eine Kurzschreibweise:

```html
<br />
```

t> [Aufgabe](https://apps.wi-wissen.de/html-css-js-editor/v3SU3)