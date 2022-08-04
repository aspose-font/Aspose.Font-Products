---
translation: true
template: /_templates/conversion-java.md
title: Font Conversion API | Jáva
url: /java/conversion/
description: Java Font Files Conversion funkció. Konvertálja a különböző betűtípusokat, például CFF, EOT, WOFF, TTF és Type 1 néhány soros Java kóddal.
keywords: fontok konvertálása java, font konverzió Java, font coverter java
family: font
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: Betűtípusok konvertálása
h2: Font format konverter API Java számára. Konvertálja a WOFF2, TTF, EOT és CFF betűtípusokat.
---

{{<section overview>}}
---
p1: A Java font API könnyen betölthet, menthet és konvertálhat különféle betűtípusokat, például CFF, OpenType, Type1 és TrueType gyűjteményeket. Betűtípus-adatszerkezetet biztosít bármely karakterjellel együtt, valamint kódolási információkat minden betűtípushoz, amelyek a karakterkódok és a karakterjel-azonosítók közötti leképezést jelentik. Az API bármilyen kívánt karakterjelet vagy szöveget, valamint speciális karakterjeleket tud előállítani, amelyek egyszerű grafikus funkciókkal, például mozgatási ponttal, vonallal és görbével stb.
p2: "A kütyük, környezetek, néhány operációs rendszer és sok más terület sokfélesége miatt különböző betűformátumokat kell használni különböző célokra, például különböző betűtípusok használata weboldalakon, alkalmazásokban és közzétételben. Néha szükség van az egyik betűtípust egy másikra átalakítani, hogy megfeleljen a kívánt megjelenítésnek."
p3: "Java Api megoldást kínálunk, amely a következő betűtípusokat támogatja kimeneti formátumként: TrueType (TTF), Web Open Font Format (WOFF és WOFF2), Embedded OpenType formátum (EOT), Type 1 és Compact Font Format (CFF)."
---

{{<section feature1>}}
---
title: TrueType Font Web Open Font Format 2.0 verzió átalakítása.
item1: Az API különböző betűtípusokat támogat olvasáshoz és íráshoz, itt található a [lista](https://docs.aspose.com/font/java/convert/#formats-supported-for-reading-andor-writing) az olvasáshoz és az íráshoz. A TTF-ből WOFF2-be való átalakítás megfontolásához a folyamat az, hogy betölt egy betűtípust a támogatott formátumok bármelyikéből, az aktuális forgatókönyvnek megfelelő TrueType betűtípusból. Használja a [*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) módszert a [*FontFormat*](https://reference.aspose.com/font/java/com.aspose.font/Font#save-java.lang.String-), amely két paraméteres kimeneti adatfolyammal és [*FontSavingFormats*](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) Felsorolás a kimeneti betűtípus kiválasztásához.
item2: Végül hívja meg a SaveToFormat()-t, hogy a betűtípusokat a támogatott kimeneti formátumok bármelyikébe mentse, jelenleg a Web Open Font Format 2.0 verziójú WOFF2 formátumba.
item3: Ha meg szeretné tekinteni ezt a funkciót egy tényleges, többplatformos alkalmazásban, keresse fel az [Aspose Font Converter alkalmazást](https://products.aspose.app/font/conversion). Ezen kívül számos további [API-megoldást](https://products.aspose.app/font/applications) találhat a betűtípusok és szövegek kezelésére.
item4: Látogasson el a [Dokumentáció](https://docs.aspose.com/font/net/) oldalra, ahol megtalálja a megoldással való munka megkezdéséhez szükséges összes információt, például a főbb funkciókról szóló oktatóanyagokat vagy a megtanító cikkeket. a betűtípusról, a Kiadási megjegyzésekről, a Fejlesztői útmutatóról és más hasznos dolgokról.
---

{{<section codeexample>}}
---
title: Java kód a CFF-ből TTF-be való konvertáláshoz
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/agp/feature-section >}}
{{< app/font/converter "Java Code for CFF to TTF Conversion" CFF TTF WOFF WOFF2>}}
    // Open {{input lower}} font
    String fontPath = Paths.get(getDataDir(), "{{inputFile}}").toString();
    FontDefinition fontDefinition = new FontDefinition(FontType.{{input upper}}, new FontFileDefinition({{input lower}}, new FileSystemStreamSource(fontPath)));
    Font font = Font.open(fontDefinition);

    // {{output camel}} output settings
    String outPath = Paths.get(getOutputDir(), "{{outputFile}}").toString();
    FileOutputStream outStream = new FileOutputStream(outPath);

    // Convert {{input lower}} to {{output lower}}
    font.SaveToFormat(outStream, FontSavingFormats.{{output upper}});
{{< /app/font/converter >}}
{{< /blocks/products/pf/agp/feature-section>}}
{{< /blocks/products/pf/main-wrap-class>}}

{{< blocks/products/pf/feature-page-options pairs="cff-to-ttf cff-to-woff cff-to-woff2 eot-to-ttf eot-to-woff eot-to-woff2 ttf-to-woff type1-to-ttf type1-to-woff type1-to-woff2 woff2-to-ttf woff2-to-woff woff-to-ttf woff-to-woff2" >}}