Kmom05 - Laddningstid
=======================

Den här undersökningen hänvisar till tre olika webbplatser och syftar till att mäta laddningstid, antal resurser och en sidas totala storlek. I udnersökningen noteras det ifall det finns åtgärder som kan förbättra webbplatsernas laddningtider.

Urval
-----------------------

Följande tre webbplatser har valts att testas i den här undersökningen: [Friskis&Svettis](http://www.friskissvettis.se/stockholm), [Matsmart](https://www.matsmart.se/) och [Nitty Gritty](http://www.nittygrittystore.com/). Dessa webbplatser är alla välbesökta och de skiljer sig totalt åt i både kategori, struktur och innehåll, därav intressanta att jämföra i den här undersökningen.

----------------

Metod
-----------------------

För att mäta webbplatsernas laddningstid används verktyget [PageSpeed Insights](http://developers.google.com/speed/pagespeed/insights/). För varje webbplats har tre undersidor valts ut och mätningar utförts på respektive sida för mobil enhet och dator. I samband med mätningarna listas en rad förbättringsåtgärder som presenteras i den här rapporten.

För att mäta webbplatsernas laddningstid, resurser som laddas samt sidornas totala storlek används devtools flik networks. Följande mätning görs tre gånger på respektive undersida och ett snittvärde från dessa mätningar presenteras i rapporten.

---------------------

Resultat
-----------------------

<b>Friskis&Svettis</b>

[FIGURE src="img/friskissvettis.jpg" class="right" caption="Friskis&Svettis startsida"]

<b>Resultat på mätningar som utförts med [PageSpeed Insights](http://developers.google.com/speed/pagespeed/insights/):</b>

[Startsida](https://www.friskissvettis.se/stockholm) -
På mobil enhet uppmättes en hastighet på 50 och på dator en hastighet på 97.

[Bokningsvy](https://friskisstockholm.brponline.se/#/webcategories) -
På mobil enhet uppmättes en hastighet på 4 och på dator en hastighet på 94.

[Anläggningar](https://www.friskissvettis.se/Stockholm/Anlaggningar) -
På mobil enhet uppmättes en hastighet på 73 och på dator en hastighet på 98.


<b>Resultat på mätningar som utörts med devtools flik networks:</b>

[Startsida](https://www.friskissvettis.se/stockholm) -
Sidans laddningstid: 4,17 s |
Antal resurser: 149 |
Sidans totala storlek: 4,9 MB

[Bokningsvy](https://friskisstockholm.brponline.se/#/webcategories) -
Sidans laddningstid: 1,67 s |
Antal resurser: 15 |
Sidans totala storlek: 2,2 MB

[Anläggningar](https://www.friskissvettis.se/Stockholm/Anlaggningar) -
Sidans laddningstid 3,25 s |
Antal resurser: 108 |
Sidans totala storlek 1,8 MB

-----------------

<b>Matsmart</b>

[FIGURE src="img/matsmart.jpg" class="right" caption="Matsmart startsida"]

<b>Resultat på mätningar som utförts med [PageSpeed Insights](http://developers.google.com/speed/pagespeed/insights/):</b>

[Startsida](https://www.matsmart.se/) -
På mobil enhet uppmättes en hastighet på 23 och på dator en hastighet på 69.

[Nyinkommet](https://www.matsmart.se/nyinkommet) -
På mobil enhet uppmättes en hastighet på 2 och på dator en hastighet på 67.

[Så funkar Matsmart](https://www.matsmart.se/sa-funkar-matsmart) -
På mobil enhet uppmättes en hastighet på 11 och på dator en hastighet på 72.


<b>Resultat på mätningar som utörts med devtools flik networks:</b>

[Startsida](https://www.matsmart.se/) -
Sidans laddningstid: 9,71 s |
Antal resurser: 210 |
Sidans totala storlek: 2,9 MB

[Nyinkommet](https://www.matsmart.se/nyinkommet) -
Sidans laddningstid 7,79 s |
Antal resurser: 180 |
Sidans totala storlek 1,6 MB

[Så funkar Matsmart](https://www.matsmart.se/sa-funkar-matsmart) -
Sidans laddningstid 13,28 s |
Antal resurser: 95 |
Sidans totala storlek 2,3 MB

---------------------

<b>Nitty Gritty</b>

[FIGURE src="img/nittygritty.jpg" class="right" caption="Nitty Gitty startsida"]

<b>Resultat på mätningar som utförts med [PageSpeed Insights](http://developers.google.com/speed/pagespeed/insights/):</b>

[Startsida](http://www.nittygrittystore.com/) -
På mobil enhet uppmättes en hastighet på 70 och på dator en hastighet på 100.

[Women](https://www.nittygrittystore.com/women) -
På mobil enhet uppmättes en hastighet på 58 och på dator en hastighet på 100.

[Men](https://www.nittygrittystore.com/men) -
På mobil enhet uppmättes en hastighet på 70 och på dator en hastighet på 100.


<b>Resultat på mätningar som utörts med devtools flik networks:</b>

[Startsida](http://www.nittygrittystore.com/) -
Sidans laddningstid: 1,58 s |
Antal resurser: 30 |
Sidans totala storlek: 2,5 MB

[Women](https://www.nittygrittystore.com/women) -
Sidans laddningstid 2,22 s |
Antal resurser: 39 |
Sidans totala storlek 2,7 MB

[Men](https://www.nittygrittystore.com/men) -
Sidans laddningstid 1,83 s |
Antal resurser: 43 |
Sidans totala storlek 3,0 MB

------------------

Analys
-----------------------

För [Friskis&Svettis](https://www.friskissvettis.se/stockholm) webbplats presenteras följande åtgärder för snabbare inläsning av sidan. Samtliga åtgärder minskar mobildaförbrukningen samt inläsningstiden. Att skicka bilder i modernare format så som JPEG 2000, JPEG XR eller WebP påverkar dessutom nedladdningstiden då de oftast ger bättre komprimering än PNG och JPEG.

1. Att använda bilder med rätt storlek.
2. Skicka bilder i modernare format.
3. Optimera bilder.

För [Matsmart](https://www.matsmart.se/) presenteras följande åtgärder för snabbare inläsning av sidan:

1. Att använda bilder med rätt storlek.
2. Skjuta upp inläsningen av bilder som inte visas på skärmen så att alla viktiga resurser prioriteras.
3. Ta bort CSS-regler som inte används från formatmallarna.
4. Skicka bilder i modernare format, se åtgärd i mätning ovan.

För [Nitty Gritty](http://www.nittygrittystore.com/) föreslås enbart en åtgärd för dator, att använda bilder av rätt storlekar. För mobil enhet presenteras följande åtgärder:

1. Använda bilder med rätt storlek.
2. Skjuta upp inläsningen av bilder som inte visas på skärmen.
3. Ta bort resurser som blockerar renderingen.
4. Skjuta upp CSS-filer som inte används.

Några förbättringsåtgärder uppskattas som mer betydande i mätningarna som utförts. Undersökningen visar att de gemensamma faktorer som framkommit påverkar sidornas laddningstid, har med optimering av bilder samt CSS-regler att göra. Att skicka bilder i modernare format, använda bilder i rätt storlek, samt att ta bort CSS-regler som inte används samt tycks ge störst effekt för samtliga webbplatser för mobil enhet såväl som dator.

1. Nitty Gritty
2. Friskis&Svettis
3. Matsmart

På plats ett i undersökningen för både dator och mobil enhet kommer Nitty Gritty. Undersökningen visar inga direkta anmärkningar på laddningstiden för webbplatsen på dator och via mobil enhet är snittvärdet relativt högt och därför utses Nitty Gritty som vinnare. På andra plats kommer Friskis&Svettis och på tredje plats Matsmart.

Jag anser att Nitty Gritty, med en genimsnittlig laddningstid på under 2 s för samtliga undersidor som mätts, klassas ha en snabb laddningstid. Matsmart däremot anser jag ha en väldigt långsam laddningstid med ett genomsitt på ca 11 s. På Matsmarts alla tre undersidor laddas betydligt fler resurser än på de övriga två webbplatserna vilket märkbart bidrar till den extremt långa laddningstiden.

-----------------

Referenser
-----------------------

Bloggartikeln [Using page speed in mobile search ranking](https://webmasters.googleblog.com/2018/01/using-page-speed-in-mobile-search.html).

Artikeln [Moz om Page Speed](https://moz.com/learn/seo/page-speed).

Sektionen [Bilder](https://dbwebb.se/guide/design-med-html5-och-css3/bilder) i guiden på dbwebb.

-------------------

Övrigt
-----------------------

Medverkande i undersökningen: Lisa Hult.
