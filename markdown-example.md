
# 0.) Inhalt
* [1.) Überschriften](#headers)
* [2.) Absätze](#absaetze)
* [3.) Textauszeichnungen](#textauszeichnung)
* [4.) Listen](#listen)
* [5.) Zitate](#zitate)
* [6.) Coding](#coding)
* [7.) Horizontal Lines](#Lines)
* [8.) Links](#links)

<a id="headers"></a>
# 1.) Überschriften

# Überschrift 1
## Überschrift 2
### Überschrift 3

 <a id="absaetze"></a>
# 2.)Absätze

Dies ist ein deutscher Absatz, mit hinreichend Länge hoffentlich und gutem Zeilenumbruch -  und getestetem zweisprachigem Spellchecking.

This is an English written paragraph, with sufficient length and a fitting line feed - and verified bilingual spell checker

Und hier selbstgesetzter Zeilenumbruch.  
Wird durch zwei Blanks am Ende ausgelöst.  
Klappt.

<a id="textauszeichnung"></a>
# 3.) Textauszeichnungen

normal text  
**bold text**  
*italic text*  
***bold and italic Text***

Alternative Notation in unsortierter Liste:
* __bold Text__
* _italic Text_
* ___bold and italic text___

<a id="listen"></a>
# 4.) Listen
Verschachtelte Liste

* Level 1
  * Level 1.A
    * Level 1.A.a
  * Level 1.B
* Level 2

Sortierte Liste

1. Level a
   1. Level a.x
   2. Level a.  
      Note: 1.1 does not work
2. Level b

 <a id="zitate"></a>
# 5.A) Zitate

> Dies wird als Zitat wiedergegeben.
>> *Everything* is going according to **plan**.
>
> **Darin sind Formatierungen möglich. Und der Umbruch ist wieder automatisch weich.**

<a id="footnote" ></a>
# 5,B) Fußnote

Dieses is ein Text, der innen eine Fußnote[^1] enthält und am Ende auch eine.[^2]

[^1]: Anmerkung im Satz

[^2]: Anmerkung am Satzende

 <a id="coding" ></a>
# 6.) Coding

Codeblocks werden mit 4 Blanks ausgezeichnet:

    if (Zeile 1)
    then
      while(true) do echo $value; done
    else
    fi

Inline `codes` sind über Backticks möglich `AND`. Das Rendern hängt von der Maschine ab.

<a id="lines" ></a>
# 7.) <a id="lines" />Horizontal Lines

---
Drei `***` oder `---`
***
<a id="links" ></a>
# 8.) Links

* nach draußen: [fodina.de](http://fodina.de "Eine Fundgrube") = `[fodina.de](http://fodina.de "Eine Fundgrube")`
* Lokale Bilder: ![Tux, the Linux mascot](tux.png)
* Anchor Links:
  * Anchor: `<a id="anchor-name" />`
  * Anchor-Link: `[Link-Text](#anchor-name)`  
    Note: anchor links only work in texts, interpreted by GitHub markdown viewer, not in normal viewers

<a id="tables"></a>
# 9.) Tabellen

| 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|
| a | ab | abc | abcd | abcde |
| xyz | xy | x | xy | xyz |
| a | b | c | d | e |
