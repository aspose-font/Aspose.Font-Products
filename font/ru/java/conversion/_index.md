---
translation: true
template: /_templates/conversion-java.md
title: API преобразования шрифтов | Ява
url: /java/conversion/
description: Функциональность преобразования файлов шрифтов Java. Преобразуйте различные шрифты, такие как CFF, EOT, WOFF, TTF и Type 1, с помощью нескольких строк кода Java.
keywords: конвертировать шрифты java, конвертировать шрифты java, обложка шрифтов java
family: font
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: Конвертировать шрифты
h2: API конвертера форматов шрифтов для Java. Конвертируйте шрифты WOFF2, TTF, EOT и CFF.
---

{{<section overview>}}
---
p1: Font API Java может легко загружать, сохранять и преобразовывать различные шрифты, такие как коллекции CFF, OpenType, Type1 и TrueType. Он предоставляет структуру данных шрифта вместе с любым глифом, а также информацию о кодировании для всех типов шрифтов, представляющую сопоставление между кодами символов и идентификаторами глифа. API может отображать любой желаемый глиф или текст, а также специальные глифы, которые можно отображать путем реализации интерфейсов с использованием простых графических функций, таких как перемещение точки, рисование линии, кривой и т. д.
p2: "Из-за разнообразия гаджетов, сред, нескольких операционных систем и многих других областей использование разных форматов шрифтов для разных целей, таких как использование разных шрифтов на веб-страницах, в приложениях и публикациях. Иногда возникает необходимость преобразовать один шрифт в другой для соответствия требуемому отображению."
p3: "Мы предлагаем вам решение Java Api, которое поддерживает следующие шрифты в качестве выходных форматов: TrueType (TTF), Web Open Font Format (WOFF и WOFF2), встроенный формат OpenType (EOT), Type 1 и Compact Font Format (CFF)."
---

{{<section feature1>}}
---
title: Преобразование шрифта TrueType в формат веб-открытого шрифта версии 2.0.
item1: API поддерживает разные шрифты для чтения и письма, вот [список](https://docs.aspose.com/font/java/convert/#formats-supported-for-reading-andor-writing) для чтения и письма. Для рассмотрения преобразования TTF в WOFF2 процесс заключается в загрузке шрифта из любого из поддерживаемых форматов, шрифта TrueType для текущего сценария. Используйте метод [*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) of [Font class](https://reference.aspose.com/font/java/com.aspose.font/Font#save-java.lang.String-) с двумя потоками вывода параметров и [*FontSavingFormats*](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) Перечисление для выбора выходного формата шрифта.
item2: Наконец, вызовите SaveToFormat(), чтобы сохранить шрифты в любом из поддерживаемых выходных форматов, в настоящее время это формат Web Open Font Format версии 2.0 WOFF2.
item3: Чтобы увидеть, как эта функциональность реализована в реальном кросс-платформенном приложении, перейдите в [приложение Aspose Font Converter](https://products.aspose.app/font/conversion). Там же можно найти множество других [API-решений](https://products.aspose.app/font/applications) для работы со шрифтами и текстом.
item4: Перейдите в [Документацию](https://docs.aspose.com/font/net/), чтобы получить всю необходимую информацию для начала работы с решением, например, учебные пособия по основным функциям или набор статей для обучения. о шрифте, примечания к выпуску, руководство разработчика и другие полезные вещи.
---

{{<section codeexample>}}
---
title: Код Java для преобразования CFF в TTF
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