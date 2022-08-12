---
translation: true
deploy: false
---


{{<section TTF>}}

Format TrueType Font lub TTF jest obecnie najpopularniejszym formatem. Ten format został po raz pierwszy opracowany przez firmę Apple, a obecnie jest używany w systemach operacyjnych Microsoft i Apple. Czcionka TTF wykorzystuje specjalne techniki w celu zapewnienia wysokiej jakości renderowania czcionki na urządzeniach o niskiej rozdzielczości ekranu. Wykorzystuje opracowane narzędzie instrukcji, które pozwalają czcionkom mieć jakość zbliżoną do czcionek bitmapowych.

{{<section WOFF>}}

Web Open Font Format lub WOFF został opracowany w 2009 roku w celu zaspokojenia potrzeb rynku aplikacji internetowych poprzez dodanie kompresji specyficznej dla formatu do czcionek TrueType i OpenType. Wykorzystuje kompresję zlib, która zapewnia czcionkom około 40% kompresji. Inną osobliwością formatu WOFF jest że czcionka formatu może zawierać dołączone dodatkowe metadane. Te metadane nie wpływają na sposób renderowania czcionki, ale mogą być wyświetlane użytkownikowi, gdy jest to potrzebne.

{{<section WOFF2>}}

Web Open Font Format 2 lub WOFF2 to kolejna wersja formatu WOFF z lepszą kompresją. Aby być precyzyjnym, daje 30% przewagę w kompresji nad formatem WOFF. Wykorzystuje algorytm kompresji na poziomie bajtów Brotli, który jest biblioteką do kompresji danych z otwartym kodem źródłowym. Służy do przyspieszenia ładowania stron internetowych. Jako format WOFF, WOFF2 jest również obsługiwany przez większość przeglądarek.

{{<section TYPE1>}}

Format Type 1 wszedł na rynek wraz z językiem programowania PostScript w 1984 roku, więc format ten jest również nazywany Postscript Type 1. Jest to specjalna forma programu Postscript i format pliku, który jest zorientowany na opisywanie czcionki. Format Type 1 jest rozpoznawany przez drukarki i komputery za pomocą wbudowanych interpreterów lub dodatkowych narzędzi, takich jak Adobe Type Manager. Czcionki nie obsługują standardów kodowania Unicode.

{{<section EOT>}}

Wbudowany format OpenType lub EOT. Jest to kompaktowy format czcionek OpenType osadzonych na stronach internetowych. Używając kompresji LZ i włączając do czcionki tylko niezbędne znaki, pliki OpenType są kompaktowe. Czcionka pozwala zapobiegać naruszeniom praw autorskich i jest zawsze czytelna, ponieważ używa czcionek zastępczych.

{{<section CFF>}}

Compact Font Format lub CFF jest również znany jako format czcionki Type 2 lub format czcionki CFF/Type 2. Mówi się, że CFF nie jest dokładnie formatem czcionki, ale sposobem na kompresję innych formatów czcionek, takich jak Type 1. Podobnie jak formaty Type 1 i TrueType, CFF również używa podpowiedzi. Wykorzystuje te same metody do reprezentowania wskazówek co Type 1, ale są one łatwiejsze i czystsze do pisania w kodzie i oferują znaczną oszczędność miejsca.

{{<section OTF>}}

Na tej podstawie powstała czcionka OpenType Font lub OTF, która swoją podstawową strukturę zaczerpnęła z TrueType. Do tego dodano dodatkowe konstrukcje danych, aby uporządkować zachowanie typograficzne. Format ten jest znany jako połączenie czcionek TrueType i Postscript. Ponieważ jest naprawdę elastyczny, jest obsługiwany przez większość systemów operacyjnych i urządzeń. Jako TTF, OTF jest również całkowicie skalowany bez utraty jakości.