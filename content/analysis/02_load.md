---
Title: Loadspeed
Description: This is a page of analysis loadspeed
---

Rapport analys laddningshastighet
=======================

Genom att titta på hemsidor och jämföra olika laddningshastighet så kan man få ett hum om hur de är uppbyggda för att ge så snabb respons som möjligt oavsett storlek på innehållet som levereras.

Urval
-----------------------
Tre webbplatser har blivit utvalda för analys. Dessa valdes utifrån akutläge med skadat djur, sida jag använder dagligen och efter googling på: "fastest websites"

1. https://www.netonnet.se/
2. https://www.mjonasdjurklinik.se/
3. https://robinjescott.com/

Metod
-----------------------
Metoden som användes i analysen bestod av:
PageSpeed. Hemsida som kontrollerar olika faktorer i loadspeed.
Samt manuell kontroll iform av "Inspektera" i Google Chrome.

Resultat
-----------------------
##Resultat från GoogleDocs

<iframe class="iframe" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSm_dag5Gb5wBg6AqOVf1jE3I2TIVAF4N8jdA-1Gkmr_JES1kd8Xo-Kny0mykeN6XIMOpMnjou7-JWA/pubhtml?widget=true&amp;headers=false"></iframe>

##Netonnet
<picture>
  <source 
    srcset="%base_url%/image/hellomonday.jpg?width=80%"
    media="(min-width: 800px)"
  />
  <img 
    src="%base_url%/image/hellomonday.jpg?width=50%" 
    alt="Netonnet"
  />
</picture>


Mobilt så fick hemsidan endast 61/100 i poäng. Däremot läsning i dator så var hemsidan 98/100 vilket tydligt visar att man byggt hemsidan från början till dator och sedan anpassat till mobilt men förlorat mycket på vägen. Man ser att det laddas över ungefär hälften av vad resurserna är och slutför inom ganska lång tid 3.78 sekunder faktiskt vilket är lång tid om man jämför med de andra två. Inläsning var långsammare än de andra två också.

##Mjönäs
<picture>
  <source 
    srcset="%base_url%/image/mjonas.jpg?width=80%"
    media="(min-width: 800px)"
  />
  <img 
    src="%base_url%/image/mjonas.jpg?width=50%" 
    alt="Mjönäs"
  />
</picture>

Mobilt så fick den här webbsidan 63/100 vilket faktiskt är bättre än netonnet. Det är lite intressant eftersom Mjönäs sida känns mer komplicerad när man ser den. På dator förbättrades det något till 77/100 men finns fortfarande potential för förbättring. Framför allt kunde man se förbättring i att ta bort resurser som blockerar renderingen. Man ser att cirka 3/4 överförs utav resurserna och slutförs väsenligt snabbare än netonnet mindre än hälften av tiden från netonnet.

##RobinJeScott
<picture>
  <source 
    srcset="%base_url%/image/robinjescott.jpg?width=80%"
    media="(min-width: 800px)"
  />
  <img 
    src="%base_url%/image/robinjescott.jpg?width=50%" 
    alt="RobinJeScott"
  />
</picture>



Överlägset snabbaste webbsidan. Fick 97/100 för mobil och 98/100 för dator vilket är överlägset bäst med båda kategorierna som jämförelsevärden. Dock ser man att det inte är mycket som överförs. Cirka hälften på en knapp halv MB. Inläsningen är cirka hälften av Mjönäs vilket gör det till snabbaste sidan. Däremot var tiden för slutfört långsammare än för Mjönäs.

Analys
-----------------------
Det är viktigt att hemsidan är snabb. Allt ska renderas snabbt. Vid resultet syndes att det fanns totalt fyra punkter som stack ut i förbättringen.
1. Reducera CSS
2. Reducera JavaScript
3. Förbättra bildhantering/kvalitet
4. Ta bort resurser som blockerar renderingen

Samtliga av dessa fyra är något som en webbprogrammerare lätt kan åtgärda och fixa. Jag har fått feedback på att jag använt för mycket kod i en del fall vilket lätt kan förbättras genom att minska mängden kod för att snabba upp hemsidan.

###Vinnare
Överlägset vann RobinJeScott. Dock bygger hela hemsidan på att få så högt resultat som möjligt i pagespeed. I alla värden vann den dock inte.

###Max laddningstid
De hemsidor jag valt har fyllt mina krav på snabbhet vilket innebär att mitt max ligger runt 1.5 sekunder för läs in även om slutförd tar längre tid. Viktiga är att jag får se startsidan och kan börja leta efter vad jag behöver.

Referenser
-----------------------
https://pagespeed.web.dev/
https://www.netonnet.se/
https://www.mjonasdjurklinik.se/
https://robinjescott.com/

Övrigt
-----------------------

Analysen är utförd av Hampus Vingren 2021-12-02