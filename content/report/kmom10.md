---
Title: kmom10
Description: Part 7-10
Template: kmom
---


<div class="kmom-content">

<h1> Kursmoment 10 </h1>
<h2></h2>
<h3></h3>

<h4> Fråga 1 <h4>
<h4>Uppdrag 1: webbplats</h4>
<p>Jag valde kund 2 artisten, Jag skapade en ny webbplats till kunden i katalogen me/kmom10 i kursreport. Jag valde först att börja från noll, det vill säga att jag kopierade portfolio som finns i exempel mappen och försökte köra den, de ville att jag kör composer install för att installera Vendor mappen, jag körde det kommandot men fick att i user/bin/composer.phar finns inte. Jag testade kolla om jag hade composer i min dator och körde då composer --version och fick samma sak. Min portfolio i me-mappen fungerade bra då. Jag kanske hade missat något när jag installerade composer innan när jag började med min portfolio så jag försökte följa kontraktionerna i kursmoment 1 och 2 och installerade labbmiljön igen. Men den ville inte funka och jag ville inte lägga mer tid på det, därför kopierade jag min portfolio och körde den i min kmom10-mappen och den funkade bra. Sen började jag rensa lite kod som index-filerna, SASS-filer och redigerade .htaccess och package.json filer. </p>

<p>Jag hade skissat innan hur min kund ville att webbplatsen skulle se ut och vad det hade för syfte och mål. Webbplatsen består av 3 sidor, en förstasida, about och galleriet. Jag använde en hero-bild i mitt vanliga tema och en annan hero-bild i mitt andra tema. Jag har lagt en logga och favicon. Webbplatsen har en fungerade navigering som fungerar för både desktop och mobil. Innehållet är lagom, använde Cimage för att få rätt storlek på bilderna och detta har jag använt i galleriet. Jag skrev en liten text på förstasidan som gynnar företagens profil. I galleriet visade jag vad kunden jobbar med. I min about-sidan la jag informationen om kunden som jag hade tolkat kundens önskemål, verksamhet och hur kunden ville att webbplatsen skulle se ut och användas. </p>

<h4> Uppdrag 2: tema</h4>
<p>Det vanliga tema är ett ljust tema som är anpassat till kunden. Jag hade delat upp SASS-filerna i flera moduler och jag gjorde rimliga val för färgpalett och typografi så att det matchade kundens profil. Alla mina färger som jag hade använt i både teman finns i en SASS-fil som heter variables-extend. Som jag hade tolkat kraven så skulle alla färger som användas i webbplatsen skrivas i variabler. På min about-sidan finns en länk till dokumentationen där beskrev jag färgpaletten och berättade hur jag valde färgerna, beskrev typografin, desinprinciper och designelements som jag hade använt. Jag berättade vilken känsla som kunde ville uppnå med webbplatsen och hur jag delade upp mina SASS-filer. Jag gjorde det på både det vanliga och mörka temat. </p>

<h4>Uppdrag 3: Responsivitet och tillgänglighet</h4>
<p> På mina sidor använde jag en absolut position för att kunna placera omslagsbilden, logo, navigeringen och rubriken som följer med på alla sidor. I den responsiva delen hade jag en längd på logon, rubrikerna flyttas 1em, på footer-delen tog jag bort float och margin då hade jag en kontaktinformation på väster-sidan och sociala medier på den högre sidan. Eftersom jag ville använda avstånd mellan element så hade jag lagt en bredd på paragraferna på 70% och flyttat de till mitten av sidan därför på den responsiva-delen återställer jag bredden till 100% och flyttar paragraferna till vänster. I galleriet använde jag CSS-grid för att kunna placera bilderna 3 X 2, för surfplattor som har max bredden 992px placeras bilderna 2 X 3 och för mobilerna som har max bredden 767px placeras 1 i rad. Bilderna anpassas efter enhet med hjälp av cimage och <pictare>/srcset. I gallery TWIG-filen lägger jag picture tags och i de lägger jag två source tags, den ena ska köra originala bilder när skärmen är bredare än 668px, mellan 668 och 376px laddar in bilder med 667 i bredd och under 767px laddas bilder med bredden 375.</p>

<p>Sidorna har 100 i accessibility enligt lighthouse via devtools, jag körde lighthouse accessibility på alla sidor och jag fick 100 på desktop och mobil från första gången. Jag fick inte accessibility mindre än 100 så jag behövde inte fixa någonting då. Färgvalet på sidorna skulle ta färgblindhet i tanke, jag hade använt hemsidan Colorblind för att testa min publicerade sida. På min hero-bild hade jag använt filer på 60% efter jag testade min sida såg jag att det var för mycket 60%, de visade att det behövde vara lite mer mörkare, jag körde på colorfilter Protanopla, då minskade jag filtret på den från contrast 60% till 40% och då blev den bättre. Det gick inte att testa mitt andra tema, jag bytte till andra tema och testade köra den men då visade de mig mitt vanliga tema istället.
</p>

<h4>Uppdrag 4: Tema alternativt</h4>
<p>Jag gjorde ett till tema till kunden, en mörkare tema. Jag ändrade då färgpaletten, typografi, designprinciper och designelement. Temat är anpassat till kundens profil och jag beskrev allt jag hade gjort i det temat i min dokumentation. I footern finns 3 sociala medier länkar, en till dbwebb Youtube, en min github kursrapport och en till att byta tema. </p>

<h4> Fråga 2 </h4>
<p>2-	Det gick bra med projektet, det var enkelt tycker jag då allt som vi har gått genom i kursmomenten har vi använt i projekten, det var ingenting nytt då. Jag la inte mycket tid på projektet då satsar jag inte på högre betyg, men jag tycker att det var kult med analyserna, man lär sig mycket. Projektet tog inte långt tid för mig, jag började också jobba med projektet sent men jag gjorde inte sista två uppdrag. Det som var lätt var att koda, navigering koden hade jag färdigt, jag gjorde bara små ändringar, i galleriet gjord jag också små ändringar. Det som var svårt var att hitta bra bilder, jag är inte 100% nöjd på de bilder som jag använde men det var inte enkelt att hitta bra bilder som passar innehållet och som får användas i de webbplatserna som vi fick använda. 
</p>

<h4> Fråga 3 </p>
<p> Jag gillade inte jobba med Pico och skriva i twig och md filer, men det var en lärorik kurs speciellt analyserna, jag fick lära mig mycket av de när det gäller att analysera webbplatsers design och skriva rapport. Jag gillade att jobba med SASS och cimage. Jag är nöjd med kursen och jag skulle rekommendera det till andra. På en skala 1-10 ger jag betyget 7.5.
</p>
</div>