---
layout: post
title:  Synchroniseren files met atom-sync
date:   2016-11-20 13:15
categories: website
---

===== 21-01-2018 UPDATE ===== <br>
Atom-sync werkt niet meer zoals verwacht. Sync is niet meer aanwezig in het context-menu. Dit is een gevolg van een update van Atom. Dit is te repareren door directories aan te passen, maar daarna werkte de config file creatie nog niet. De package lijkt niet onderhouden te worden, dus verwijderd en overgestapt op de package remote-ftp. <br>
============================<br>

Ik gebruik [Atom] al een tijdje als text editor. Het is een ontwikkeling van [GitHub] dus ook weer goed geïntegreerd met [Git], [GitHub] en [Jekyll].
[Atom] kan op meerdere platforms gebruikt worden en is volledig in te richten naar je eigen smaak.
Er zijn packages beschikbaar die extra functionaliteit kunnen bieden.

Eén van de packages is [atom-sync]. Met [atom-sync] kan je files en directories synchroniseren tussen een remote host en je lokale systeem.
Bijvoorbeeld het synchroniseren van je lokaal ontwikkelde website met je provider.
Synchronisatie gebeurd met [ssh] en [rsync] die overigens wel apart op je systeem geïnstalleerd moeten zijn.

[Git]: https://git-scm.com/
[Atom]: https://atom.io/
[GitHub]: http://github.com/
[Jekyll]: http://jekyllrb.com/
[atom-sync]: https://atom.io/packages/atom-sync
[ssh]: https://nl.wikipedia.org/wiki/Secure_Shell
[rsync]: https://nl.wikipedia.org/wiki/Rsync
