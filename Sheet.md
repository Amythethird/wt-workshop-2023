# Tastaturbelegungen
Wenn wir von Tastaturbedienung reden, ist in der Barrierefreien-Webentwicklung davon die Rede, das alle Komponenten per Tastatur gesteuert werden können.

Tastenbefehl/Befehl | Funktion 
-------- | -------- | 
Tab-Taste| Die Tab-Taste ermöglicht es dem Benutzer, durch interaktive Elemente auf derSeite (z.B. Links, Formulare, Schaltflächen) zu navigieren. Der Fokus wird dabei in derRegel von oben links nach unten rechts bewegt.
Umschalt + Tab| Diese Tastenkombination ermöglicht es dem Benutzer, den Fokus inumgekehrter Reihenfolge zu bewegen, also von unten rechts nach oben links.
Pfeiltasten| Die Pfeiltasten können verwendet werden, um durch Menüs, Dropdown-Listen undandere Listen zu navigieren, wenn diese geöffnet sind.
Eingabetaste| Die Eingabetaste wird verwendet, um interaktive Elemente wie Links,Schaltflächen und Formularelemente auszuwählen oder zu aktivieren.
Leertaste| Die Leertaste wird in der Regel verwendet, um interaktive Elemente wieCheckboxen und Radiobuttons auszuwählen oder zu aktivieren.
Escape-Taste| Die Escape-Taste wird verwendet, um Modal-Dialoge und andere Popup-Fensterzu schließen.

<span>Quelle: https://www.barrierefreies-webdesign.de/knowhow/msaa/checkpunkte.html</span>

# Aria Attribute

Tastenbefehl/Befehl | Funktion 
-------- | -------- | 
aria-atomic | Legt fest, ob eine Änderung des Inhalts den Textbereich umfassen soll.
aria-busy | Legt fest, ob ein Element gerade beschäftigt ist oder arbeitet.
aria-controls | Weist ein Element einem anderen Element zu, das es steuert.
aria-describedby | Beschreibt das Element genauer.
aria-disabled | Legt fest, ob ein Element deaktiviert ist.
aria-dropeffect | Legt den Effekt fest, den das Ziel haben soll, wenn ein Objekt darauf gezogen wird.
aria-flowto | Weist ein Element einem anderen Element zu, das ihm folgt.
aria-grabbed | Legt fest, ob ein Element gerade gezogen oder bewegt wird.
aria-haspopup | Legt fest, ob ein Element ein Popup-Menü, Dialog oder ähnliches enthält.
aria-hidden | Legt fest, ob ein Element sichtbar ist oder nicht.
aria-invalid | Legt fest, ob ein Element einen ungültigen Wert enthält.
aria-label | Legt einen Text als Beschriftung für ein Element fest.
aria-labelledby | Weist einem Element eine Beschriftung zu.
aria-level | Gibt das Strukturniveau eines Elements an.
aria-live | Legt fest, ob Änderungen an einem Element sofort aktualisiert und angesagt werden sollen.
aria-multiline | Legt fest, ob ein Element mehrere Zeilen Text enthält.
aria-multiselectable | Legt fest, ob mehrere Elemente ausgewählt werden können.
aria-orientation | Legt die Ausrichtung eines Elements fest.
aria-owns | Weist einem Element ein anderes Element zu, das ihm gehört.
aria-posinset | Gibt die Position eines Elements innerhalb einer Gruppe an.
aria-pressed | Legt fest, ob ein Element als gedrückt oder ungedrückt dargestellt wird.
aria-readonly | Legt fest, ob ein Element schreibgeschützt ist oder nicht.
aria-relevant | Gibt an, welche Änderungen an einem Element als relevant betrachtet werden sollten.
aria-required | Legt fest, ob ein Element zwingend erforderlich ist.
aria-selected | Legt fest, ob ein Element ausgewählt ist oder nicht.
aria-setsize | Gibt die Anzahl der Elemente in einer Gruppe an.
aria-sort | Legt die Sortierreihenfolge eines Elements fest.
aria-valuemax | Legt den höchsten Wert für ein Element mit einem numerischen Wert fest.
aria-valuemin | Legt den niedrigsten Wert für ein Element mit einem numerischen Wert fest.
aria-valuenow | Gibt den aktuellen Wert für ein Element mit einem numerischen Wert an.
aria-valuetext | Gibt einen Textwert für ein Element mit einem numerischen Wert an.

# Aria Role
Tastenbefehl/Befehl | Funktion 
-------- | -------- | 
role="alert"| Gibt an, dass ein Element wichtige und zeitkritische Informationen enthält, die für den Benutzer sofortige Aufmerksamkeit erfordern.
role="button"| Gibt an, dass ein Element als Schaltfläche fungiert, die vom Benutzer aktiviert werden kann.
role="checkbox"| Gibt an, dass ein Element eine Checkbox ist, die vom Benutzer aktiviert oder deaktiviert werden kann.
role="combobox"| Gibt an, dass ein Element eine Kombinationsfeld ist, das dem Benutzer eine Liste von Optionen zur Auswahl bietet.
role="dialog"| Gibt an, dass ein Element ein Dialogfeld ist, das verwendet wird, um mit dem Benutzer zu interagieren und Informationen zu sammeln.
role="grid"| Gibt an, dass ein Element eine Tabelle oder Raster von Daten enthält, die für den Benutzer navigierbar sind.
role="link"| Gibt an, dass ein Element als Link fungiert, der den Benutzer zu einer anderen Seite oder einem anderen Bereich der aktuellen Seite führt.
role="listbox"| Gibt an, dass ein Element eine Liste von Elementen enthält, aus der der Benutzer eine oder mehrere Optionen auswählen kann.
role="menu"| Gibt an, dass ein Element eine Liste von Menüoptionen enthält, die vom Benutzer ausgewählt werden können.
role="progressbar"| Gibt an, dass ein Element den Fortschritt eines Vorgangs anzeigt.
role="radio"| Gibt an, dass ein Element ein Radiobutton ist, der vom Benutzer ausgewählt werden kann.
role="slider"| Gibt an, dass ein Element einen Schieberegler enthält, der vom Benutzer bewegt werden kann, um einen Wert auszuwählen.
role="spinbutton"| Gibt an, dass ein Element ein Spinner ist, der vom Benutzer verwendet werden kann, um einen numerischen Wert auszuwählen.
role="tab"| Gibt an, dass ein Element als Registerkarte fungiert, die vom Benutzer ausgewählt werden kann, um zwischen verschiedenen Inhalten zu wechseln.
role="textbox"| Gibt an, dass ein Element einen Textbereich enthält, in dem der Benutzer Text eingeben oder bearbeiten kann.
uvm|

<span>Quelle: https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles </span>

# Abstände und Text-Formattierung

* Abstand zwischen Text und Bildern: Mindestens 10 Pixel Abstand zwischen Text und Bildern, damit der Text klar und deutlich lesbar bleibt.
* Abstand zwischen Text und Rand: Ein Abstand von mindestens 20 Pixel zwischen Text und Rand des Textcontainers, damit der Text nicht zu eng am Rand sitzt und dadurch schwerer lesbar ist.
* Abstand zwischen Absätzen: Ein Abstand von mindestens einer Zeile zwischen den Absätzen, um den Text besser lesbar und visuell ansprechender zu machen.
* Abstand zwischen Überschriften und Text: Ein Abstand von mindestens einer halben Zeile zwischen den Überschriften und dem Text, um eine klare Abgrenzung und Hierarchie zu schaffen.

* `<h1>` Eine geeignete Schriftgröße für `<h1>` liegt zwischen 28 und 36 Pixeln.
* `<h2>` Eine geeignete Schriftgröße für `<h2>` liegt zwischen 24 und 30 Pixeln.
* `<h3>` Eine geeignete Schriftgröße für `<h3>` liegt zwischen 18 und 24 Pixeln.
* `<h4>` Eine geeignete Schriftgröße für `<h4>` liegt zwischen 16 und 20 Pixeln.
* `<h5>` Eine geeignete Schriftgröße für `<h5>` liegt zwischen 14 und 18 Pixeln.
* `<h6>` Eine geeignete Schriftgröße für `<h6>` liegt zwischen 12 und 16 Pixeln.

## Beispiel Text und ARIA
```sh
<h5>Fruit Trees</h5>
...
<h6>Apples</h6>
<p>Apples grow on trees in areas known as orchards...</p>
...
<div role="heading" aria-level="7">Jonagold/div>
<p>Jonagold is a cross between the Golden Delicious and Jonathan varieties...</p>
```
Der Beispiel Code erweitert die Headings um ein weiteres Level, da es standardmäßig nur 6 Level gibt.



# Videos und Bilder

* Verwende Untertitel: Stelle sicher, dass Untertitel für Videos verfügbar sind, um gehörlose oder schwerhörige Benutzer zu unterstützen. Die Untertitel sollten korrekt synchronisiert und in einer leicht lesbarenSchriftart und Größe angezeigt werden.

* Transkribiere Audioinhalte: Wenn du Audioinhalte verwendest, solltest du auch eine Transkription des Audios bereitstellen, um gehörlose Benutzer oder Benutzer, die Schwierigkeiten haben, das Gesprochene zuverstehen, zu unterstützen.

* Verwende Beschreibungen: Beschreibungen (auch bekannt als Audiodeskriptionen) sind für blinde oder sehbehinderte Benutzer wichtig, um das Video zu verstehen. Beschreibungen beschreiben visuelle Inhalte inWorten, so dass der Benutzer eine genaue Vorstellung davon hat, was im Video gezeigt wird.
* Verwende eine Bedienleiste: Stelle sicher, dass das Video eine Bedienleiste hat, mit der Benutzer das Video steuern können. Die Bedienleiste sollte für alle Benutzer zugänglich sein, auch für Benutzer, die keineMaus verwenden.

* Verwende einen geeigneten Mediaplayer: Verwende einen Mediaplayer, der für alle Benutzer zugänglich und barrierefrei ist. Der Mediaplayer sollte mit einer Tastatur bedient werden können und für Benutzer mitSehbehinderungen zugänglich sein.

* Verwende geeignete Formate: Verwende geeignete Audio- und Videoformate, die für alle Benutzer zugänglich sind und auf allen Geräten wiedergegeben werden können. Verwende auch komprimierte Dateiformate, umsicherzustellen, dass die Dateigröße nicht zu groß ist und das Laden der Website nicht verlangsamt.

* Optimiere die Ladezeit: Audio- und Videoinhalte können die Ladezeit der Website beeinträchtigen. Optimiere die Ladezeit, indem du die Dateigröße der Medien reduzierst und das Caching von Medieninhaltenverwendest.

<span>Quelle: https://www.barrierefreiheit-dienstekonsolidierung.bund.de/Webs/PB/DE/gesetze-und-richtlinien/wcag/wcag-artikel.html</span> <br>
<span>Quelle: https://www.w3.org/WAI/media/av/</span>