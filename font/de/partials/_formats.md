---
translation: true
deploy: false
---


{{<section TTF>}}

Das TrueType-Schriftformat oder TTF ist mittlerweile das beliebteste. Dieses Format wurde zuerst von Apple entwickelt und wird heute in Microsoft- und Apple-Betriebssystemen verwendet. TTF-Schriftarten verwenden spezielle Techniken, um die hochwertige Wiedergabe der Schriftart auf Geräten mit niedriger Bildschirmauflösung bereitzustellen. Es verwendet das entwickelte Tool mit Anweisungen, die es Schriftarten ermöglichen, eine ähnliche Qualität wie Bitmap-Schriftarten zu haben.

{{<section WOFF>}}

Das Web Open Font Format oder WOFF wurde 2009 entwickelt, um die Bedürfnisse des Marktes für Webanwendungen abzudecken, indem TrueType- und OpenType-Schriftarten um eine formatspezifische Komprimierung erweitert wurden. Es verwendet die zlib-Komprimierung, die Schriften eine Komprimierung von etwa 40 % verleiht dass die Schriftart des Formats angehängte zusätzliche Metadaten enthalten kann. Diese Metadaten wirken sich nicht auf die Art und Weise aus, wie die Schriftart gerendert wird, können aber einem Benutzer angezeigt werden, wenn sie benötigt werden.

{{<section WOFF2>}}

Web Open Font Format 2 oder WOFF2 ist die nächste Version des WOFF-Formats mit besserer Komprimierung. Um genau zu sein, bietet es einen Komprimierungsvorteil von 30 % gegenüber dem WOFF-Format. Es verwendet den Komprimierungsalgorithmus auf Byteebene Brotli, eine Bibliothek zur Datenkomprimierung mit Open Source. Es wird verwendet, um das Laden von Webseiten zu beschleunigen. Als WOFF-Format wird auch WOFF2 von den meisten Browsern unterstützt.

{{<section TYPE1>}}

Das Typ-1-Format kam 1984 zusammen mit der Programmiersprache PostScript auf den Markt, daher wird das Format auch als Postscript Typ 1 bezeichnet. Es ist eine spezielle Form des Programms Postscript und des Dateiformats, das sich an der Beschreibung der Schriftart orientiert. Das Typ-1-Format wird von Druckern und Computern entweder durch integrierte Interpreter oder durch zusätzliche Dienstprogramme wie Adobe Type Manager erkannt. Die Schriftarten unterstützen keine Unicode-Codierungsstandards.

{{<section EOT>}}

Eingebettetes OpenType- oder EOT-Format. Es ist ein kompaktes Format von OpenType-Schriftarten, die in Webseiten eingebettet sind. Durch die LZ-Komprimierung und das Einfügen nur notwendiger Zeichen in eine Schriftart sind OpenType-Dateien kompakt. Die Schriftart ermöglicht das Verhindern von Urheberrechtsverletzungen für Schriftarten und ist immer lesbar, da sie Fallback-Schriftarten verwendet.

{{<section CFF>}}

Compact Font Format oder CFF wird auch als Type 2 Font Format oder CFF/Type 2 Font Format bezeichnet. Es wird gesagt, dass CFF nicht genau das Schriftartformat ist, sondern die Möglichkeit, andere Schriftartformate wie Type 1 zu komprimieren. Wie Type 1 und TrueType-Formate verwendet CFF auch Hinting. Es verwendet die gleichen Methoden zur Darstellung von Hinweisen wie Typ 1, aber sie sind einfacher und sauberer in Code zu schreiben und bieten eine bemerkenswerte Platzersparnis.

{{<section OTF>}}

OpenType Font oder OTF wurde auf der Basis erstellt und hat seine Grundstruktur von TrueType übernommen. Dazu wurden weitere Datenkonstrukte hinzugefügt, um das typografische Verhalten zu ordnen. Das Format ist als Verbindung von TrueType- und Postscript-Schriftarten bekannt. Da es sehr flexibel ist, wird es von den meisten Betriebssystemen und Geräten unterstützt. Als TTF wird auch OTF komplett skaliert ohne an Qualität zu verlieren.