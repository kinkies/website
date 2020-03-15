# Webseite für `kinkies.de`

Die Quellen der Webseite verwenden das Format
[Markdown](https://pandoc.org/MANUAL.html#pandocs-markdown)
in der erweiterten Variante von `pandoc`. Die
entsprechenden HTML-Seiten können mit den
Kommandos

    $ pandoc --standalone index.md -o index.html
    $ pandoc --standalone --from=markdown+smart mv.md -o mv.html

erzeugt werden.
