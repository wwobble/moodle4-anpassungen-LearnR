Blockbereich oben ist wirklich super, aber der Button zum Auf bzw. zuklappen ist einfach hässlich

Ich habe den Pfeil kleiner gemacht und den Hintergrund transparent,
Beim Schließen-Button habe ich den Pfeil weggemacht, den Text kleiner und den Hintergrund transparent.

```
.fa-2x {
  font-size: 1em;
}


.headerbutton{
  
  background-color: #fff;
  border-color: #fff;
  border-radius: 1rem;
}

.blockpanelbutton{
  
  background-color: transparent;
  border-color: transparent;
}

.blockpanelbutton .fa-arrows-v::before {
  content: "";
}

```


Den Bereich unten habe ich ebenfalls angepasst. 
- Hintergrundfarbe transparent
- Rand weg

```
.container-fluid.footerblocks .fp-blocks{
background-color: transparent;}

.container-fluid.footerblocks section[role=complementary]
{
border-style: none;
}
```