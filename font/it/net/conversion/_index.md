---
translation: true
template: /_templates/conversion-net.md
title: API di conversione dei caratteri | .RETE
url: /net/conversion/
description: Funzionalità di conversione dei caratteri. Converti diversi tipi di carattere come CFF, EOT, WOFF, TTF e Type 1 con poche righe di codice C# tramite la libreria .NET.
keywords: convertitore di font .net, convertitore di font net, coversion di font c#
family: font
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Converti caratteri tramite C#
h2: API di conversione del formato dei caratteri per .NET. Converti i caratteri WOFF2, TTF, EOT e CFF.
---

{{<section overview>}}
---
p1: L'API dei caratteri .NET può caricare, salvare e convertire facilmente diversi tipi di carattere come le raccolte CFF, OpenType, Type1 e TrueType. Fornisce la struttura dei dati dei caratteri insieme a qualsiasi glifo e le informazioni di codifica per tutti i tipi di carattere che rappresentano una mappatura tra codici carattere e identificatori di glifi. L'API può eseguire il rendering di qualsiasi glifo o testo desiderato, nonché glifi speciali, che possono essere resi implementando interfacce utilizzando semplici funzionalità grafiche come spostare il punto, disegnare una linea e una curva, ecc.
p2: "A causa della diversa natura di gadget, ambienti, alcuni sistemi operativi e molte altre aree, è possibile utilizzare formati di caratteri diversi per scopi diversi, ad esempio l'utilizzo di caratteri diversi su pagine Web, applicazioni e pubblicazioni. A volte è necessario trasformare un font in un altro per soddisfare la visualizzazione richiesta."
p3: "La soluzione qui supporta i caratteri successivi come formati di output: TrueType (TTF), Web Open Font Format (WOFF e WOFF2), Embedded OpenType format (EOT), Type 1 e Compact Font Format (CFF)."
---

{{<section feature1>}}
---
title: TrueType Font to Web Open Font Format versione 2.0 Conversione.
item1: L'API supporta diversi tipi di carattere per la lettura e la scrittura, ecco la [list](https://docs.aspose.com/font/net/convert/#formats-supported-for-reading-andor-writing) per la lettura e la scrittura. Per considerare la conversione da TTF a WOFF2, il processo consiste nel caricare un font da uno qualsiasi dei formati supportati, TrueType Font per lo scenario corrente. Utilizzare il metodo [*SaveToFormat()*](https://apiference.aspose.com/font/net/aspose.font/font/methods/savetoformat) con due parametri flusso di output e [*FontSavingFormats*](https://reference.aspose.com/font/net/aspose.font/fontsavingformats) Enumerazione per la selezione del formato del carattere di output.
item2: Infine, chiama SaveToFormat() per salvare i caratteri in uno qualsiasi dei formati di output supportati, attualmente formato WOFF2 Web Open Font Format versione 2.0.
item3: Per vedere questa funzionalità realizzata in un'effettiva applicazione multipiattaforma, vai su [App Aspose Font Converter](https://products.aspose.app/font/conversion). Lì puoi anche trovare molte altre [soluzioni API](https://products.aspose.app/font/applications) per lavorare con caratteri e testo.
item4: Vai alla [Documentazione](https://docs.aspose.com/font/net/) per ottenere tutte le informazioni necessarie per iniziare a lavorare con la soluzione, come i Tutorial per le caratteristiche principali o la serie di articoli da insegnarti su font, note di rilascio, guida per gli sviluppatori e altre cose utili.
---

{{<section codeexample>}}
---
title: Esempio di codice C# Conversione da TTF a WOFF2
---
