Övning if-sats
================

Översikt
---------
Bollen ska styras med piltangenterna. Instruktioner förljer.

Kom ihåg att kommentera koden.

Utmaning 1
-------------

skriv följande if-sats

  om key är 37
    flytta bollen 25 pixlar till vänster med koden nedan
    ball.style.left = ball.offsetLeft - 25 + "px";

  om key är 39
    flytta bollen 25 pixlar till höger

  om key är 38
    flytta bollen 25 pixlar uppåt med koden nedan
    ball.style.top = ball.offsetTop - 25 + "px";

  om key är 40
    flytta bollen 25 pixlar nedåt

###Problem
Bollen kan flyttas utanför den blå rektangeln. I nästa utmaning löses detta.

Utmaning 2
-----------

På svenska blandat med JavaScript blir lösningen.

  om key är 37
    flytta bollen 25 pixlar till vänster med koden nedan
    ball.style.left = ball.offsetLeft - 25 + "px";

    om boller är för långt till vänster
      flytta den till vänsterkanten

  på samma sätt för de övriga fallen höger, upp, ner

###tips

  ball.offsetLeft

  ball.offsetTop

Utmaning 3 - extra - konstanter
-----------
Det är dags att göra koden vackrare.

Deklarera fyra konstanter ovanför if-satserna. Döp konstanterna till arrowLeft, arrowRight, arrowUp, och arrowDown. Låt de få värdena 37, 39 38 och 40.

Byt ut siffervärdena i if-satserna mot arrowLeft, och så vidare.

Utmaning 4 - extra - fler konstanter
-----------------
Fortsätt att göra koden vackrare.

Använd konstanter för att få bort alla siffervärden ur koden. Det är bara konstanterna som får ha siffervärden.

###tips

area.offSetWidth ger den blå rektangels bredd

area.offsetHeight ger den blå rektangels höjd

Utmaning 5 - extra - funktioner
-------------------
Fortsatt arbete med att få vackrare kod.

Deklarera två funktioner moveRight och moveUp som sköter förflyttningarna.

Anropet

  moveRight(10);

flyttar bollen 10 pixlar åt höger.

På samma sätt flyttar anropet

  moveUp(10);

bollen 10 pixlar uppåt.



