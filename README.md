# FJSX24Bootcamp

Det här är kurs 1 som kallas för Bootcamp på Chas Academy

Onsdag 11/9: Workshop - Semantisk HTML, CSS

Praktiska övningar: Omvandla en befintlig HTML-sida till en mer semantisk struktur genom att använda rätt element. Lägg till grundläggande CSS för att förbättra layouten (t.ex. centrera innehållet, ändra avstånd, typsnittsstyling).

Utgångspunkt: HTML-kod utan semantiska element: html Kopiera kod

<title>My Webpage</title> <style> body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
div {
  padding: 20px;
  margin: 10px;
}

.header {
background-color: #333;
color: white;
text-align: center;
}

.content {
background-color: white;
}

.footer {
background-color: #333;
color: white;
text-align: center;
}
</style>
Welcome to My Webpage
Home | About | Contact

About Me
This is some information about me. I am a web developer who loves creating websites.

Footer information goes here

Studenternas uppgift: Omvandla strukturen till en semantisk HTML-struktur genom att byta ut

-taggar mot mer meningsfulla element som , ,
, och . Lägg till CSS för att centrera innehållet, förbättra layouten, och ändra typsnittsstyling.
Avancerad Övning: "Skapa en bloggpost med semantisk HTML och tillgänglighetsförbättringar" Mål: Eleverna ska skapa en semantiskt korrekt blogginläggsstruktur, inkludera tillgänglighetsattribut och arbeta med SEO-vänliga element som förbättrar sidans struktur och synlighet i sökmotorer.

Uppgifter: Skapa en semantisk bloggpost:

Använd semantiska element för att skapa en blogginläggsstruktur som innehåller följande delar: Rubrik: Använd

för blogginläggets rubrik och författarinformation. Innehåll: Använd för huvudtexten. Bild: Inkludera en bild i inlägget med en beskrivande text med hjälp av och . Kommentarer: Använd
för att lägga till en kommentaravdelning, där varje kommentar är en egen . Footer: Använd i varje kommentar och i blogginlägget för att visa publiceringsdatum och eventuellt länkar till sociala medier. Tillgänglighetsförbättringar:
Inkludera aria-label och andra ARIA-attribut där det är lämpligt för att förbättra tillgängligheten, till exempel för kommentarsavsnittet eller för förklarande text till bilder. Använd alt-attribut för alla bilder och se till att alla interaktiva element som länkar och knappar är tydliga och tillgängliga för skärmläsare. SEO-förbättringar:

Använd korrekt rubrikstruktur (

för blogginläggets titel,
och
för underrubriker) för att förbättra sidans hierarki och läsbarhet för sökmotorer. Använd metadata i -delen (t.ex. ). Inkludera strukturerad data med hjälp av schema.org (valfritt för mer avancerade elever) för att ge sökmotorer ytterligare information om sidan (t.ex. författare, datum, och ämne).
Vanliga Semantiska HTML-element:

Beskrivning: Används för att definiera sidhuvudet för en webbsida eller en sektion. Innehåller vanligtvis navigeringslänkar, logotyper eller rubriker. Tillgänglighet: Hjälper skärmläsare att identifiera och navigera i sidhuvudet, vilket underlättar orienteringen på sidan. SEO: Ger sökmotorer en tydlig signal om att detta är sidhuvudet, vilket kan förbättra sidans struktur och hierarki.

Beskrivning: Markerar en sektion som innehåller navigeringslänkar till andra sidor eller delar av sidan. Tillgänglighet: Skärmläsare kan snabbt hoppa till och navigera genom navigeringslänkar, vilket underlättar navigation för användare med funktionsnedsättningar. SEO: Sökmotorer förstår att detta område innehåller viktiga länkar, vilket kan hjälpa till med sidindexering och användarupplevelse.

Beskrivning: Anger huvudinnehållet på en webbsida, vilket ska vara unikt för varje sida. Tillgänglighet: Skärmläsare kan hoppa direkt till huvudinnehållet, vilket förbättrar användbarheten för de som använder hjälpmedel. SEO: Genom att definiera det viktigaste innehållet, hjälper detta sökmotorer att förstå vad sidan handlar om.

Beskrivning: Representerar ett självständigt innehåll som kan distribueras eller återanvändas, som en blogginlägg, tidningsartikel eller foruminlägg. Tillgänglighet: Gör det enklare för skärmläsare att skilja mellan olika sektioner av innehåll. SEO: Sökmotorer kan lättare förstå att detta är en separat informationsenhet, vilket kan förbättra sidans indexering.

Beskrivning: Används för att definiera en sektion eller ett tema inom en sida, som en avdelning med relaterat innehåll. Tillgänglighet: Skärmläsare kan snabbt identifiera och hoppa mellan olika sektioner, vilket gör det enklare att navigera. SEO: Organiserar innehållet i tydliga sektioner, vilket kan förbättra sökmotorernas förståelse för sidans struktur.

Beskrivning: Representerar sidoinnehåll eller innehåll som är relaterat till huvudinnehållet, som en sidopanel eller relaterade länkar. Tillgänglighet: Hjälper skärmläsare att förstå att detta innehåll är sekundärt till det huvudsakliga innehållet. SEO: Sökmotorer vet att detta är mindre centralt för sidans innehåll men kan fortfarande vara relevant för användaren.

Beskrivning: Används för att definiera sidans eller sektionens sidfot, som ofta innehåller information som copyright, länkar till kontaktinformation eller annan nödvändig information. Tillgänglighet: Skärmläsare kan identifiera sidfoten och låta användare snabbt hoppa till den. SEO: Ger sökmotorer en signal om att detta är sidans slut och kan innehålla relevanta länkar och information.

till
Beskrivning: Rubriker används för att definiera hierarkin av innehåll på en sida, från huvudrubriken (

) till underrubriker (
,
, etc.). Tillgänglighet: Hjälper skärmläsare att navigera och förstå strukturen på sidan, så att användare kan hoppa mellan rubriker. SEO: Sökmotorer använder rubriker för att förstå hierarkin och vikten av olika delar av innehållet. En korrekt struktur förbättrar sökmotorns förståelse.
och
Beskrivning:

används för att gruppera visuellt media som bilder och diagram, medan ger en förklaring till bilden eller figuren. Tillgänglighet: Skärmläsare kan läsa upp beskrivningen för användare, vilket gör visuellt innehåll mer tillgängligt. SEO: Sökmotorer kan bättre förstå och indexera bildinnehåll, särskilt om det åtföljs av en meningsfull beskrivning.
Beskrivning: Markerar text som är av särskild vikt eller som ska betonas. Tillgänglighet: Skärmläsare läser markerad text med extra betoning, vilket kan förbättra förståelsen för användare. SEO: Genom att använda kan du lyfta fram viktig information, vilket kan bidra till bättre användarupplevelse och sökmotorns förståelse för viktiga delar av texten.

Beskrivning: Representerar en tidsangivelse eller ett datum. Tillgänglighet: Hjälper skärmläsare att läsa upp datum och tider korrekt, vilket förbättrar användarupplevelsen. SEO: Sökmotorer kan förstå och indexera tidsstämplar bättre, vilket kan vara viktigt för nyhetsinnehåll eller bloggar. Mindre vanliga semantiska element:

och
Detaljer
