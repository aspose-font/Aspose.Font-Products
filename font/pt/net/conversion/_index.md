---
translation: true
template: /_templates/conversion-net.md
title: API de conversão de fontes | .INTERNET
url: /net/conversion/
description: Funcionalidade de conversão de fontes. Converta diferentes fontes como CFF, EOT, WOFF, TTF e Type 1 com algumas linhas de código C# por meio da biblioteca .NET.
keywords: conversor de fontes .net, conversor de fontes net, cobertura de fontes c#
family: font
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Converter fontes via C#
h2: API do conversor de formato de fonte para .NET. Converta fontes WOFF2, TTF, EOT e CFF.
---

{{<section overview>}}
---
p1: A API de fonte .NET pode facilmente carregar, salvar e converter fontes diferentes, como coleções CFF, OpenType, Type1 e TrueType. Ele fornece estrutura de dados de fonte junto com qualquer glifo, bem como informações de codificação para todos os tipos de fonte, representando um mapeamento entre códigos de caracteres e identificadores de glifo. A API pode renderizar qualquer glifo ou texto desejado, bem como glifos especiais, que podem ser renderizados implementando interfaces usando funcionalidades gráficas simples, como ponto de movimento, linha de desenho e curva, etc.
p2: "Devido à natureza diversa de gadgets, ambientes, alguns sistemas operacionais e muitas outras áreas, use formatos de fonte diferentes para atender a propósitos diferentes, como usar fontes diferentes em páginas da Web, aplicativos e publicações. Às vezes há a necessidade de transformar uma fonte em outra para atender a exibição necessária."
p3: "A solução aqui suporta as próximas fontes como formatos de saída: TrueType (TTF), Web Open Font Format (WOFF e WOFF2), Embedded OpenType format (EOT), Type 1 e Compact Font Format (CFF)."
---

{{<section feature1>}}
---
title: Fonte TrueType para Web Open Font Format versão 2.0 Conversão.
item1: A API suporta diferentes fontes para leitura e escrita, aqui está a [lista](https://docs.aspose.com/font/net/convert/#formats-supported-for-reading-andor-writing) para leitura e escrita. Para considerar a conversão de TTF para WOFF2, o processo é carregar uma fonte de qualquer um dos formatos suportados, TrueType Font para o cenário atual. Use o método [*SaveToFormat()*](https://reference.aspose.com/font/net/aspose.font/font/methods/savetoformat) com dois parâmetros de fluxo de saída e [*FontSavingFormats*](https://reference.aspose.com/font/net/aspose.font/fontsavingformats) Enumeração para selecionar o formato da fonte de saída.
item2: Finalmente, chame SaveToFormat() para salvar fontes em qualquer um dos formatos de saída suportados, atualmente o formato Web Open Font Format versão 2.0 WOFF2.
item3: Para ver essa funcionalidade realizada em um aplicativo multiplataforma real, acesse [Aplicativo Aspose Font Converter](https://products.aspose.app/font/conversion). Lá você também pode encontrar muito mais [soluções de API](https://products.aspose.app/font/applications) para trabalhar com fontes e texto.
item4: Acesse a [Documentação](https://docs.aspose.com/font/net/) para obter todas as informações necessárias para começar a trabalhar com a solução, como os Tutoriais para os principais recursos ou o conjunto de artigos para ensiná-lo sobre fonte, notas de versão, guia do desenvolvedor e outras coisas úteis.
---

{{<section codeexample>}}
---
title: Exemplo de código C# conversão de TTF para WOFF2
---
