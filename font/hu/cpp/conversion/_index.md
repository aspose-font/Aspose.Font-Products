---
translation: true
template: /_templates/conversion-cpp.md
title: Betűtípusok átalakítása | C++
url: /cpp/conversion/
description: Betűtípusok konvertálása a C++ Font feldolgozó könyvtárral és webalkalmazásokkal. Konverziós funkció, amely TTF, WOFF, CFF, EOT és Type 1 betűtípusokkal működik.
metakeywords: c++ font konverzió, font konverziós megoldások c++, font conerter cpp
family: font
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Betűtípusok konvertálása
h2: Betűformátum-átalakító API a С++-hoz. Konvertálja a WOFF2, TTF, EOT és CFF betűtípusokat.
---

{{<section overview>}}
---
p1: A С++ font API könnyen betölthet, menthet és konvertálhat különböző betűtípusokat, például CFF, OpenType, Type1 és TrueType gyűjteményeket. Betűtípus-adatszerkezetet biztosít bármely karakterjellel együtt, valamint kódolási információkat minden betűtípushoz, amelyek a karakterkódok és a karakterjel-azonosítók közötti leképezést jelentik. Az API bármilyen kívánt karakterjelet vagy szöveget, valamint speciális karakterjeleket tud előállítani, amelyek egyszerű grafikus funkciókkal, például mozgatási ponttal, vonallal és görbével stb.
p2: "A kütyük, környezetek, néhány operációs rendszer és sok más terület sokfélesége miatt különböző betűformátumokat kell használni különböző célokra, például különböző betűtípusok használata weboldalakon, alkalmazásokban és közzétételben. Néha szükség van az egyik betűtípust egy másikra átalakítani, hogy megfeleljen a kívánt megjelenítésnek."
p3: "Kínálunk Önnek egy С++ Api megoldást, amely a következő betűtípusokat támogatja kimeneti formátumként: TrueType (TTF), Web Open Font Format (WOFF és WOFF2), Embedded OpenType formátum (EOT), Type 1 és Compact Font Format (CFF)."
---

{{<section feature1>}}
---
title: TrueType Font Web Open Font Format 2.0 verzió átalakítása.
item1: Az API különböző betűtípusokat támogat olvasáshoz és íráshoz, itt található a [lista](https://docs.aspose.com/font/cpp/convert/#formats-supported-for-reading-andor-writing) az olvasáshoz és az íráshoz. A TTF-ből WOFF2-be való átalakítás megfontolásához a folyamat az, hogy betölt egy betűtípust a támogatott formátumok bármelyikéből, az aktuális forgatókönyvnek megfelelő TrueType betűtípusból. Használja a [*SaveToFormat()*](https://reference.aspose.com/font/cpp/class/aspose.font.font#a670ea97404fd72c2e51b0e8c543c8a45) metódust, amely két paraméteres kimeneti adatfolyamot és [*FontFormat*](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74) Felsorolás a kimeneti betűtípus kiválasztásához.
item2: Végül hívja meg a SaveToFormat()-t, hogy a betűtípusokat a támogatott kimeneti formátumok bármelyikébe mentse, jelenleg a Web Open Font Format 2.0 verziójú WOFF2 formátumba.
item3: Ha meg szeretné tekinteni ezt a funkciót egy tényleges, többplatformos alkalmazásban, keresse fel az [Aspose Font Converter alkalmazást](https://products.aspose.app/font/conversion). Ezen kívül számos további [API-megoldást](https://products.aspose.app/font/applications) találhat a betűtípusok és szövegek kezelésére.
item4: Látogasson el a [Dokumentáció](https://docs.aspose.com/font/net/) oldalra, ahol megtalálja a megoldással való munka megkezdéséhez szükséges összes információt, például a főbb funkciókról szóló oktatóanyagokat vagy a megtanító cikkeket. a betűtípusról, a Kiadási megjegyzésekről, a Fejlesztői útmutatóról és más hasznos dolgokról.
---

{{<section codeexample>}}
---
title: C++ kód példa TTF konvertálás WOFF2-re
---



