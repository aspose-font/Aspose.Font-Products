---
translation: true
template: /_templates/conversion-java.md
title: API de conversion de police | Java
url: /java/conversion/
description: Fonctionnalité de conversion de fichiers de polices Java. Convertissez différentes polices telles que CFF, EOT, WOFF, TTF et Type 1 avec quelques lignes de code Java.
keywords: convertir les polices java, conversion de polices Java, convertisseur de polices java
family: font
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: Convertir les polices
h2: API de conversion de format de police pour Java. Convertissez les polices WOFF2, TTF, EOT et CFF.
---

{{<section overview>}}
---
p1: L'API de police Java peut facilement charger, enregistrer et convertir différentes polices telles que les collections CFF, OpenType, Type1 et TrueType. Il fournit une structure de données de police avec tout glyphe ainsi que des informations de codage pour tous les types de police représentant un mappage entre les codes de caractères et les identifiants de glyphe. L'API peut restituer n'importe quel glyphe ou texte souhaité, ainsi que des glyphes spéciaux, qui peuvent être rendus en implémentant des interfaces utilisant des fonctionnalités graphiques simples telles que déplacer un point, tracer une ligne et une courbe, etc.
p2: "En raison de la nature diversifiée des gadgets, des environnements, de quelques systèmes opérationnels et de nombreux autres domaines, différents formats de polices doivent être utilisés à des fins différentes, telles que l'utilisation de différentes polices sur les pages Web, les applications et la publication. Parfois, il est nécessaire de transformer une police en une autre pour répondre à l'affichage requis."
p3: "Nous vous proposons la solution Java Api qui prend en charge les polices suivantes en tant que formats de sortie : TrueType (TTF), Web Open Font Format (WOFF et WOFF2), Embedded OpenType format (EOT), Type 1 et Compact Font Format (CFF)."
---

{{<section feature1>}}
---
title: Conversion de la police TrueType au format Web Open Font version 2.0.
item1: L'API prend en charge différentes polices pour la lecture et l'écriture, voici la [liste](https://docs.aspose.com/font/java/convert/#formats-supported-for-reading-andor-writing) pour la lecture et l'écriture. Pour envisager la conversion TTF en WOFF2, le processus consiste à charger une police à partir de l'un des formats pris en charge, la police TrueType pour le scénario actuel. Utilisez la méthode [*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) de [Font class](https://reference.aspose.com/font/java/com.aspose.font/Font#save-java.lang.String-) ayant deux paramètres output stream et [*FontSavingFormats*](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) Énumération pour sélectionner le format de police de sortie.
item2: Enfin, appelez SaveToFormat() pour enregistrer les polices dans l'un des formats de sortie pris en charge, actuellement le format Web Open Font Format version 2.0 WOFF2.
item3: Pour voir cette fonctionnalité réalisée dans une application multiplateforme réelle, accédez à [application Aspose Font Converter](https://products.aspose.app/font/conversion). Vous y trouverez également de nombreuses autres [solutions API](https://products.aspose.app/font/applications) pour travailler avec les polices et le texte.
item4: Accédez à la [Documentation](https://docs.aspose.com/font/net/) pour obtenir toutes les informations nécessaires pour commencer à travailler avec la solution, comme les tutoriels pour les principales fonctionnalités ou l'ensemble des articles pour vous apprendre sur la police, les notes de version, le guide du développeur et d'autres choses utiles.
---

{{<section codeexample>}}
---
title: Code Java pour la conversion CFF en TTF
---
