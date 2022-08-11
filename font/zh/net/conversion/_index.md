---
translation: true
template: /_templates/conversion-net.md
title: 字体转换 API | .NET
url: /net/conversion/
description: 字体转换功能。通过 .NET 库，只需几行 C# 代码即可转换 CFF、EOT、WOFF、TTF 和 Type 1 等不同字体。
keywords: 字体转换器.net, 字体转换器网, c# 字体覆盖
family: font
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: 通过 C# 转换字体
h2: .NET 的字体格式转换器 API。转换 WOFF2、TTF、EOT 和 CFF 字体。
---

{{<section overview>}}
---
p1: .NET 字体 API 可以轻松加载、保存和转换不同的字体，例如 CFF、OpenType、Type1 和 TrueType 集合。它提供字体数据结构以及任何字形以及表示字符代码和字形标识符之间映射的所有字体类型的编码信​​息。 API 可以渲染任何需要的字形或文本，以及特殊字形，可以通过使用简单的图形功能(如移动点、画线和曲线等)实现接口来渲染。
p2: "由于小工具、环境、一些操作系统和许多其他领域的多样性，使用不同的字体格式来服务于不同的目的，例如在网页、应用程序和发布上使用不同的字体。有时需要将一种字体转换为另一种字体以满足所需的显示。"
p3: "此处的解决方案支持以下字体作为输出格式：TrueType (TTF)、Web Open Font Format(WOFF 和 WOFF2)、Embedded OpenType 格式 (EOT)、Type 1 和 Compact Font Format (CFF)。"
---

{{<section feature1>}}
---
title: TrueType 字体到 Web 开放字体格式 2.0 版的转换。
item1: API支持不同字体的读写，这里是读写的[列表](https://docs.aspose.com/font/net/convert/#formats-supported-for-reading-andor-writing)。考虑到 TTF 到 WOFF2 的转换，该过程是从任何支持的格式加载字体，当前场景的 TrueType 字体。使用 [*SaveToFormat()*](https://reference.aspose.com/font/net/aspose.font/font/savetoformat/) 方法有两个参数输出流和 [*FontSavingFormats*](https://reference.aspose.com/font/net/aspose.font/fontsavingformats/) 用于选择输出字体格式的枚举。
item2: 最后，调用 SaveToFormat() 将字体保存为任何支持的输出格式，当前是 Web Open Font Format version 2.0 WOFF2 格式。
item3: 要查看在实际跨平台应用程序中实现的此功能，请转到 [Aspose 字体转换器应用程序](https://products.aspose.app/font/conversion)。在那里，您还可以找到更多 [API 解决方案](https://products.aspose.app/font/applications) 来处理字体和文本。
item4: 转到 [文档](https://docs.aspose.com/font/net/) 以获取开始使用解决方案所需的所有信息，例如主要功能的教程或教你的文章集关于字体、发行说明、开发人员指南和其他有用的东西。
---

{{<section codeexample>}}
---
title: C# 代码示例 TTF 到 WOFF2 转换
---
