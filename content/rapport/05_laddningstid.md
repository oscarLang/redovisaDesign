Utvärdering av laddningstiden hos webbplatser.
=======================

Denna rapportens syfte är att analysera och diskutera laddningstiden för tre olika webbplatser.

Urval
-----------------------
I rapporten fokuserar att analysera tre webbplatser som används mycket i vardagen. Urvalet består av sidorna [ICA.se](https://handla.ica.se/), [Reddit.com](https://www.reddit.com/) och [SvtPlay](https://www.svtplay.se/). De är av olika storlek och används för olika saker så det blir intressant att analysera  skillnader.
Metod
-----------------------
För att samla in mätvärden från alla webbplatser så användes [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/). Det är ett verktyg som ger ett betyg på hur snabbt en webbplats laddar samt ger tips på saker som kan förbättras.

Utöver pagespeed så användes även chrome devtools för att få mätvärdena laddningstid, resurser och storlek. Datan sparades i ett [excel-dokument](https://docs.google.com/spreadsheets/d/1c-KHk6nJ-6YbBxk1q4z9YBadgjnd5WqcaMVoKGHK4Wk/edit?usp=sharing).

###ICA
[FIGURE src="image/hemsidor/ica.jpg"?w=300 class="right" caption="Startsida för ica."]
Ica hade i snitt cirka två sekunders laddningstid och var cirka två megabyte stor. Webbplatsen fick väldigt bra resultat för dator men enbart 23 för mobil. Enligt pagespeed så bör webbplatsen skjuta upp inläsningen av bilder som inte visas på skärmen samt skicka bilderna i modernare filformat.

###Reddit
[FIGURE src="image/hemsidor/reddit.png"?w=300 class="right" caption="Startsida för reddit."]
Reddit är en väldigt stor webbplats på hela 19mb och inladdningen tar i snitt nio sekunder. Reddit får av pagespeed betyget 51 för mobiler vilket är det bästa av de tre sidorna. Webbplatsen kan förbättras genom att skicka bilderna i rätt storlek samt att skjuta upp inläsningen av JavaScript-kod som inte används direkt.

###Svt Play
[FIGURE src="image/hemsidor/svtplay.jpg"?w=300 class="right" caption="Startsida för Svt Play."]
SvtPlay laddades in på circa 1.7 sekunder och var 2.3mb stor. Webbplatsen får bra betyg för dator men dåligt för mobil. För att förbättras så rekommenderas det att inladdningen bilder som inte visas på skärmen skjuts upp tills allt annat har laddats.

Analys
-----------------------
Den vanligaste förbättringen för att en webbplats ska laddas snabbare verkar vara att inläsningen av bilder och kod som inte används direkt ska skjutas på tills allt annat är färdigladdat. Baserat på datainsamlingen från pagespeed så vinner reddit följt av SvtPlay och sist kommer ICA. SvtPlay har dock en väldigt imponerande laddningstid vilket troligen har med upplösningen av bilderna att göra. Användare kan själva ladda upp bilder i vilken storlek som helst på reddit vilket gör att laddningstiden påverkas av det. Men baserat på laddningstiden och värdena på pagespeed så dras slutsatsen att SvtPlay vinner, reddit två och ICA.se trea.

##Personlig slutsats
En rimlig gräns på laddningstiden innan en användare lämnar den känns personligen av mig som fyra sekunder. Det beror givetvis på vilken sida som jag besöker, är det en sida som jag besöker dagligen så kan jag vänta lite extra men är det en webbplats som jag tillexempel hittat efter en google-sökning så är jag lite mer kräsen. Jag tycker att webbplatserna i den här rapporten gör helt okej ifrån sig. Det tar ett tag för reddit att ladda men samtidigt så brukar inte så mycket annat behöva laddas in efter att “grunden” har laddats in.  

Övrigt
-----------------------
Skriven av Oscar Lang.
