---
translation: true
template: /_templates/conversion-java.md
title: API de conversão de fontes | Java
url: /java/conversion/
description: Funcionalidade de conversão de arquivos de fonte Java. Converta diferentes fontes como CFF, EOT, WOFF, TTF e Type 1 com algumas linhas de código Java.
keywords: converter fontes java, conversão de fontes Java, fonte coverter java
family: font
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: Converter fontes
h2: API do conversor de formato de fonte para Java. Converta fontes WOFF2, TTF, EOT e CFF.
---

{{<section overview>}}
---
p1: A API de fonte Java pode facilmente carregar, salvar e converter fontes diferentes, como coleções CFF, OpenType, Type1 e TrueType. Ele fornece estrutura de dados de fonte junto com qualquer glifo, bem como informações de codificação para todos os tipos de fonte, representando um mapeamento entre códigos de caracteres e identificadores de glifo. A API pode renderizar qualquer glifo ou texto desejado, bem como glifos especiais, que podem ser renderizados implementando interfaces usando funcionalidades gráficas simples, como ponto de movimento, linha de desenho e curva, etc.
p2: "Devido à natureza diversa de gadgets, ambientes, alguns sistemas operacionais e muitas outras áreas, use formatos de fonte diferentes para atender a propósitos diferentes, como usar fontes diferentes em páginas da Web, aplicativos e publicações. Às vezes há a necessidade de transformar uma fonte em outra para atender a exibição necessária."
p3: "Oferecemos a você Java Api Solution que suporta as próximas fontes como formatos de saída: TrueType (TTF), Web Open Font Format (WOFF e WOFF2), Embedded OpenType format (EOT), Type 1 e Compact Font Format (CFF)."
---

{{<section feature1>}}
---
title: Fonte TrueType para Web Open Font Format versão 2.0 Conversão.
item1: A API suporta diferentes fontes para leitura e escrita, aqui está a [lista](https://docs.aspose.com/font/java/convert/#formats-supported-for-reading-andor-writing) para leitura e escrita. Para considerar a conversão de TTF para WOFF2, o processo é carregar uma fonte de qualquer um dos formatos suportados, TrueType Font para o cenário atual. Use o método [*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) de [Font class](https://reference.aspose.com/font/java/com.aspose.font/Font#save-java.lang.String-) com fluxo de saída de dois parâmetros e [*FontSavingFormats*](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) Enumeração para selecionar o formato da fonte de saída.
item2: Finalmente, chame SaveToFormat() para salvar fontes em qualquer um dos formatos de saída suportados, atualmente o formato Web Open Font Format versão 2.0 WOFF2.
item3: Para ver essa funcionalidade realizada em um aplicativo multiplataforma real, acesse [Aplicativo Aspose Font Converter](https://products.aspose.app/font/conversion). Lá você também pode encontrar muito mais [soluções de API](https://products.aspose.app/font/applications) para trabalhar com fontes e texto.
item4: Acesse a [Documentação](https://docs.aspose.com/font/net/) para obter todas as informações necessárias para começar a trabalhar com a solução, como os Tutoriais para os principais recursos ou o conjunto de artigos para ensiná-lo sobre fonte, notas de versão, guia do desenvolvedor e outras coisas úteis.
---

{{<section codeexample>}}
---
title: Código Java para conversão de CFF para TTF
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