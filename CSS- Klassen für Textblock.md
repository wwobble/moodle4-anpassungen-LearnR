In Website-Administration -> Plugins ->Blöcke -> Textblock

Zusätzliche CSS-Klassen erlauben (block_html_allowcssclasses) aktivieren.

CSS Klassen im Raw-SCSS definieren
```
/* definiert CSS-Klasse für Infobox */
.infobox {
background-color: #D3FFE9;
}
```

Mit Icon (CSS Klasse für Verwendung: infoboxicon)
```
.infoboxicon .card-title::before {
 content: "\f05a";
 font-family: FontAwesome;
 display: inline-block;
        padding-right: 3px;
        vertical-align: middle;
        font-weight: 900;
}
```
Um Rand anzuzeigen:
```
/* definiert CSS-Klasse für Rand */
.borderbox {
border-style: solid !important;
}
```
K:K können Textblöcke formatieren durch Verwendung von CSS-Klassen

Man kann Klassen auch kombinieren z.B. will ich eine Infobox (grüner Hintergrund) und einen Rand, bekommt der Textblock beide Klassen: infobox borderbox
