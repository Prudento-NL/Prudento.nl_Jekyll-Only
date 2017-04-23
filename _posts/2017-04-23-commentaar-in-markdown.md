---
layout: post
title:  Commentaar in Markdown
date:   2017-04-23 13:45
categories: website
---
Voor het toevoegen van commentaar in Markdown bestanden is geen syntax gedefinieerd.
Zie hiervoor o.a. de originele specificatie van Markdown op de site van de bedenker [John Gruber] en de site [GitHub Mastering Markdown].   

Om commentaar toe te voegen kan de volgende oplossing gebruikt worden waarbij eigenlijk de methode om linken toe te voegen wordt  misbruikt:
```
(empty line)
[comment]: # (This actually is the most platform independent comment)
```
**Uitleg**  
* De (empty line) is een lege regel tussen de tekst en het commentaar.  
* De tekst tussen de haken [comment] kan naar eigen inzicht aangepast worden. Je ziet ook vaak [//] om het commentaar weer te geven.  
* De tekst tussen de () is het werkelijke commentaar.  
* Het hekje # is gebruikt i.p.v. <> om het zoveel mogelijk platform onafhankelijk te maken.

Voor aanvullende uitleg en details: zie de bron op [Stackoverflow].

[John Gruber]: http://daringfireball.net/projects/markdown/ "http://daringfireball.net/projects/markdown/"
[GitHub Mastering Markdown]: https://guides.github.com/features/mastering-markdown/ "https://guides.github.com/features/mastering-markdown/"
[Stackoverflow]: http://stackoverflow.com/questions/4823468/comments-in-markdown/32190021#32190021 "http://stackoverflow.com/questions/4823468/comments-in-markdown/32190021#32190021"
