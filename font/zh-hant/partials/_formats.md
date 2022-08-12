---
translation: true
deploy: false
---


{{<section TTF>}}

TrueType 字體格式或 TTF 是目前最流行的。這種格式最初是由 Apple 開發的，現在它用於 Microsoft 和 Apple 操作系統。 TTF 字體使用特殊技術在低屏幕分辨率的設備上提供高質量的字體渲染。它使用開發的指令工具，使字體具有類似於位圖字體的質量。

{{<section WOFF>}}

Web Open Font Format 或 WOFF 於 2009 年開發，通過向 TrueType 和 OpenType 字體添加特定格式的壓縮來滿足 Web 應用程序市場的需求。它使用 zlib 壓縮，使字體壓縮率約為 40%。WOFF 格式的另一個特點是“該格式的字體可以包含附加的附加元數據。此元數據不會影響字體呈現的方式，但可能會在需要時向用戶顯示。

{{<section WOFF2>}}

Web Open Font Format 2 或 WOFF2 是具有更好壓縮的 WOFF 格式的下一個版本。準確地說，它在壓縮方面比 WOFF 格式有 30% 的優勢。它使用字節級壓縮算法 Brotli，這是一個開源的數據壓縮庫。它用於加快網頁的加載速度。作為 WOFF 格式，大多數瀏覽器也支持 WOFF2。

{{<section TYPE1>}}

Type 1 格式與 PostScript 編程語言於 1984 年一起上市，因此該格式也稱為 Postscript Type 1。它是 Postscript 程序和文件格式的一種特殊形式，面向描述字體。打印機和計算機可以通過內置解釋器或 Adob​​e Type Manager 等附加實用程序識別 Type 1 格式。字體不支持 Unicode 編碼標準。

{{<section EOT>}}

嵌入式 OpenType 或 EOT 格式。它是嵌入到網頁中的 OpenType 字體的緊湊格式。使用 LZ 壓縮並僅在字體中包含必要的字符，OpenType 文件非常緊湊。該字體允許防止侵犯字體版權，並且由於它使用後備字體而始終可讀。

{{<section CFF>}}

緊湊字體格式或 CFF 也稱為 Type 2 字體格式或 CFF/Type 2 字體格式。據說CFF並不完全是字體格式，而是壓縮其他字體格式的方式，比如Type 1。CFF和Type 1和TrueType格式一樣，也使用了hinting。它使用與 Type 1 相同的方法來表示提示，但它們在代碼中編寫起來更容易、更清晰，並且顯著節省了空間。

{{<section OTF>}}

OpenType Font 或 OTF 是在此基礎上創建的，其基本結構來自 TrueType。為此添加了額外的數據結構來排序印刷行為。該格式被稱為 TrueType 和 Postscript 字體的結合。由於它非常靈活，因此大多數操作系統和設備都支持它。作為 TTF，OTF 也是完全縮放而不損失質量。