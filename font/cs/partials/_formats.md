---
translation: true
deploy: false
---


{{<section TTF>}}

Formát TrueType Font nebo TTF je nyní nejoblíbenější. Tento formát byl poprvé vyvinut společností Apple a dnes se používá v operačních systémech Microsoft a Apple. Písmo TTF používá speciální techniky k zajištění vysoce kvalitního vykreslení písma na zařízeních s nízkým rozlišením obrazovky. Využívá vyvinutý nástroj instrukcí, které umožňují fontům mít podobnou kvalitu jako bitmapové fonty.

{{<section WOFF>}}

Web Open Font Format neboli WOFF byl vyvinut v roce 2009, aby pokryl potřeby trhu webových aplikací přidáním komprese specifické pro daný formát k fontům TrueType a OpenType. Používá kompresi zlib, která dává fontům asi 40% kompresi. Další zvláštností formátu WOFF je že písmo formátu může obsahovat připojená další metadata. Tato metadata neovlivňují způsob vykreslování písma, ale mohou být zobrazena uživateli, když je to potřeba.

{{<section WOFF2>}}

Web Open Font Format 2 nebo WOFF2 je další verzí formátu WOFF s lepší kompresí. Přesněji řečeno, poskytuje 30% výhodu v kompresi oproti formátu WOFF. Využívá kompresní algoritmus na úrovni bajtů Brotli, což je knihovna pro kompresi dat s open-source. Slouží k urychlení načítání webových stránek. Jako formát WOFF je WOFF2 podporován také většinou prohlížečů.

{{<section TYPE1>}}

Formát Type 1 přišel na trh spolu s programovacím jazykem PostScript v roce 1984, proto se tento formát nazývá také Postscript Type 1. Jedná se o speciální formu programu Postscript a formát souboru, který je orientován na popis písma. Formát Type 1 rozpoznávají tiskárny a počítače buď pomocí vestavěných interpretů, nebo pomocí dalších nástrojů, jako je Adobe Type Manager. Písma nepodporují standardy kódování Unicode.

{{<section EOT>}}

Vestavěný formát OpenType nebo EOT. Jedná se o kompaktní formát písem OpenType vložených do webových stránek. Díky kompresi LZ a zahrnutí pouze nezbytných znaků do písma jsou soubory OpenType kompaktní. Písmo umožňuje zabránit porušování autorských práv na písmo a je vždy čitelné, protože používá záložní písma.

{{<section CFF>}}

Compact Font Format nebo CFF je také známý jako formát písma Type 2 nebo formát písma CFF/Type 2. Říká se, že CFF není přesně formát písma, ale způsob, jak komprimovat jiné formáty písem, jako je Type 1. Stejně jako formáty Type 1 a TrueType, CFF také používá hinting. K reprezentaci nápověd používá stejné metody jako Type 1, ale jejich zápis do kódu je jednodušší a čistší a nabízí výraznou úsporu místa.

{{<section OTF>}}

OpenType Font nebo OTF byl vytvořen na základě a převzal svou základní strukturu z TrueType. K tomu byly přidány další datové konstrukce pro uspořádání typografického chování. Formát je znám jako spojení písem TrueType a Postscript. Protože je opravdu flexibilní, podporuje jej většina operačních systémů a zařízení. Jako TTF je OTF také kompletně škálován bez ztráty kvality.