﻿---
translation: true
template: /_templates/conversion-java.md
title: API μετατροπής γραμματοσειράς | Ιάβα
url: /java/conversion/
description: Λειτουργία μετατροπής αρχείων γραμματοσειράς Java. Μετατρέψτε διαφορετικές γραμματοσειρές όπως CFF, EOT, WOFF, TTF και Type 1 με μερικές γραμμές κώδικα Java.
keywords: μετατροπή γραμματοσειρών java, μετατροπή γραμματοσειρών Java, κάλυψη γραμματοσειρών java
family: font
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: Μετατροπή γραμματοσειρών
h2: API μετατροπέα μορφής γραμματοσειράς για Java. Μετατρέψτε τις γραμματοσειρές WOFF2, TTF, EOT και CFF.
---

{{<section overview>}}
---
p1: Το Java γραμματοσειράς API μπορεί εύκολα να φορτώσει, να αποθηκεύσει και να μετατρέψει διαφορετικές γραμματοσειρές όπως συλλογές CFF, OpenType, Type1 και TrueType. Παρέχει δομή δεδομένων γραμματοσειράς μαζί με οποιοδήποτε γλυφό, καθώς και πληροφορίες κωδικοποίησης για όλους τους τύπους γραμματοσειρών που αντιπροσωπεύουν μια αντιστοίχιση μεταξύ κωδικών χαρακτήρων και αναγνωριστικών γλυφών. Το API μπορεί να αποδώσει οποιοδήποτε επιθυμητό γλυφό ή κείμενο, καθώς και ειδικούς γλυφούς, οι οποίοι μπορούν να αποδοθούν με την υλοποίηση διεπαφών χρησιμοποιώντας απλές λειτουργίες γραφικών όπως σημείο κίνησης, γραμμή σχεδίασης και καμπύλη κ.λπ.
p2: "Λόγω της ποικιλόμορφης φύσης των gadget, των περιβαλλόντων, ορισμένων λειτουργικών συστημάτων και πολλών άλλων περιοχών για χρήση διαφορετικών μορφών γραμματοσειρών για την εξυπηρέτηση διαφορετικών σκοπών, όπως η χρήση διαφορετικών γραμματοσειρών σε ιστοσελίδες, εφαρμογές και δημοσίευση. Μερικές φορές υπάρχει ανάγκη μετατροπής μιας γραμματοσειράς σε άλλη για να καλύψει την απαιτούμενη εμφάνιση."
p3: "Σας προσφέρουμε Java Api Solution που υποστηρίζει τις επόμενες γραμματοσειρές ως μορφές εξόδου: TrueType (TTF), Web Open Font Format (WOFF και WOFF2), Embedded OpenType format (EOT), Type 1, and Compact Font Format (CFF)."
---

{{<section feature1>}}
---
title: Μετατροπή γραμματοσειράς TrueType σε Web Ανοιχτή μορφή γραμματοσειράς έκδοση 2.0.
item1: Το API υποστηρίζει διαφορετικές γραμματοσειρές για ανάγνωση και γραφή, εδώ είναι η [λίστα](https://docs.aspose.com/font/java/convert/#formats-supported-for-reading-andor-writing) για ανάγνωση και γραφή. Για να εξετάσετε τη μετατροπή TTF σε WOFF2, η διαδικασία είναι να φορτώσετε μια γραμματοσειρά από οποιαδήποτε από τις υποστηριζόμενες μορφές, τη γραμματοσειρά TrueType για το τρέχον σενάριο. Χρησιμοποιήστε τη μέθοδο [*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) του [Font class](https://reference.aspose.com/font/java/com.aspose.font/Font#save-java.lang.String-) με ροή εξόδου δύο παραμέτρων και [*FontSavingFormats*](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) Αριθμός για την επιλογή της μορφής γραμματοσειράς εξόδου.
item2: Τέλος, καλέστε το SaveToFormat() για να αποθηκεύσετε γραμματοσειρές σε οποιαδήποτε από τις μορφές εξόδου που υποστηρίζονται, αυτήν τη στιγμή μορφή Web Open Font Format έκδοση 2.0 WOFF2.
item3: Για να δείτε αυτή τη λειτουργικότητα να υλοποιείται σε μια πραγματική εφαρμογή πολλαπλών πλατφορμών, μεταβείτε στην [Aspose Font Converter app](https://products.aspose.app/font/conversion). Εκεί μπορείτε επίσης να βρείτε πολλές ακόμη [λύσεις API](https://products.aspose.app/font/applications) για να εργαστείτε με γραμματοσειρές και κείμενο.
item4: Μεταβείτε στην [Τεκμηρίωση](https://docs.aspose.com/font/net/) για να λάβετε όλες τις απαραίτητες πληροφορίες για να ξεκινήσετε να εργάζεστε με τη λύση, όπως τα Εκπαιδευτικά προγράμματα για τις κύριες λειτουργίες ή το σύνολο άρθρων που θα σας διδάξουν σχετικά με τη γραμματοσειρά, τις Σημειώσεις έκδοσης, τον Οδηγό προγραμματιστή και άλλα χρήσιμα πράγματα.
---

{{<section codeexample>}}
---
title: Κώδικας Java για μετατροπή CFF σε TTF
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