---
---
Rapport om laddningstid
=========================
I denna rapport kommer jag att analysera tre godtyckligt utvalda webbplatser genom att mäta hur snabbt de laddas. Syftet med analysen är att göra en bedömning om webbplatserna innehåller några saker som kan förbättras med tanke på laddningstid och användbarhet.    

Urval
-----------------------

Jag bestämde mig för att jag ville studera laddningshastigheten för bloggar då de generellt innehåller mycket bilder, vilket i sin tur kan påverka laddningshastigheten. Jag gick således in på bloggportalens hemsida och valde två bloggar från listan "mest besökta privata bloggar". Då jag tyckte det skulle vara intressant att studera likheter och skillnader i laddningshastigheten mellan så kallade toppbloggar med en mindre känd blogg valde jag att komplettera urvalet med en mindre känd blogg. Det slutliga urvalet blev: [Kenzas blogg](http://kenzas.se/), [UnderbaraClaras blogg](https://underbaraclaras.se/) och [Calle Rockbäcks blogg](https://callerockback.blogspot.com/).


Metod
-----------------------
För att utvärdera webbplatsernas laddningshastigheten har jag använt mig av verktygen [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) (PSI) samt devtools i webbläsaren Google Chrome. Vid varje mätning har jag uppdaterat sidan med hjälp av shift-ctrl-r för att förhindra att webbläsaren använder sina cachade objekt. Resultaten av mätningarna har slutligen sammanställts i ett [kalkylark](https://docs.google.com/spreadsheets/d/1xc2E_MnMcCMzRXkZba6SqShBKjIisD5BzjHK6xtircA/edit?usp=sharing).

Resultat
-----------------------
####Kenza

[FIGURE class="figure" src=image/kenza.PNG?w=500 caption="Förstasidan på Kenzas blogg."]

Enligt mina mätningar hade Kenzas blogg lägst PSI poäng för mobil. Hennes sida lyckades i snitt enbart generera 37 poäng, vilket medför att sidan hamnar i den röda kategorin. PSI poängen för desktop var betydligt bättre då sidan i snitt genererade 91 poäng, vilket motsvarar den gröna kategorin.

Enligt devtools hade Kenzas blogg i snitt en laddningstid på 1,09 sekunder. Antalet resurser som laddades in var 78 stycken och sidans totala storlek var 2,2 MB.

De åtgärder som PSI föreslår för att förbättra prestandan är att skicka bilder i modernare bildformat, använda bilder med rätt storlek samt att ta bort resurser som blockerar renderingen. För att förbättra laddningshastigheten för mobil föreslår de även att skjuta upp inläsningen av bilder som inte visas på skärmen.

####UnderbaraClara

[FIGURE class="figure" src=image/underbaraclara.PNG?w=500 caption="Förstasidan på Underbara Claras blogg."]

Underbara Claras blogg hade något bättre PSI poäng för mobil än Kenza. Hennes sida lyckades i snitt generera ungefär 65 poäng, vilket medför att sidan hamnar i den gula kategorin. PSI poängen för desktop var även här betydligt bättre då sidan i snitt genererade ungefär 98 poäng, vilket motsvarar den gröna kategorin.

Enligt devtools hade Underbara Claras blogg i snitt en laddningstid på 808 milisekunder, vilket ger hennes sida den överlägset lägsta laddningshastigheten i urvalet. Antalet resurser som laddades in var 41 stycken och sidans totala storlek var 1,3 MB.

De åtgärder som PSI föreslår för att förbättra prestandan är att skicka bilder i modernare bildformat samt att ta bort resurser som blockerar renderingen. För att förbättra laddningshastigheten för mobil föreslår de även att skjuta upp inläsningen av bilder som inte visas på skärmen.

####Calle Rockbäcks

[FIGURE class="figure" src=image/calle.PNG?w=500 caption="Förstasidan på Calle Rockbäcks blogg."]

Calles blogg var den enda som lyckades generera tillräckligt många PSI poäng för mobil för att hamna i den gröna kategorin. Hans sida lyckades i snitt generera 93 poäng. Däremot var PSI poängen för desktop något lägre då sidan i snitt genererade ungefär 84 poäng, vilket motsvarar den gula kategorin.

Enligt devtools hade Calles blogg i snitt en laddningstid på 43,48 sekunder, vilket ger hans sida den överlägset högsta laddningshastigheten i urvalet. Antalet resurser som laddades in var 110 stycken och sidans totala storlek var 1,1 MB.

De åtgärder som PSI föreslår för att förbättra prestandan är att skicka bilder i modernare bildformat, att skjuta upp inläsningen av bilder som inte visas på skärmen samt att minska svarstiden från servern.

Analys
-----------------------
Samtliga sidor i mitt urval fick i princip samma förslag på förbättringsåtgärder, nämligen att skicka bilder i modernare bildformat, ta bort resurser som blockerar renderingen samt att skjuta upp inläsningen av bilder som inte visas på skärmen.

Vinnaren i mitt urval anser jag vara UnderbaraClara så hennes sida hade den lägsta laddningshastigheten samt bäst PSI poäng för desktop. Därtill hade hon även tillräckligt många PSI poäng för mobil för att hamna i den gula kategorin, till skillnad från Kenza vars PSI poäng gör mobil gör att hon hamnar i den röda kategorin. På andraplats kommer Calle. Trots den långa inladdningshastigheten så blev sidan fullt läsbar inom någon sekund vilket gjorde att jag inte upplevde att den totala laddningstiden påverkade användarupplevelsen av webbsidan. Dessutom var Calles sidan den enda som genererat tillräckligt många PSI poäng för mobil för att hamna i den gröna kategorin. Detta innebär att Kenzas webbsida hamnar på sistaplats.

Enligt min åsikt bör en webbsida inte behöva mer än en laddningstid på max 1,5 sekunder för att jag ska anse att den är snabb. För att en sida ska klassas som långsam skulle jag påstå att gränsen går vid 5 sekunder eller mer. Jag anser att alla sidorna i mitt urval laddades in snabbt. Detta trots att jag i mitt urval hade en sida som enligt devtools tog uppemot 44 sekunder för att ha laddat in allt innehåll. Dock var det inget jag märkte av då blogginläggen laddades in inom någon sekund och sidan blev fullt användbar väldigt snabbt. Jag kan således inte lista ut vad det var som genererade den extremt långa laddningstiden, men den påverkade inte användarupplevelsen i detta fallet.

Referenser
-----------------------
[Kenzas blogg](http://kenzas.se/)

[UnderbaraClaras blogg](https://underbaraclaras.se/)

[Calle Rockbäcks blogg](https://callerockback.blogspot.com/)

[PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)


Övrigt
-----------------------

Skriven av: Katarina Käll
