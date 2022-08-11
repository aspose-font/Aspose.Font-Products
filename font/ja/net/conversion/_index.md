---
translation: true
template: /_templates/conversion-net.md
title: フォント変換 API | .NET
url: /net/conversion/
description: フォント変換機能。 CFF、EOT、WOFF、TTF、Type 1 などのさまざまなフォントを、.NET ライブラリを介して数行の C# コードで変換します。
keywords: フォント コンバーター .net、フォント コンバーター ネット、c# フォント カバーション
family: font
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: C# 経由でフォントを変換する
h2: .NET 用のフォント形式コンバーター API。 WOFF2、TTF、EOT、および CFF フォントを変換します。
---

{{<section overview>}}
---
p1: .NET フォント API は、CFF、OpenType、Type1、および TrueType コレクションなどのさまざまなフォントを簡単にロード、保存、および変換できます。これは、文字コードとグリフ識別子間のマッピングを表すすべてのフォント タイプのエンコード情報だけでなく、任意のグリフと共にフォント データ構造を提供します。 API は、ポイントの移動、線の描画、曲線などの単純なグラフィック機能を使用してインターフェイスを実装することでレンダリングできる特別なグリフだけでなく、必要なグリフやテキストもレンダリングできます。
p2: "ガジェット、環境、いくつかの運用システム、およびその他の多くの領域の多様な性質により、さまざまなフォント形式を使用して、Web ページ、アプリケーション、公開でさまざまなフォントを使用するなど、さまざまな目的に対応します。必要な表示に合わせて、あるフォントを別のフォントに変換する必要がある場合があります。"
p3: "ここでのソリューションは、次のフォントを出力形式としてサポートしています: TrueType (TTF)、Web Open Font Format (WOFF および WOFF2)、Embedded OpenType 形式 (EOT)、Type 1、および Compact Font Format (CFF)。"
---

{{<section feature1>}}
---
title: TrueType フォントから Web Open Font Format バージョン 2.0 への変換。
item1: API は、読み書き用にさまざまなフォントをサポートしています。ここでは、読み書き用の [リスト](https://docs.aspose.com/font/net/convert/#formats-supported-for-reading-andor-writing)  つのフォントを示します。 TTF から WOFF2 への変換を検討するためのプロセスは、サポートされている任意のフォーマット (現在のシナリオでは TrueType フォント) からフォントをロードすることです。 出力フォント形式を選択するには、2 つのパラメータ出力ストリームと [*FontSavingFormats*](https://reference.aspose.com/font/net/aspose.font/fontsavingformats/) 列挙を持つ [*SaveToFormat()*](https://reference.aspose.com/font/net/aspose.font/font/savetoformat/) つのメソッドを使用します。
item2: 最後に、SaveToFormat() を呼び出して、サポートされている任意の出力形式 (現在は Web Open Font Format バージョン 2.0 WOFF2 形式) にフォントを保存します。
item3: この機能が実際のクロスプラットフォーム アプリケーションで実現されていることを確認するには、[Aspose フォント コンバーター アプリ](https://products.aspose.app/font/conversion) にアクセスしてください。そこには、フォントとテキストを操作するための [API ソリューション](https://products.aspose.app/font/applications) も多数あります。
item4: '[ドキュメント](https://docs.aspose.com/font/net/) にアクセスして、ソリューションの使用を開始するために必要なすべての情報を入手してください。たとえば、主な機能のチュートリアルや一連の記事などがあります。フォント、リリース ノート、開発者ガイド、およびその他の便利なことについて。'
---

{{<section codeexample>}}
---
title: C# コード例 TTF から WOFF2 への変換
---
