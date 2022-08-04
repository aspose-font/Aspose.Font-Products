---
translation: true
template: /_templates/conversion-java.md
title: フォント変換 API |ジャワ
url: /java/conversion/
description: Java フォント ファイル変換機能。 CFF、EOT、WOFF、TTF、Type 1 などのさまざまなフォントを、数行の Java コードで変換します。
keywords: フォント変換 Java、フォント変換 Java、フォント変換 Java
family: font
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: フォントを変換する
h2: Java 用のフォント形式変換 API。 WOFF2、TTF、EOT、および CFF フォントを変換します。
---

{{<section overview>}}
---
p1: Java フォント API は、CFF、OpenType、Type1、および TrueType コレクションなどのさまざまなフォントを簡単にロード、保存、および変換できます。これは、文字コードとグリフ識別子間のマッピングを表すすべてのフォント タイプのエンコード情報だけでなく、任意のグリフと共にフォント データ構造を提供します。 API は、ポイントの移動、線の描画、曲線などの単純なグラフィック機能を使用してインターフェイスを実装することでレンダリングできる特別なグリフだけでなく、必要なグリフやテキストもレンダリングできます。
p2: "ガジェット、環境、いくつかの運用システム、およびその他の多くの領域の多様な性質により、さまざまなフォント形式を使用して、Web ページ、アプリケーション、公開でさまざまなフォントを使用するなど、さまざまな目的に対応します。必要な表示に合わせて、あるフォントを別のフォントに変換する必要がある場合があります。"
p3: "TrueType (TTF)、Web Open Font Format (WOFF および WOFF2)、Embedded OpenType 形式 (EOT)、Type 1、および Compact Font Format (CFF) の次のフォントを出力形式としてサポートする Java Api ソリューションを提供します。"
---

{{<section feature1>}}
---
title: TrueType フォントから Web Open Font Format バージョン 2.0 への変換。
item1: API は、読み書き用にさまざまなフォントをサポートしています。読み書き用の [リスト](https://docs.aspose.com/font/java/convert/#formats-supported-for-reading-andor-writing) をご覧ください。 TTF から WOFF2 への変換を検討するためのプロセスは、サポートされている任意のフォーマット (現在のシナリオでは TrueType フォント) からフォントをロードすることです。 [*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) メソッドを使用する出力ストリームと [*FontSavingFormats*](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) 出力フォント形式を選択するための列挙。
item2: 最後に、SaveToFormat() を呼び出して、サポートされている任意の出力形式 (現在は Web Open Font Format バージョン 2.0 WOFF2 形式) にフォントを保存します。
item3: この機能が実際のクロスプラットフォーム アプリケーションで実現されていることを確認するには、[Aspose フォント コンバーター アプリ](https://products.aspose.app/font/conversion) にアクセスしてください。そこには、フォントとテキストを操作するための [API ソリューション](https://products.aspose.app/font/applications) も多数あります。
item4: '[ドキュメント](https://docs.aspose.com/font/net/) にアクセスして、ソリューションの使用を開始するために必要なすべての情報を入手してください。たとえば、主な機能のチュートリアルや一連の記事などがあります。フォント、リリース ノート、開発者ガイド、およびその他の便利なことについて。'
---

{{<section codeexample>}}
---
title: CFF から TTF への変換用の Java コード
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