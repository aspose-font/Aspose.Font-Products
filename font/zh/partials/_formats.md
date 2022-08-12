---
translation: true
deploy: false
---


{{<section TTF>}}

TrueType 字体格式或 TTF 是目前最流行的。这种格式最初由 Apple 开发，如今已用于 Microsoft 和 Apple 操作系统。 TTF 字体使用特殊技术在低屏幕分辨率的设备上提供高质量的字体渲染。它使用开发的指令工具，使字体具有类似于位图字体的质量。

{{<section WOFF>}}

Web Open Font Format 或 WOFF 于 2009 年开发，通过向 TrueType 和 OpenType 字体添加特定格式的压缩来满足 Web 应用程序市场的需求。它使用 zlib 压缩，使字体压缩率约为 40%。WOFF 格式的另一个特点是“该格式的字体可以包含附加的附加元数据。此元数据不会影响字体呈现的方式，但可能会在需要时向用户显示。

{{<section WOFF2>}}

Web Open Font Format 2 或 WOFF2 是具有更好压缩的 WOFF 格式的下一个版本。准确地说，它在压缩方面比 WOFF 格式有 30% 的优势。它使用字节级压缩算法 Brotli，这是一个开源的数据压缩库。它用于加快网页的加载速度。作为 WOFF 格式，大多数浏览器也支持 WOFF2。

{{<section TYPE1>}}

Type 1 格式与 PostScript 编程语言于 1984 年一起上市，因此该格式也称为 Postscript Type 1。它是 Postscript 程序和文件格式的一种特殊形式，面向描述字体。打印机和计算机可以通过内置解释器或 Adob​​e Type Manager 等附加实用程序识别 Type 1 格式。字体不支持 Unicode 编码标准。

{{<section EOT>}}

嵌入式 OpenType 或 EOT 格式。它是嵌入到网页中的 OpenType 字体的紧凑格式。使用 LZ 压缩并仅在字体中包含必要的字符，OpenType 文件非常紧凑。该字体允许防止侵犯字体版权，并且由于它使用后备字体而始终可读。

{{<section CFF>}}

紧凑字体格式或 CFF 也称为 Type 2 字体格式或 CFF/Type 2 字体格式。据说CFF并不完全是字体格式，而是压缩其他字体格式的方式，比如Type 1。CFF和Type 1和TrueType格式一样，也使用了hinting。它使用与 Type 1 相同的方法来表示提示，但它们在代码中编写起来更容易、更清晰，并且显着节省了空间。

{{<section OTF>}}

OpenType Font 或 OTF 是在此基础上创建的，其基本结构来自 TrueType。为此添加了额外的数据结构来排序印刷行为。该格式被称为 TrueType 和 Postscript 字体的结合。由于它非常灵活，因此大多数操作系统和设备都支持它。作为 TTF，OTF 也是完全缩放而不损失质量。