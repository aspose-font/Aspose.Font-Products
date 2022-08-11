---
translation: true
template: /_templates/conversion-java.md
title: API chuyển đổi phông chữ | Java
url: /java/conversion/
description: Chức năng chuyển đổi tệp phông chữ Java. Chuyển đổi các phông chữ khác nhau như CFF, EOT, WOFF, TTF và Loại 1 với một vài dòng mã Java.
keywords: chuyển đổi phông chữ java, chuyển đổi phông chữ Java, trình che phông chữ java
family: font
platformtag: java
feature: conversion
---

{{<section banner>}}
---
h1: Chuyển đổi Phông chữ
h2: API chuyển đổi định dạng phông chữ cho Java. Chuyển đổi phông chữ WOFF2, TTF, EOT và CFF.
---

{{<section overview>}}
---
p1: API phông chữ Java có thể dễ dàng tải, lưu và chuyển đổi các phông chữ khác nhau như bộ sưu tập CFF, OpenType, Type1 và TrueType. Nó cung cấp cấu trúc dữ liệu phông chữ cùng với bất kỳ glyph nào cũng như thông tin mã hóa cho tất cả các loại phông chữ biểu thị ánh xạ giữa mã ký tự và mã nhận dạng glyph. API có thể hiển thị bất kỳ glyph hoặc văn bản mong muốn nào, cũng như các glyph đặc biệt, có thể được hiển thị bằng cách triển khai các giao diện sử dụng chức năng đồ họa đơn giản như điểm di chuyển, đường vẽ và đường cong, v.v.
p2: "Do tính chất đa dạng của các tiện ích, môi trường, một số hệ thống hoạt động và nhiều lĩnh vực khác sử dụng các định dạng phông chữ khác nhau để phục vụ các mục đích khác nhau như sử dụng các phông chữ khác nhau trên các trang web, ứng dụng và xuất bản. Đôi khi cần phải chuyển đổi một phông chữ này thành một phông chữ khác để đáp ứng yêu cầu hiển thị."
p3: "Chúng tôi cung cấp cho bạn Giải pháp Java Api hỗ trợ các phông chữ tiếp theo dưới dạng định dạng đầu ra: TrueType (TTF), Định dạng phông chữ mở trên web (WOFF và WOFF2), định dạng OpenType nhúng (EOT), Loại 1 và Định dạng phông chữ thu gọn (CFF)."
---

{{<section feature1>}}
---
title: Chuyển đổi TrueType Font sang Web Open Font Format phiên bản 2.0.
item1: API hỗ trợ các phông chữ khác nhau để đọc và viết, đây là [danh sách](https://docs.aspose.com/font/java/convert/#formats-supported-for-reading-andor-writing) để đọc và viết. Để xem xét chuyển đổi TTF sang WOFF2, quá trình là tải một phông chữ từ bất kỳ định dạng nào được hỗ trợ, Phông chữ TrueType cho tình huống hiện tại. Sử dụng phương thức [*SaveToFormat()*](https://reference.aspose.com/font/java/com.aspose.font/Font#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) của [Lớp phông chữ](https://reference.aspose.com/font/java/com.aspose.font/Font#save-java.lang.String-) có luồng đầu ra hai tham số và [*FontSavingFormats*](https://reference.aspose.com/font/java/com.aspose.font/FontSavingFormats) Liệt kê để chọn định dạng phông chữ đầu ra.
item2: Cuối cùng, gọi SaveToFormat () để lưu phông chữ vào bất kỳ định dạng đầu ra nào được hỗ trợ, hiện tại là định dạng WOFF2 của Định dạng phông chữ mở trên Web phiên bản 2.0.
item3: Để xem chức năng này được thực hiện trong một ứng dụng đa nền tảng thực tế, hãy truy cập [ứng dụng Aspose Font Converter](https://products.aspose.app/font/conversion). Ở đó, bạn cũng có thể tìm thấy nhiều khác [giải pháp API](https://products.aspose.app/font/application) để làm việc với phông chữ và văn bản.
item4: Truy cập [Tài liệu](https://docs.aspose.com/font/net/) để nhận tất cả thông tin cần thiết để bắt đầu làm việc với giải pháp, chẳng hạn như Hướng dẫn về các tính năng chính hoặc tập hợp các bài viết hướng dẫn bạn về phông chữ, Ghi chú phát hành, Hướng dẫn dành cho nhà phát triển và những thứ hữu ích khác.
---

{{<section codeexample>}}
---
title: Mã Java cho chuyển đổi CFF sang TTF
---