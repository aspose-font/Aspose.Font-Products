---
translation: true
template: /_templates/conversion-java.md
title: API di conversione dei caratteri | Giava
url: /java/conversion/
description: Funzionalità di conversione dei file di font Java. Converti diversi tipi di carattere come CFF, EOT, WOFF, TTF e Type 1 con poche righe di codice Java.
keywords: converti font java, conversione font Java, font coverter java
family: font
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: Converti caratteri
h2: API di conversione del formato dei caratteri per Java. Converti i caratteri WOFF2, TTF, EOT e CFF.
---

{{<section overview>}}
---
p1: L'API dei font Java può facilmente caricare, salvare e convertire diversi font come raccolte CFF, OpenType, Type1 e TrueType. Fornisce la struttura dei dati dei caratteri insieme a qualsiasi glifo e le informazioni di codifica per tutti i tipi di carattere che rappresentano una mappatura tra codici carattere e identificatori di glifi. L'API può eseguire il rendering di qualsiasi glifo o testo desiderato, nonché glifi speciali, che possono essere resi implementando interfacce utilizzando semplici funzionalità grafiche come spostare il punto, disegnare una linea e una curva, ecc.
p2: "A causa della diversa natura di gadget, ambienti, alcuni sistemi operativi e molte altre aree, è possibile utilizzare formati di caratteri diversi per scopi diversi, ad esempio l'utilizzo di caratteri diversi su pagine Web, applicazioni e pubblicazioni. A volte è necessario trasformare un font in un altro per soddisfare la visualizzazione richiesta."
p3: "Ti offriamo Java Api Solution che supporta i seguenti font come formati di output: TrueType (TTF), Web Open Font Format (WOFF e WOFF2), Embedded OpenType format (EOT), Type 1 e Compact Font Format (CFF)."
---

{{<section feature1>}}
---
title: TrueType Font to Web Open Font Format versione 2.0 Conversione.
item1: L'API supporta diversi tipi di carattere per la lettura e la scrittura, ecco la [list](https://docs.aspose.com/font/java/convert/#formats-supported-for-reading-andor-writing) per la lettura e la scrittura. Per considerare la conversione da TTF a WOFF2, il processo consiste nel caricare un font da uno qualsiasi dei formati supportati, TrueType Font per lo scenario corrente. Utilizzare il metodo [*SaveToFormat()*](https://apiference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) di [Classe font](https://apiference.aspose.com/font/java/com.aspose.font/Font#save-java.lang.String-) con due parametri flusso di output e [*FontSavingFormats*](https://apiference.aspose.com/font/java/com.aspose.font/FontSavingFormats) Enumerazione per la selezione del formato del carattere di output.
item2: Infine, chiama SaveToFormat() per salvare i caratteri in uno qualsiasi dei formati di output supportati, attualmente formato WOFF2 Web Open Font Format versione 2.0.
item3: Per vedere questa funzionalità realizzata in un'effettiva applicazione multipiattaforma, vai su [App Aspose Font Converter](https://products.aspose.app/font/conversion). Lì puoi anche trovare molte altre [soluzioni API](https://products.aspose.app/font/applications) per lavorare con caratteri e testo.
item4: Vai alla [Documentazione](https://docs.aspose.com/font/net/) per ottenere tutte le informazioni necessarie per iniziare a lavorare con la soluzione, come i Tutorial per le caratteristiche principali o la serie di articoli da insegnarti su font, note di rilascio, guida per gli sviluppatori e altre cose utili.
---

{{<section codeexample>}}
---
title: Codice Java per la conversione da CFF a TTF
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