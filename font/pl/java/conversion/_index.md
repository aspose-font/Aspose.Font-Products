---
translation: true
template: /_templates/conversion-java.md
title: Interfejs API konwersji czcionek | Jawa
url: /java/conversion/
description: Funkcjonalność konwersji plików czcionek Java. Konwertuj różne czcionki, takie jak CFF, EOT, WOFF, TTF i Type 1, za pomocą kilku linijek kodu Java.
keywords: konwertuj czcionki java, konwersja czcionek Java, konwerter czcionek java
family: font
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: Konwertuj czcionki
h2: Interfejs API konwertera formatu czcionek dla języka Java. Konwertuj czcionki WOFF2, TTF, EOT i CFF.
---

{{<section overview>}}
---
p1: Java Font API może łatwo ładować, zapisywać i konwertować różne czcionki, takie jak kolekcje CFF, OpenType, Type1 i TrueType. Zapewnia strukturę danych czcionki wraz z dowolnym glifem, a także informacje o kodowaniu dla wszystkich typów czcionek reprezentujących mapowanie między kodami znaków i identyfikatorami glifów. API może renderować dowolny pożądany glif lub tekst, a także specjalne glify, które można renderować, implementując interfejsy za pomocą prostych funkcji graficznych, takich jak przesuwanie punktu, rysowanie linii i krzywej itp.
p2: "Ze względu na różnorodny charakter gadżetów, środowisk, kilku systemów operacyjnych i wielu innych obszarów różne formaty czcionek mogą być używane do różnych celów, takich jak używanie różnych czcionek na stronach internetowych, aplikacjach i publikowaniu. Czasami istnieje potrzeba przekształcenia jednej czcionki w inną, aby sprostać wymaganiom wyświetlacza."
p3: "Oferujemy rozwiązanie Java Api, które obsługuje następujące czcionki jako formaty wyjściowe: TrueType (TTF), Web Open Font Format (WOFF i WOFF2), Embedded OpenType format (EOT), Type 1 i Compact Font Format (CFF)."
---

{{<section feature1>}}
---
title: Konwersja czcionki TrueType do formatu Web Open Font w wersji 2.0.
item1: API obsługuje różne czcionki do czytania i pisania, oto [lista](https://docs.aspose.com/font/java/convert/#formats-supported-for-reading-andor-writing) do czytania i pisania. Aby uwzględnić konwersję TTF do WOFF2, proces polega na załadowaniu czcionki z dowolnego z obsługiwanych formatów, TrueType Font dla bieżącego scenariusza. Użyj metody [*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) [Klasy czcionek](https://reference.aspose.com/font/java/com.aspose.font/Font#save-java.lang.String-) mającego dwa parametry strumienia wyjściowego i [*FontSavingFormats*](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) Wyliczenie służące do wybierania formatu czcionki wyjściowej.
item2: Na koniec wywołaj SaveToFormat(), aby zapisać czcionki w dowolnym z obsługiwanych formatów wyjściowych, obecnie w formacie Web Open Font Format w wersji 2.0 WOFF2.
item3: Aby zobaczyć tę funkcjonalność realizowaną w rzeczywistej aplikacji wieloplatformowej, przejdź do [aplikacji Aspose Font Converter](https://products.aspose.app/font/conversion). Znajdziesz tam również wiele innych [rozwiązań API](https://products.aspose.app/font/applications) do pracy z czcionkami i tekstem.
item4: Przejdź do [Dokumentacji](https://docs.aspose.com/font/net/), aby uzyskać wszystkie informacje potrzebne do rozpoczęcia pracy z rozwiązaniem, takie jak samouczki dotyczące głównych funkcji lub zestaw artykułów do nauki o czcionkach, informacjach o wydaniu, podręczniku programisty i innych przydatnych rzeczach.
---

{{<section codeexample>}}
---
title: Kod Java do konwersji CFF na TTF
---