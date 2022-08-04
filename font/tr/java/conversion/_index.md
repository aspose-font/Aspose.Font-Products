---
translation: true
template: /_templates/conversion-java.md
title: Yazı Tipi Dönüştürme API'si | Java
url: /java/conversion/
description: Java Yazı Tipi Dosyaları Dönüştürme işlevi. Birkaç satır Java kodu ile CFF, EOT, WOFF, TTF ve Type 1 gibi farklı yazı tiplerini dönüştürün.
keywords: yazı tiplerini dönüştür java, yazı tipi dönüştürme Java, yazı tipi örtücü java
family: font
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: Yazı Tiplerini Dönüştür
h2: Java için yazı tipi formatı dönüştürücü API'si. WOFF2, TTF, EOT ve CFF yazı tiplerini dönüştürün.
---

{{<section overview>}}
---
p1: Java font API'si, CFF, OpenType, Type1 ve TrueType koleksiyonları gibi farklı fontları kolayca yükleyebilir, kaydedebilir ve dönüştürebilir. Karakter kodları ve glif tanımlayıcıları arasındaki bir eşlemeyi temsil eden tüm yazı tipi türleri için kodlama bilgilerinin yanı sıra herhangi bir glif ile birlikte yazı tipi veri yapısı sağlar. API, istenen herhangi bir glif veya metnin yanı sıra hareket noktası, çizim çizgisi ve eğri vb. gibi basit grafik işlevleri kullanılarak arabirimler uygulanarak oluşturulabilen özel glifleri oluşturabilir.
p2: "Gadget'ların, ortamların, birkaç işletim sisteminin ve diğer birçok alanın farklı doğası nedeniyle, web sayfalarında, uygulamalarda ve yayınlarda farklı yazı tiplerini kullanmak gibi farklı amaçlara hizmet etmek için farklı yazı tipi biçimleri kullanmak. Bazen gerekli gösterimi karşılamak için bir yazı tipini diğerine dönüştürmek gerekebilir."
p3: "Çıktı formatı olarak aşağıdaki yazı tiplerini destekleyen Java Api Çözümü sunuyoruz: TrueType (TTF), Web Açık Yazı Tipi Formatı (WOFF ve WOFF2), Gömülü OpenType formatı (EOT), Tip 1 ve Kompakt Yazı Tipi Formatı (CFF)."
---

{{<section feature1>}}
---
title: TrueType Yazı Tipinden Web'e Açık Yazı Tipi Biçimi sürüm 2.0 Dönüştürme.
item1: API, okuma ve yazma için farklı yazı tiplerini destekler, işte okuma ve yazma için [liste](https://docs.aspose.com/font/java/convert/#formats-supported-for-reading-andor-writing). TTF'den WOFF2'ye dönüştürmeyi değerlendirmek için işlem, mevcut senaryo için desteklenen biçimlerden herhangi birinden bir yazı tipi yüklemektir, TrueType Yazı Tipi. [*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) Yöntemini kullanın [Font class](https://reference.aspose.com/font/java/com.aspose.font/Font#save-java.lang.String-) iki parametreli çıktı akışına ve [*FontSavingFormats*](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) Çıktı yazı tipi biçimini seçmek için numaralandırma.
item2: Son olarak, yazı tiplerini desteklenen çıktı biçimlerinden herhangi birine kaydetmek için SaveToFormat()'ı çağırın, şu anda Web Açık Yazı Tipi Biçimi sürüm 2.0 WOFF2 biçimi.
item3: Gerçek bir platformlar arası uygulamada gerçekleştirilen bu işlevselliği görmek için [Aspose Font Converter uygulamasına](https://products.aspose.app/font/conversion) gidin. Burada ayrıca yazı tipleri ve metinle çalışmak için daha birçok [API çözümü](https://products.aspose.app/font/applications) bulabilirsiniz.
item4: Çözümle çalışmaya başlamak için gerekli tüm bilgileri almak üzere [Belgelere](https://docs.aspose.com/font/net/) gidin, örneğin ana özelliklere yönelik Öğreticiler veya size öğretecek makaleler grubu gibi yazı tipi, Sürüm Notları, Geliştirici Kılavuzu ve diğer faydalı şeyler hakkında.
---

{{<section codeexample>}}
---
title: CFF'den TTF'ye Dönüştürme için Java Kodu
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/agp/feature-section >}}
{{< app/font/converter "Java Code for CFF to TTF Conversion" CFF TTF WOFF WOFF2>}}
    // Open {{input lower}} font
    String fontPath = Paths.get(getDataDir(), "{{inputFile}}").toString();
    FontDefinition fontDefinition = new FontDefinition(FontType.{{input upper}}, new FontFileDefinition({{input lower}}, new FileSystemStreamSource(fontPath)));
    Font font = Font.open(fontDefinition);

    // {{output camel}} output settings
    String outPath = Paths.get(getOutputDir(), "{{outputFile}}").toString();
    FileOutputStream outStream = new FileOutputStream(outPath);

    // Convert {{input lower}} to {{output lower}}
    font.SaveToFormat(outStream, FontSavingFormats.{{output upper}});
{{< /app/font/converter >}}
{{< /blocks/products/pf/agp/feature-section>}}
{{< /blocks/products/pf/main-wrap-class>}}

{{< blocks/products/pf/feature-page-options pairs="cff-to-ttf cff-to-woff cff-to-woff2 eot-to-ttf eot-to-woff eot-to-woff2 ttf-to-woff type1-to-ttf type1-to-woff type1-to-woff2 woff2-to-ttf woff2-to-woff woff-to-ttf woff-to-woff2" >}}