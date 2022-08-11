---
translation: true
template: /_templates/conversion-cpp.md
title: フォント変換 | C++
url: /cpp/conversion/
description: C++ フォント処理ライブラリと Web アプリケーションを使用してフォントを変換します。 TTF、WOFF、CFF、EOT、Type 1 フォントに対応した変換機能。
metakeywords: c++ フォント変換, フォント変換ソリューション c++, フォント conerter cpp
family: font
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: フォントを変換する
h2: С++ のフォント形式変換 API。 WOFF2、TTF、EOT、および CFF フォントを変換します。
---

{{<section overview>}}
---
p1: С++ フォント API は、CFF、OpenType、Type1、および TrueType コレクションなどのさまざまなフォントを簡単にロード、保存、および変換できます。これは、文字コードとグリフ識別子間のマッピングを表すすべてのフォント タイプのエンコード情報だけでなく、任意のグリフと共にフォント データ構造を提供します。 API は、ポイントの移動、線の描画、曲線などの単純なグラフィック機能を使用してインターフェイスを実装することでレンダリングできる特別なグリフだけでなく、必要なグリフやテキストもレンダリングできます。
p2: "ガジェット、環境、いくつかの運用システム、およびその他の多くの領域の多様な性質により、さまざまなフォント形式を使用して、Web ページ、アプリケーション、公開でさまざまなフォントを使用するなど、さまざまな目的に対応します。必要な表示に合わせて、あるフォントを別のフォントに変換する必要がある場合があります。"
p3: "TrueType (TTF)、Web Open Font Format (WOFF および WOFF2)、Embedded OpenType フォーマット (EOT)、Type 1、および Compact Font Format (CFF) の次のフォントを出力フォーマットとしてサポートする С++ Api ソリューションを提供します。"
---

{{<section feature1>}}
---
title: TrueType フォントから Web Open Font Format バージョン 2.0 への変換。
item1: API は、読み書き用にさまざまなフォントをサポートしています。ここでは、読み書き用の [リスト](https://docs.aspose.com/font/cpp/convert/#formats-supported-for-reading-andor-writing) つのフォントを示します。 TTF から WOFF2 への変換を検討するためのプロセスは、サポートされている任意のフォーマット (現在のシナリオでは TrueType フォント) からフォントをロードすることです。 出力フォント形式を選択するには、2 つのパラメータ出力ストリームと [*FontSavingFormats*](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74)  列挙を持つ [*SaveToFormat()*](https://reference.aspose.com/font/cpp/class/aspose.font.font#a670ea97404fd72c2e51b0e8c543c8a45) つのメソッドを使用します。
item2: 最後に、SaveToFormat() を呼び出して、サポートされている任意の出力形式 (現在は Web Open Font Format バージョン 2.0 WOFF2 形式) にフォントを保存します。
item3: この機能が実際のクロスプラットフォーム アプリケーションで実現されていることを確認するには、[Aspose フォント コンバーター アプリ](https://products.aspose.app/font/conversion) にアクセスしてください。そこには、フォントとテキストを操作するための [API ソリューション](https://products.aspose.app/font/applications) も多数あります。
item4: '[ドキュメント](https://docs.aspose.com/font/net/) にアクセスして、ソリューションの使用を開始するために必要なすべての情報を入手してください。たとえば、主な機能のチュートリアルや一連の記事などがあります。フォント、リリース ノート、開発者ガイド、およびその他の便利なことについて。'
---

{{<section codeexample>}}
---
title: C++ コード例 TTF から WOFF2 への変換
---



