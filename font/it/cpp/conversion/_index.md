---
translation: true
template: /_templates/conversion-cpp.md
title: Conversione caratteri | C++
url: /cpp/conversion/
description: Converti i caratteri con la libreria di elaborazione dei caratteri C++ e le applicazioni Web. Funzionalità di conversione che può funzionare con i caratteri TTF, WOFF, CFF, EOT e Type 1.
metakeywords: conversione dei font c++, soluzioni di conversione dei font c++, font conerter cpp
family: font
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Converti caratteri
h2: API di conversione del formato dei caratteri per С++. Converti i caratteri WOFF2, TTF, EOT e CFF.
---

{{<section overview>}}
---
p1: L'API dei font С++ può facilmente caricare, salvare e convertire diversi font come raccolte CFF, OpenType, Type1 e TrueType. Fornisce la struttura dei dati dei caratteri insieme a qualsiasi glifo e le informazioni di codifica per tutti i tipi di carattere che rappresentano una mappatura tra codici carattere e identificatori di glifi. L'API può eseguire il rendering di qualsiasi glifo o testo desiderato, nonché glifi speciali, che possono essere resi implementando interfacce utilizzando semplici funzionalità grafiche come spostare il punto, disegnare una linea e una curva, ecc.
p2: "A causa della diversa natura di gadget, ambienti, alcuni sistemi operativi e molte altre aree, è possibile utilizzare formati di caratteri diversi per scopi diversi, ad esempio l'utilizzo di caratteri diversi su pagine Web, applicazioni e pubblicazioni. A volte è necessario trasformare un font in un altro per soddisfare la visualizzazione richiesta."
p3: "Ti offriamo С++ Api Solution che supporta i seguenti font come formati di output: TrueType (TTF), Web Open Font Format (WOFF e WOFF2), Embedded OpenType format (EOT), Type 1 e Compact Font Format (CFF)."
---

{{<section feature1>}}
---
title: TrueType Font to Web Open Font Format versione 2.0 Conversione.
item1: L'API supporta diversi tipi di carattere per la lettura e la scrittura, ecco la [list](https://docs.aspose.com/font/cpp/convert/#formats-supported-for-reading-andor-writing) per la lettura e la scrittura. Per considerare la conversione da TTF a WOFF2, il processo consiste nel caricare un font da uno qualsiasi dei formati supportati, TrueType Font per lo scenario corrente. Utilizzare il metodo [*SaveToFormat()*](https://reference.aspose.com/font/cpp/class/aspose.font.font#a670ea97404fd72c2e51b0e8c543c8a45) con due parametri flusso di output e [*FontSavingFormats*](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74) Enumerazione per la selezione del formato del carattere di output.
item2: Infine, chiama SaveToFormat() per salvare i caratteri in uno qualsiasi dei formati di output supportati, attualmente formato WOFF2 Web Open Font Format versione 2.0.
item3: Per vedere questa funzionalità realizzata in un'effettiva applicazione multipiattaforma, vai su [App Aspose Font Converter](https://products.aspose.app/font/conversion). Lì puoi anche trovare molte altre [soluzioni API](https://products.aspose.app/font/applications) per lavorare con caratteri e testo.
item4: Vai alla [Documentazione](https://docs.aspose.com/font/net/) per ottenere tutte le informazioni necessarie per iniziare a lavorare con la soluzione, come i Tutorial per le caratteristiche principali o la serie di articoli da insegnarti su font, note di rilascio, guida per gli sviluppatori e altre cose utili.
---

{{<section codeexample>}}
---
title: Esempio di codice C++ Conversione da TTF a WOFF2
---



