---
translation: true
deploy: false
---


{{<section TTF>}}

TrueType Font format or TTF is by now the most popular. This format was first developed by Apple and nowadays it is used in Microsoft and Apple operating systems. TTF font uses special techniques to supply the high-quality rendering of the font on devices with low screen resolution. It uses the developed tool of instructions that allow fonts to have similar to bitmap fonts quality.

{{<section WOFF>}}

Web Open Font Format or WOFF was developed in 2009 to cover the needs of the web application market by adding format-specific compression to TrueType and OpenType fonts. It uses zlib compression that gives fonts about 40% compression. Another peculiarity of WOFF format is that the font of the format can include attached additional metadata. This metadata does not affect the way the font renders, but may be shown to a user when it is needed.

{{<section WOFF2>}}

Web Open Font Format 2 or WOFF2 is the next version of WOFF format with better compression. To be precise it gives a 30% advantage in compression over WOFF format. It uses the byte-level compression algorithm Brotli, which is a library for data compression with the open-source. It is used to speed up the loading of web pages. As WOFF format, WOFF2 is also supported by most browsers.

{{<section TYPE1>}}

Type 1 format came to market along with the PostScript programming language in 1984 so the format is also called Postscript Type 1. It is a special form of the program Postscript and the file format, which is oriented toward describing the font. Type 1 format is recognized by printers and computers either by built-in interpreters or by additional utilities like Adobe Type Manager. The fonts do not support Unicode coding standards.

{{<section EOT>}}

Embedded OpenType or EOT format. It is a compact format of OpenType fonts embedded into web pages. Using LZ compression and including only necessary characters into a font, OpenType files are compact. The font allows preventing font copyright violations and is always readable as it uses fallback fonts.

{{<section CFF>}}

Compact Font Format or CFF is also known as Type 2 font format, or CFF/Type 2 font format. It is said that CFF is not exactly the font format but the way to compress other font formats, like Type 1. Like Type 1 and TrueType formats, CFF also uses hinting. It uses the same methods to represent hints as Type 1, but they are easier and cleaner to write in code and offer a notable space saving.

{{<section OTF>}}

OpenType Font or OTF was created on the basis and took its basic structure from TrueType. To this were added additional data constructs to order the typographic behavior. The format is known as the conjunction of TrueType and Postscript fonts. As it is really flexible it is supported by most operating systems and devices. As TTF, OTF is also completely scaled without losing the quality.