---
translation: true
template: /_templates/conversion-cpp.md
title: Konvertierung von Schriftarten | C++
url: /cpp/conversion/
description: Konvertieren Sie Schriftarten mit der C++-Schriftverarbeitungsbibliothek und Webanwendungen. Konvertierungsfunktion, die mit TTF-, WOFF-, CFF-, EOT- und Typ-1-Schriftarten arbeiten kann.
metakeywords: C++-Schriftkonvertierung, Lösungen zur Konvertierung von Schriftarten c++, Schriftartkonverter cpp
family: font
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Schriftarten konvertieren
h2: Schriftformatkonverter-API für С++. Konvertieren Sie WOFF2-, TTF-, EOT- und CFF-Schriftarten.
---

{{<section overview>}}
---
p1: Die С++-Schriftarten-API kann verschiedene Schriftarten wie CFF-, OpenType-, Type1- und TrueType-Sammlungen einfach laden, speichern und konvertieren. Es stellt Schriftdatenstrukturen zusammen mit jedem Glyphen sowie Codierungsinformationen für alle Schrifttypen bereit, die eine Abbildung zwischen Zeichencodes und Glyphenkennungen darstellen. Die API kann jede gewünschte Glyphe oder jeden gewünschten Text sowie spezielle Glyphen rendern, die durch Implementieren von Schnittstellen mit einfachen Grafikfunktionen wie Verschieben von Punkten, Zeichnen von Linien und Kurven usw. gerendert werden können.
p2: "Aufgrund der unterschiedlichen Natur von Gadgets, Umgebungen, einigen Betriebssystemen und vielen anderen Bereichen müssen unterschiedliche Schriftartformate verwendet werden, um unterschiedliche Zwecke zu erfüllen, z. B. die Verwendung unterschiedlicher Schriftarten auf Webseiten, Anwendungen und Veröffentlichungen. Manchmal ist es erforderlich, eine Schriftart in eine andere umzuwandeln, um die erforderliche Anzeige zu erfüllen."
p3: "Wir bieten Ihnen die С++ Api-Lösung, die die folgenden Schriftarten als Ausgabeformate unterstützt: TrueType (TTF), Web Open Font Format (WOFF und WOFF2), Embedded OpenType-Format (EOT), Type 1 und Compact Font Format (CFF)."
---

{{<section feature1>}}
---
title: Umwandlung von TrueType-Schriftarten in Web Open Font Format Version 2.0.
item1: Die API unterstützt verschiedene Schriftarten zum Lesen und Schreiben, hier ist die [Liste](https://docs.aspose.com/font/cpp/convert/#formats-supported-for-reading-andor-writing) zum Lesen und Schreiben. Um die Konvertierung von TTF in WOFF2 in Betracht zu ziehen, besteht der Prozess darin, eine Schriftart aus einem der unterstützten Formate zu laden, TrueType-Schriftart für das aktuelle Szenario. Verwenden Sie die Methode [*SaveToFormat()*](https://reference.aspose.com/font/cpp/class/aspose.font.font#a670ea97404fd72c2e51b0e8c543c8a45) mit zwei Parametern für den Ausgabestrom und [*FontSavingFormats*](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74) Aufzählung zur Auswahl des Ausgabeschriftformats.
item2: Rufen Sie schließlich SaveToFormat() auf, um Schriftarten in einem der unterstützten Ausgabeformate zu speichern, derzeit im Format Web Open Font Format Version 2.0 WOFF2.
item3: Um zu sehen, wie diese Funktionalität in einer tatsächlichen plattformübergreifenden Anwendung realisiert wird, gehen Sie zu [Aspose Font Converter App](https://products.aspose.app/font/conversion). Dort finden Sie auch viele weitere [API-Lösungen](https://products.aspose.app/font/applications) zum Arbeiten mit Schriftarten und Text.
item4: Rufen Sie die [Dokumentation](https://docs.aspose.com/font/net/) auf, um alle erforderlichen Informationen zu erhalten, um mit der Arbeit mit der Lösung zu beginnen, wie z. B. die Tutorials für die Hauptfunktionen oder die Artikel, die Sie unterrichten über Schriftarten, Versionshinweise, Entwicklerhandbuch und andere nützliche Dinge.
---

{{<section codeexample>}}
---
title: C++-Codebeispiel Umwandlung von TTF in WOFF2
---



