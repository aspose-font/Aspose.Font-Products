---
translation: true
template: /_templates/conversion-net.md
title: 字體轉換 API | 。網
url: /net/conversion/
description: 字體轉換功能。通過 .NET 庫，只需幾行 C# 代碼即可轉換 CFF、EOT、WOFF、TTF 和 Type 1 等不同字體。
keywords: 字體轉換器.net, 字體轉換器網, c# 字體覆蓋
family: font
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: 通過 C# 轉換字體
h2: .NET 的字體格式轉換器 API。轉換 WOFF2、TTF、EOT 和 CFF 字體。
---

{{<section overview>}}
---
p1: .NET 字體 API 可以輕鬆加載、保存和轉換不同的字體，例如 CFF、OpenType、Type1 和 TrueType 集合。它提供字體數據結構以及任何字形以及表示字符代碼和字形標識符之間映射的所有字體類型的編碼信息。 API 可以渲染任何需要的字形或文本，以及特殊字形，可以通過使用簡單的圖形功能(如移動點、畫線和曲線等)實現接口來渲染。
p2: "由於小工具、環境、一些操作系統和許多其他領域的多樣性，使用不同的字體格式來服務於不同的目的，例如在網頁、應用程序和發布上使用不同的字體。有時需要將一種字體轉換為另一種字體以滿足所需的顯示。"
p3: "此處的解決方案支持以下字體作為輸出格式：TrueType (TTF)、Web Open Font Format(WOFF 和 WOFF2)、Embedded OpenType 格式 (EOT)、Type 1 和 Compact Font Format (CFF)。"
---

{{<section feature1>}}
---
title: TrueType 字體到 Web 開放字體格式 2.0 版的轉換。
item1: API支持不同字體的讀寫，這裡是讀寫的[列表](https://docs.aspose.com/font/net/convert/#formats-supported-for-reading-andor-writing)。考慮到 TTF 到 WOFF2 的轉換，該過程是從任何支持的格式加載字體，當前場景的 TrueType 字體。使用 [*SaveToFormat()*](https://reference.aspose.com/font/net/aspose.font/font/methods/savetoformat) 方法有兩個參數輸出流和 [*FontSavingFormats*](https:///apireference.aspose.com/font/net/aspose.font/fontsavingformats) 用於選擇輸出字體格式的枚舉。
item2: 最後，調用 SaveToFormat() 將字體保存為任何支持的輸出格式，當前是 Web Open Font Format version 2.0 WOFF2 格式。
item3: 要查看在實際跨平台應用程序中實現的此功能，請轉到 [Aspose 字體轉換器應用程序](https://products.aspose.app/font/conversion)。在那裡，您還可以找到更多 [API 解決方案](https://products.aspose.app/font/applications) 來處理字體和文本。
item4: 轉到 [文檔](https://docs.aspose.com/font/net/) 以獲取開始使用解決方案所需的所有信息，例如主要功能的教程或教你的文章集關於字體、發行說明、開發人員指南和其他有用的東西。
---

{{<section codeexample>}}
---
title: C# 代碼示例 TTF 到 WOFF2 轉換
---
