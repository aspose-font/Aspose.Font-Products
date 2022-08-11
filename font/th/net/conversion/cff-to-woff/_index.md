---
translation: true
template: /_templates/conversion-child-net.md
title: CFF เป็น WOFF Converter API |.NET
description: แปลง CFF เป็น WOFF โดยใช้ .NET API บน Windows รวมฟังก์ชันการแปลงฟอนต์ CFF ดั้งเดิมนี้เป็น WOFF เข้ากับโซลูชันของคุณเอง
keywords: cff ถึง woff api, โซลูชัน cff2woff, cff ถึง woff net
url: /net/conversion/cff-to-woff/
family: font
platformtag: net
feature: conversion
otherformats: TTF WOFF2
---

{{<section banner>}}
---
h1: แปลง CFF เป็น WOFF
h2: ฟังก์ชันการแปลง CFF เป็น WOFF สำหรับ C№ .NET API เพื่อแปลงแบบอักษร
---

{{<section overview>}}
---
p1: การแปลง CFF เป็น WOFF ภายในแอปพลิเคชันที่ใช้ .NET ด้วยโค้ดเพียงไม่กี่บรรทัด Font API Solution สำหรับ С# นั้นง่ายต่อการรวมเข้ากับผลิตภัณฑ์ของคุณ .NET API นี้จัดเตรียมโครงสร้างข้อมูลแบบอักษรพร้อมกับสัญลักษณ์ใดๆ รวมทั้งข้อมูลการเข้ารหัสสำหรับแบบอักษรทุกประเภทที่แสดงการจับคู่ระหว่างรหัสอักขระและตัวระบุสัญลักษณ์ API สามารถแสดงสัญลักษณ์หรือข้อความที่ต้องการได้ เช่นเดียวกับร่ายมนตร์พิเศษ ซึ่งสามารถแสดงผลได้โดยใช้อินเทอร์เฟซโดยใช้ฟังก์ชันกราฟิกที่เรียบง่าย เช่น จุดเคลื่อนที่ ขีดเส้น และเส้นโค้ง เป็นต้น
p2: "เนื่องจากธรรมชาติของแกดเจ็ต สภาพแวดล้อม ระบบปฏิบัติการบางส่วน และพื้นที่อื่น ๆ อีกมากมายจึงต้องใช้รูปแบบแบบอักษรที่แตกต่างกันเพื่อให้บริการตามวัตถุประสงค์ที่แตกต่างกัน เช่น การใช้แบบอักษรที่แตกต่างกันบนหน้าเว็บ แอปพลิเคชัน และการเผยแพร่ ดังนั้นบางครั้งคุณอาจต้องเผชิญกับความต้องการแปลงแบบอักษร CFF เป็นรูปแบบอื่นเพื่อให้ตรงกับการแสดงผลที่ต้องการ"
p3: "เราขอเสนอ С# .NET Api Solution ที่รองรับฟอนต์ถัดไปเป็นรูปแบบอินพุต: TrueType (TTF) และรูปแบบฟอนต์ Web Open (WOFF และ WOFF2)"
---

{{<section feature1>}}
---
title: 'การแปลง CFF เป็น WOFF บน C #'
item1: หากต้องการเรียนรู้เพิ่มเติมเกี่ยวกับสิ่งที่คุณต้องใช้ในการทำงานกับ API และข้อมูลพื้นฐานเกี่ยวกับแบบอักษรที่จะช่วยให้คุณเขียนโค้ดได้ ให้ไปที่[เอกสารประกอบ](https://docs.aspose.com/font/) และเลือกภาษาที่คุณเขียนโค้ด ใน.
item2: เปิดแบบอักษร CFF โดยใช้วิธีการ [*Open()*](https://reference.aspose.com/font/net/aspose.font/font/open/)
item3: ระบุการตั้งค่าเอาต์พุต WOFF
item4: แปลง CFF เป็น WOFF โดยใช้เมธอด [*SaveToFormat()*](https://reference.aspose.com/font/net/aspose.font/font/savetoformat/) และส่ง WOFF เป็น [FontSavingFormats](https://reference.aspose.com/font/net/aspose.font/fontsavingformats/)
---

{{<section feature2>}}
---
title: เริ่มต้นใช้งาน .NET Font API
item1: ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Font``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Font```
item2: หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/font/net)
item3: ดูตัวอย่างการใช้งานฟังก์ชันที่กล่าวถึงใน Aspose ข้ามแพลตฟอร์ม [CFF to WOFF Converter](https://products.aspose.app/font/conversion/cff-to-woff) ไปที่ที่เก็บ [GitHub](https://github.com/aspose-font/Aspose.Font-Documentation/tree/master/net-examples) ของเราเพื่อรับตัวอย่างโค้ดเพิ่มเติมเกี่ยวกับวิธีการทำงานกับ Font API Solution สำหรับ C# .NET.
---

{{<section codeexample>}}
---
title: ตัวอย่างโค้ด C# การแปลง CFF เป็น WOFF
---