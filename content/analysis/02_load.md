---
Title: load
Description: Part 2
Template: index
---

Utvärdering av webbplatsers laddningstid och användbarhet 
=======================

Uppgiften handlar om att välja ut 3 webbplatser som ska analyseras. Vi ska testa dem för att mäta hur snabbt de laddas och om de innehåller några saker som kan förbättras med tanke på laddningstid och användbarhet. 

Urval
-----------------------

Jag valde ut 3 webbplatser, Pubg Mobile (Player Unknown’s Battlegrounds), Zalando och Nordea banken. Jag ville blanda och välja ut 3 webbplatser som inte har något gemensamt, de webbplatserna har olika mål och innehåll. Pubg Mobile är en spelwebsida som handlar om spelet, Zalando är ett modeföretag som säljer livsstilsprodukter och modekläder online, Nordea är en bank sida. Så jag har 3 olika webbplatser, en för spel, en för modekläder och en för ekonomi. 

Metod
-----------------------

Jag har använt mig av PageSpeed Insights för att analysera laddningstid för dator och mobil. Jag använde devtools network i Chrome för att mäta sidornas laddningstid med antalet resurser samt sidornas totala storlek. För alla 3 sidor gjorde jag mätningen 3 gånger och tog snittet av mätvärdena. Jag använde också Google Kalkylark för att skriva in alla mätvärdena jag gjorde i mina 3 webbplatser. 

Resultat
-----------------------

<span class="bold-text">Pubg Mobile </span> fick betyget 46 av 100 enligt PageSpeed DATOR analys och 41 av 100 MOBIL analys.
<p> Dator-analys:</p>
Labbdata: First Contentful Paint 0.4s, Time to Interactive 7.1s, speed Index 3.9s, Total Blocking Time 190ms, Largest ContentPaint 6.6s, Cumulative Layout Shift 0.035. 
<p> De förbättringsmöjligheterna som kan göras för att hjälpa sidan läsas in snabbare på datorn: </p>

<div class="list">
<ul>
    <li>Skicka bilder i modernare bildformat, uppskattad tidsbesparing är 4.96s. (Hemsidan fick många varningar). </li>
    <li> Koda bilder effektivt, uppskattad tidsbesparing är 3.28s.</li>
    <li> Använd bilder med rätt storlek, uppskattad tidsbesparing är 0.88s.</li>
    <li> Ta bort JavaScript som inte används, uppskattad tidsbesparing är 1s.</li>
    <li>Minska serverns första svarstid, uppskattad tidsbesparing är 0.68s.</li>
    <li>Ta bort resurser som blockerar renderingen, uppskattad tidsbesparing är 0.21s.</li>
</ul>
</div>

Mobil-analys:
<p>Labbdata: First Contentful Paint 1.8s, Time to Interactive 107.7s, speed Index 37.8s, Total Blocking Time 320ms, Largest ContentPaint 58.9s, Cumulative Layout Shift 0.016. </p>

<p> De förbättringsmöjligheterna som kan göras för att hjälpa sidan läsas in snabbare på mobiler: </p>

<div class="list">
<ul>
    <li>Använd bilder med rätt storlek, uppskattad tidsbesparing är 184.83s.</li>
    <li> Skjut upp inläsningen av bilder som inte visas på skärmen, uppskattad tidsbesparing är 168.18s.</li>
    <li> Skicka bilder i modernare bildformat, uppskattad tidsbesparing är 152.25s.</li>
    <li> Ta bort JavaScript som inte används, uppskattad tidsbesparing är 1.8s.</li>
    <li>Ta bort resurser som blockerar renderingen, uppskattad tidsbesparing är 0.54s.</li>
    <li>Minska serverns första svarstid, uppskattad tidsbesparing är 0.57s.</li>
    <li>Koda bilder effektivt, uppskattad tidsbesparing är 120.72s.</li>
    <li>Läs in viktiga resurser i förväg, uppskattad tidsbesparing är 0.36s.</li>
</ul>
</div>

Enligt devtools analysen visar den laddningstid 4.5s, antal resurser som laddas 20.8MB och sidans totala storlek 25.2MB.

<div class="image">
    <a href="../image/pubg_mobile.jpg"><img src="../image/pubg_mobile.jpg"> </a>
</div>

<span class="bold-text"> Zalando </span>fick betyget 41 av 100 enligt PageSpeed DATOR analys och 16 av 100 MOBIL analys.
<p> Dator-analys:</p>
Labbdata: First Contentful Paint 0.7s, Time to Interactive 3.9s, speed Index 4.2s, Total Blocking Time 1050ms, Largest ContentPaint 4.2s, Cumulative Layout Shift 0.019. 

<p>De förbättringsmöjligheterna som kan göras för att hjälpa sidan läsas in snabbare på datorn:</p>

<div class="list">
<ul>
    <li>Ta bort oanvända CSS, uppskattad tidsbesparing är 0.13s.</li>
    <li> Skjut upp inläsningen av bilder som inte visas på skärmen, uppskattad tidsbesparing är 0.24s..</li>
    <li> Använder bilder med rätt storlek, uppskattad tidsbesparing är 0.24s.</li>
    <li> Ta bort JavaScript som inte används, uppskattad tidsbesparing är 0.59s.</li>
</ul>
</div>

Mobil-analys:
<p> Labbdata: First Contentful Paint 3.1s, Time to Interactive 22.4s, speed Index 13.2s, Total Blocking Time 8280ms, Largest ContentPaint 5.9s, Cumulative Layout Shift 0.566. </p>

<p>De förbättringsmöjligheterna som kan göras för att hjälpa sidan läsas in snabbare på mobiler:</p>

<div class="list">
<ul>
    <li>Använd bilder med rätt storlek, uppskattad tidsbesparing är 7.14s.</li>
    <li> Skjut upp inläsningen av bilder som inte visas på skärmen, uppskattad tidsbesparing är 3.78s.</li>
    <li> Skicka bilder i modernare bildformat, uppskattad tidsbesparing är 0.75s.</li>
    <li> Ta bort JavaScript som inte används, uppskattad tidsbesparing är 1.05s.</li>
    <li>Ta bort resurser som blockerar renderingen, uppskattad tidsbesparing är 0.45s.</li>
    <li> Ta bort oanvända CSS, uppskattad tidsbesparing är 0.48s.</li>
    <li>Koda bilder effektivt, uppskattad tidsbesparing är 0.45s.</li>
</ul>
</div>

Enligt devtools analysen visar den laddningstid 3.5s, antal resurser som laddas 1.8MB och sidans totala storlek 5.0MB.

<div class="image">
    <a href= "../image/zalando.jpg"> <img src="../image/zalando.jpg"> </a>
</div>


<span class="bold-text">Nordea </span> banken fick betyget 97 av 100 enligt PageSpeed DATOR analys och 33 av 100 MOBIL analys.

<p>Dator-analys:</p>

Labbdata: First Contentful Paint 0.5s, Time to Interactive 1.8s, speed Index 1.2s, Total Blocking Time 70ms, Largest ContentPaint 0.9s, Cumulative Layout Shift 0.006. 

<p>De förbättringsmöjligheterna som kan göras för att hjälpa sidan läsas in snabbare på datorn: </p>

<div class="list">
<ul>
    <li>Läs in viktiga resurser i förväg, uppskattad tidsbesparing är 0.5s.</li>
    <li> Aktivera textkomprimering, uppskattad tidsbesparing är 0.24s.</li>
    <li>Ta bort resurser som blockerar renderingen, uppskattad tidsbesparing är 0.21s.</li>
    <li>Ta bort JavaScript som inte används, uppskattad tidsbesparing är 0.2s.</li>
</ul>
</div>

Mobil-analys:

<p>Labbdata: First Contentful Paint 2.9s, Time to Interactive 11.8s, speed Index 8.3s, Total Blocking Time 5960ms, Largest ContentPaint 3.9s, Cumulative Layout Shift 0.248. </p>

<p>De förbättringsmöjligheterna som kan göras för att hjälpa sidan läsas in snabbare på mobiler:</p>

<div class="list">
<ul>
    <li>Läs in viktiga resurser i förväg, uppskattad tidsbesparing är 3.21s.</li>
    <li> Aktivera textkomprimering, uppskattad tidsbesparing är 1.5s.</li>
    <li>Ta bort resurser som blockerar renderingen, uppskattad tidsbesparing är 1.23s.</li>
    <li>Ta bort JavaScript som inte används, uppskattad tidsbesparing är 1.35s.</li>
    <li>Skicka bilder i modernare bildformat, uppskattad tidsbesparing är 0.3s.</li>
    <li>Ta bort oanvända CSS, uppskattad tidsbesparing är 0.15s.</li>
    
</ul>
</div>

Enligt devtools analysen visar den laddningstid 1.13s, antal resurser som laddas 1.0MB och sidans totala storlek 1.4MB.

<div class="image">
    <a href= "../image/norde.jpg"> <img src="../image/norde.jpg"> </a>
</div>




Analys
-----------------------

<p>Alla mätningen som gjordes i denna analys finns här i <a href="https://docs.google.com/spreadsheets/d/1OSGk5hC0iN6RaqMiY9s8VA0aqBEba9BBOkJATj1qsxM/edit?usp=sharing"> Google Kalkylark </a>. De vanligaste förbättringsåtgärderna för desktop kan vara att ta bort resurser som blockerar renderingen, ta bort JavaScript som inte används och använda bilder med rätt storlek. De vanligaste förbättringsåtgärderna för mobile kan vara att läsa in viktiga resurser i förväg, Ta bort resurser som blockerar renderingen, Ta bort JavaScript som inte används, Skicka bilder i modernare bildformat, Ta bort oanvända CSS. De flesta hemsidor som innehåller många bilder som Zalando och Pubg mobile kan förbättringsåtgärderna vara att använda bilder med rätt storlek, Skjut upp inläsningen av bilder som inte visas på skärmen och koda bilder effektivt. </p>

<p> Sammanfattningsvis kan jag säga att den webbplatsen som vinner analys testet är Nordea banken som fick betyget för desktop 97 av 100 och mobile 33 av 100. Den är mycket sämre på mobiler men fortfarande bättre än de andra då innehåller den inte många bilder, den laddas snabbt, laddningstiden enligt mina mätvärden ligger mellan 1.04s och 1.8s, webbplatsens storlek är 1.4MB därför laddas den snabbt och det är inte många resurser som labbas. </p>

<p> Gränsen för absolut laddningstid som jag själv uppfattar snabb är mellan 1.5s och 3.5s och långsam från 4 och uppåt. Jag tycker att Nordea klarar testet bra till skillnad från Pubg Mobile som innehåller en video och bildgalleri på sitt första sidan, den är en jättestor webbplats som tar lång tid att ladda speciellt på mobiler och det är på grund av storleken på webbplatsen och de bilderna som tar stor plats på hemsidan.</p>

Referenser
-----------------------

<p> <a href="https://developers.google.com/speed/pagespeed/insights/"> Laddningssida </a></p>
<p> <a href="https://docs.google.com/spreadsheets/d/1OSGk5hC0iN6RaqMiY9s8VA0aqBEba9BBOkJATj1qsxM/edit?usp=sharing"> Google Kalkylark </a></p>


Källor som använts i denna rapport:
<p> <a href="http://www.pubgmobile.com/en-US/index.shtml"> Pubg Mobile</a></p>
<p> <a href="https://www.zalando.se/"> Zalando </a> </p>
<p> <a href= "https://www.nordea.se/" > Nordea </a> </p>

Övrigt
-----------------------

Rapporten är skriven av Ranim Hanna Malko