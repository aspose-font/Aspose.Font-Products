---
translation: true
template: /_templates/conversion-net.md
title: Interfejs API konwersji czcionek | .INTERNET
url: /net/conversion/
description: Funkcjonalność konwersji czcionek. Konwertuj różne czcionki, takie jak CFF, EOT, WOFF, TTF i Type 1, za pomocą kilku wierszy kodu C# za pośrednictwem biblioteki .NET.
keywords: konwerter czcionek .net, konwerter czcionek netto, konwersja czcionek c#
family: font
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Konwertuj czcionki za pomocą C#
h2: Interfejs API konwertera formatu czcionek dla platformy .NET. Konwertuj czcionki WOFF2, TTF, EOT i CFF.
---

{{<section overview>}}
---
p1: Interfejs API czcionek .NET umożliwia łatwe ładowanie, zapisywanie i konwertowanie różnych czcionek, takich jak kolekcje CFF, OpenType, Type1 i TrueType. Zapewnia strukturę danych czcionki wraz z dowolnym glifem, a także informacje o kodowaniu dla wszystkich typów czcionek reprezentujących mapowanie między kodami znaków i identyfikatorami glifów. API może renderować dowolny pożądany glif lub tekst, a także specjalne glify, które można renderować, implementując interfejsy za pomocą prostych funkcji graficznych, takich jak przesuwanie punktu, rysowanie linii i krzywej itp.
p2: "Ze względu na różnorodny charakter gadżetów, środowisk, kilku systemów operacyjnych i wielu innych obszarów różne formaty czcionek mogą być używane do różnych celów, takich jak używanie różnych czcionek na stronach internetowych, aplikacjach i publikowaniu. Czasami istnieje potrzeba przekształcenia jednej czcionki w inną, aby sprostać wymaganiom wyświetlacza."
p3: "Rozwiązanie tutaj obsługuje następujące czcionki jako formaty wyjściowe: TrueType (TTF), Web Open Font Format (WOFF i WOFF2), Embedded OpenType format (EOT), Type 1 i Compact Font Format (CFF)."
---

{{<section feature1>}}
---
title: Konwersja czcionki TrueType do formatu Web Open Font w wersji 2.0.
item1: API obsługuje różne czcionki do czytania i pisania, oto [lista](https://docs.aspose.com/font/net/convert/#formats-supported-for-reading-andor-writing) do czytania i pisania. Aby uwzględnić konwersję TTF do WOFF2, proces polega na załadowaniu czcionki z dowolnego z obsługiwanych formatów, TrueType Font dla bieżącego scenariusza. Użyj metody [*SaveToFormat()*](https://reference.aspose.com/font/net/aspose.font/font/savetoformat/) z dwoma parametrami strumienia wyjściowego i [*FontSavingFormats*](https://aireference.aspose.com/font/net/aspose.font/fontsavingformats) Wyliczenie służące do wybierania wyjściowego formatu czcionki.
item2: Na koniec wywołaj SaveToFormat(), aby zapisać czcionki w dowolnym z obsługiwanych formatów wyjściowych, obecnie w formacie Web Open Font Format w wersji 2.0 WOFF2.
item3: Aby zobaczyć tę funkcjonalność realizowaną w rzeczywistej aplikacji wieloplatformowej, przejdź do [aplikacji Aspose Font Converter](https://products.aspose.app/font/conversion). Znajdziesz tam również wiele innych [rozwiązań API](https://products.aspose.app/font/applications) do pracy z czcionkami i tekstem.
item4: Przejdź do [Dokumentacji](https://docs.aspose.com/font/net/), aby uzyskać wszystkie informacje potrzebne do rozpoczęcia pracy z rozwiązaniem, takie jak samouczki dotyczące głównych funkcji lub zestaw artykułów do nauki o czcionkach, informacjach o wydaniu, podręczniku programisty i innych przydatnych rzeczach.
---

{{<section codeexample>}}
---
title: Przykład kodu C# Konwersja TTF do WOFF2
---
