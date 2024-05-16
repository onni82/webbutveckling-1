# Introduktion

Denna presentation handlar om tillgänglighet i webbapplikationer.

Tillgänglighet i sammanhanget av webbapplikationer handlar om att säkerställa att personer med olika förmågor och behov kan använda och ta del av webbapplikationer på ett effektivt och jämlikt sätt. Det innebär att göra webbapplikationer tillgängliga för personer med funktionsnedsättningar såsom synnedsättning, hörselnedsättning, rörelsebegränsningar eller kognitiva svårigheter.

En annan del som tillhör anpassning av tillgänglighet är att man anpassar efter mjukvara och hårdvara.

## Teknisk anpassning

Att säkerställa att en applikation är oberoende av användaragent, operativsystem och hårdvaruplattform innebär att applikationen ska fungera lika bra oavsett vilken webbläsare, vilket operativsystem eller vilken enhet användaren använder. Det innebär att användaren ska ha en enhetlig upplevelse och att applikationen ska vara robust nog att fungera på olika plattformar utan att kräva anpassningar för varje enskild miljö.

Exempel på hur detta kan uppnås med standarder som HTML, CSS och JavaScript inkluderar:

 * Semantisk HTML: Genom att använda semantisk HTML-kod kan du säkerställa att innehållet är tydligt strukturerat och meningsfullt för både användare och webbläsare. Detta hjälper till att säkerställa att innehållet visas korrekt på olika enheter och webbläsare.

 * Responsiv design med CSS: Genom att använda CSS för responsiv design kan du skapa layouter som anpassar sig dynamiskt baserat på skärmstorlek och enhetstyp. Detta gör att applikationen kan anpassa sig till olika enheter, från stora skrivbordsskärmar till små mobila skärmar, utan att behöva skapa separata versioner för varje enhet.

 * Progressiv förbättring med JavaScript: I stället för att förlita sig på avancerade JavaScript-funktioner som kanske inte stöds av alla webbläsare eller enheter, bör du implementera funktioner med progressiv förbättring. Det innebär att applikationen fungerar grundläggande även utan JavaScript, och mer avancerade funktioner läggs till gradvis för användare med moderna webbläsare och enheter som kan hantera dem.

 * Webstandarder och kompatibilitetstester: Genom att följa webbstandarder och genomföra kompatibilitetstester på olika webbläsare och enheter kan du säkerställa att din applikation fungerar korrekt över olika plattformar. Detta innebär att du bör undvika användning av webbläsarspecifika funktioner eller egenskaper som kan orsaka problem på andra plattformar.

Genom att följa dessa principer och använda standarder som HTML, CSS och JavaScript kan du skapa webbapplikationer som är oberoende av användaragent, operativsystem och hårdvaruplattform och som ger en enhetlig och robust användarupplevelse för alla användare.

## Användaranpassning

Tillgänglighet för användare med funktionsnedsättning innebär att säkerställa att webbapplikationer är utformade och implementerade på ett sätt som gör dem användbara och tillgängliga för alla, oavsett deras förmågor eller funktionsnedsättningar. Det handlar om att eliminera hinder och skapa en inkluderande miljö där alla användare kan få åtkomst till information, interaktion och funktioner på lika villkor.

Här är några exempel på tekniker som kan användas för att göra en webbapplikation mer tillgänglig:

 * Alternativ text för bilder: Att tillhandahålla alternativ text för bilder gör det möjligt för användare med synnedsättning att förstå och tolka innehållet på webbplatsen genom skärmläsare. Alternativ text beskriver vad bilden föreställer och bör vara kort och beskrivande.

 * Beskrivande länkar: I stället för att använda generiska länktexter som "klicka här" eller "läs mer", bör länktexten vara beskrivande och tydligt förklara var länken leder till. Detta hjälper användare med skärmläsare att förstå syftet med länken utan att behöva navigera till den.

 * Användning av ARIA-attribut: ARIA (Accessible Rich Internet Applications) är en uppsättning attribut som används för att förbättra tillgängligheten för interaktiva element och dynamiskt innehåll. Genom att använda ARIA-attribut kan utvecklare tillhandahålla ytterligare information till skärmläsare om hur olika komponenter i webbapplikationen fungerar.

 * Tillgängliga formulär: Att utforma formulär på ett sätt som gör dem användbara för alla användare, inklusive de med rörelsebegränsningar eller kognitiva svårigheter. Detta kan inkludera användning av tydliga och lättförståeliga instruktioner, tillräckligt stora klickbara områden och användning av rätt HTML-element för formulärfält.

 * Tillgänglig navigering: Att se till att navigeringen på webbapplikationen är logisk, konsekvent och enkel att använda för alla användare. Det kan innefatta användning av huvudrubriker, sidlänkar och tillbaka till toppen-knappar för att underlätta navigeringen, särskilt för användare som använder tangentbordet i stället för musen.

Genom att integrera dessa tekniker och principer för tillgänglighet i utvecklingen av webbapplikationer kan man säkerställa att alla användare, inklusive de med funktionsnedsättningar, kan få tillgång till och använda applikationen på ett effektivt och meningsfullt sätt.
