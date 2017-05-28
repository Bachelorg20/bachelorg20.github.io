---
layout: post
title: "Møte"
date: 2017-03-28 13:50:00
image: '/assets/img/'
description: 'Møte med Norapps 27.03.2017'
tags: 
- blog
- bachelor
- Norapps
categories:
- Møtereferat

---

# Møtereferat
## 27.03.2017
Til stede: Jørgen, Kim Runar, Magnus, Christer, Morten og Roy

Hensikten med møte var å få klarhet i diverse spørsmål vi hadde om utformingen av prosjektet. Hva og hvordan ting skulle gjøres.
Vi ønsket også å få litt tips om selve utviklingen.
Referatet er laget som en Q&A. 

- Skal flere brukere kunne kommentere samme kamp? 
 
Kun en om gangen

- Hvordan skal kommentatorer godkjennes?

Logger inn, så godkjennes manuelt.
Tre nivåer av tilganger (lag, liga, kamp)
Modellering for å evt kunne legge til flere nivåer.

- Er meningen at vi lager egen presentasjonsside av kommentarer eller bruke eksisterende?

De sjekker først om Opta har kommentarer tilgjengelig for en match, dersom det ikke er tilfellet henter de kommentarer fra vår database dersom de eksisterer der. 


- Design-tips? 

Norapps vil lage design-mocks til oss i løpet av uken.


- Hvor skal dataen hentes fra. Spillerprofiler o.l.. Opta? Norapps database?

Henter kamper, spillerinfo og annen info fra Norapps sitt API.

- Tips til oppsett av database. (S3 file storage og mysql?)

Ignorerer S3, bruker kun database og deres API for info.


- Formeninger om ES5 eller ES6? eventuelt supportbibliotek. Babel? 

Bruker express. (vi også)
De bruker også Redux, rest kallene mot API. Spørsmål om det er nødvendig for oss. 
Kan skrive i ES6 og skrive fritt.



- Prioriteringer av brukstilfelle
Norapps vil skrive om listen vi tidligere har fått i prioritert rekkefølge. 


- Annet

utseenet:
utgangspunkt i fotmob.com
mulig bruke deres css.


Vi kan sitte på møterommet på Norapps
De er her fra 9.30 til ca 16.



- Andre tips:

Kommer over kneik at det er litt forvirrende at koden kjører flere ganger (server og klient). Hvor kommer det ut? Chrome eller server konsoll? Dèbugger.
Se at vi får til debugging.
Nettverkstab, Konsolltab (chrome).







