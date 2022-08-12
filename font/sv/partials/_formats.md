---
translation: true
deploy: false
---


{{<section TTF>}}

TrueType Font-format eller TTF är nu det mest populära. Detta format utvecklades först av Apple och numera används det i Microsoft och Apples operativsystem. TTF-teckensnittet använder speciella tekniker för att tillhandahålla högkvalitativ rendering av teckensnittet på enheter med låg skärmupplösning. Den använder det utvecklade verktyget med instruktioner som tillåter typsnitt att ha liknande bitmappsteckensnitts kvalitet.

{{<section WOFF>}}

Web Open Font Format eller WOFF utvecklades 2009 för att täcka behoven på webbapplikationsmarknaden genom att lägga till formatspecifik komprimering till TrueType och OpenType-teckensnitt. Den använder zlib-komprimering som ger typsnitt cirka 40% komprimering. En annan egenhet med WOFF-format är att formatets teckensnitt kan inkludera bifogad ytterligare metadata. Denna metadata påverkar inte hur teckensnittet renderas, men kan visas för en användare när det behövs.

{{<section WOFF2>}}

Web Open Font Format 2 eller WOFF2 är nästa version av WOFF-formatet med bättre komprimering. För att vara exakt ger det en 30% fördel i komprimering jämfört med WOFF-format. Den använder byte-nivå komprimeringsalgoritmen Brotli, som är ett bibliotek för datakomprimering med öppen källkod. Det används för att påskynda laddningen av webbsidor. Som WOFF-format stöds WOFF2 också av de flesta webbläsare.

{{<section TYPE1>}}

Typ 1-format kom på marknaden tillsammans med PostScript-programmeringsspråket 1984 så formatet kallas även Postscript Type 1. Det är en speciell form av programmet Postscript och filformatet, som är inriktat på att beskriva typsnittet. Typ 1-format känns igen av skrivare och datorer, antingen av inbyggda tolkar eller av ytterligare verktyg som Adobe Type Manager. Teckensnitten stöder inte Unicode-kodningsstandarder.

{{<section EOT>}}

Inbäddat OpenType- eller EOT-format. Det är ett kompakt format av OpenType-teckensnitt inbäddade i webbsidor. Genom att använda LZ-komprimering och endast inkludera nödvändiga tecken i ett teckensnitt, är OpenType-filer kompakta. Teckensnittet gör det möjligt att förhindra teckensnittsupphovsrättsbrott och är alltid läsbart eftersom det använder reservteckensnitt.

{{<section CFF>}}

Kompakt teckensnittsformat eller CFF är också känt som typ 2 teckensnittsformat, eller CFF/typ 2 teckensnitt. Det sägs att CFF inte precis är typsnittsformatet utan sättet att komprimera andra typsnittsformat, som typ 1. Precis som typ 1- och TrueType-format använder CFF också antydningar. Den använder samma metoder för att representera tips som typ 1, men de är enklare och renare att skriva i kod och ger en anmärkningsvärd utrymmesbesparing.

{{<section OTF>}}

OpenType Font eller OTF skapades på basen och tog sin grundläggande struktur från TrueType. Till detta lades ytterligare datakonstruktioner för att ordna det typografiska beteendet. Formatet är känt som en kombination av TrueType- och Postscript-teckensnitt. Eftersom det är väldigt flexibelt stöds det av de flesta operativsystem och enheter. Som TTF är OTF också helt skalad utan att tappa kvaliteten.