---
translation: true
template: /_templates/conversion-java.md
title: Rozhraní API pro konverzi písem | Jáva
url: /java/conversion/
description: Funkce konverze souborů písem Java. Převeďte různá písma, jako jsou CFF, EOT, WOFF, TTF a Type 1, pomocí několika řádků kódu Java.
keywords: konvertovat fonty java, font konverze Java, font coverter java
family: font
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: Převést písma
h2: Rozhraní API pro převod formátu písem pro Javu. Převeďte písma WOFF2, TTF, EOT a CFF.
---

{{<section overview>}}
---
p1: Java font API může snadno načítat, ukládat a převádět různá písma, jako jsou kolekce CFF, OpenType, Type1 a TrueType. Poskytuje datovou strukturu písem spolu s libovolným glyfem a také informace o kódování pro všechny typy písem představující mapování mezi kódy znaků a identifikátory glyfů. API dokáže vykreslit jakýkoli požadovaný glyf nebo text, stejně jako speciální glyfy, které lze vykreslit implementací rozhraní pomocí jednoduchých grafických funkcí, jako je přesun bodu, kreslení čáry a křivky atd.
p2: "Vzhledem k různorodé povaze gadgetů, prostředí, několika operačních systémů a mnoha dalších oblastí používat různé formáty písem pro různé účely, jako je použití různých písem na webových stránkách, aplikacích a publikování. Někdy je potřeba přeměnit jedno písmo na jiné, aby vyhovovalo požadovanému zobrazení."
p3: "Nabízíme vám řešení Java Api, které podporuje následující fonty jako výstupní formáty: TrueType (TTF), Web Open Font Format (WOFF a WOFF2), Embedded OpenType formát (EOT), Type 1 a Compact Font Format (CFF)."
---

{{<section feature1>}}
---
title: Převod TrueType Font na Web Open Font Format verze 2.0.
item1: API podporuje různá písma pro čtení a zápis, zde je [seznam](https://docs.aspose.com/font/java/convert/#formats-supported-for-reading-andor-writing) pro čtení a zápis. Pro zvážení převodu TTF na WOFF2 je proces načíst písmo z libovolného z podporovaných formátů, pro aktuální scénář TrueType Font. Použijte metodu [*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) z [třídy písma](https://reference.aspose.com/font/java/com.aspose.font/Font#save-java.lang.String-) se dvěma parametry výstupního proudu a [*FontSavingFormats*](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) Výčet pro výběr výstupního formátu písma.
item2: Nakonec zavolejte SaveToFormat() pro uložení písem do libovolného z podporovaných výstupních formátů, aktuálně formátu Web Open Font Format verze 2.0 WOFF2.
item3: Chcete-li vidět tuto funkci realizovanou ve skutečné multiplatformní aplikaci, přejděte na [aplikaci Aspose Font Converter](https://products.aspose.app/font/conversion). Najdete zde také mnoho dalších [řešení API](https://products.aspose.app/font/applications) pro práci s písmy a textem.
item4: Přejděte na [Dokumentaci](https://docs.aspose.com/font/net/), kde získáte všechny potřebné informace, abyste mohli začít pracovat s řešením, jako jsou návody k hlavním funkcím nebo soubor článků, které vás naučí o písmu, poznámkách k verzi, příručce pro vývojáře a dalších užitečných věcech.
---

{{<section codeexample>}}
---
title: Java kód pro konverzi CFF na TTF
---