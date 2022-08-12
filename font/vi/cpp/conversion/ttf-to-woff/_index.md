---
translation: true
template: /_templates/conversion-child-cpp.md
title: API chuyển đổi TTF sang WOFF | C ++
description: Chuyển đổi TTF sang Phông chữ WOFF bằng cách sử dụng API C ++ này. Chức năng Chuyển đổi hoạt động trên Windows và Linux và trong bất kỳ môi trường phát triển nào hỗ trợ C ++.
metakeywords: c ++ Giải pháp TTF sang WOFF, TTF sang WOFF c ++, Bộ mã phông chữ TTF sang WOFF cpp
url: /cpp/conversion/ttf-to-woff/
family: font
platformtag: cpp
feature: conversion
otherformats: WOFF2
---

{{<section banner>}}
---
h1: Chuyển đổi TTF sang WOFF
h2: Chức năng chuyển đổi TTF sang WOFF cho C ++. API để chuyển đổi phông chữ.
---

{{<section overview>}}
---
p1: Chuyển đổi TTF sang WOFF trong các ứng dụng dựa trên С ++ chỉ với một vài dòng mã. Giải pháp Font API cho С ++ thực sự dễ dàng tích hợp vào sản phẩm của bạn. API C ++ này cung cấp cấu trúc dữ liệu phông chữ cùng với bất kỳ glyph nào cũng như thông tin mã hóa cho tất cả các loại phông chữ biểu thị ánh xạ giữa mã ký tự và mã nhận dạng glyph. API có thể hiển thị bất kỳ glyph hoặc văn bản mong muốn nào, cũng như các glyph đặc biệt, có thể được hiển thị bằng cách triển khai các giao diện sử dụng chức năng đồ họa đơn giản như điểm di chuyển, đường vẽ và đường cong, v.v.
p2: "Do tính chất đa dạng của các tiện ích, môi trường, một số hệ thống hoạt động và nhiều lĩnh vực khác sử dụng các định dạng phông chữ khác nhau để phục vụ các mục đích khác nhau như sử dụng các phông chữ khác nhau trên các trang web, ứng dụng và xuất bản. Vì vậy, đôi khi bạn có thể phải chuyển đổi phông chữ TTF thành một phông chữ khác có định dạng khác để đáp ứng yêu cầu hiển thị."
p3: "Chúng tôi cung cấp cho bạn Giải pháp С ++ Api hỗ trợ các phông chữ tiếp theo làm định dạng đầu vào: TrueType (TTF) và Định dạng phông chữ mở trên web (WOFF và WOFF2)."
---

{{<section feature1>}}
---
title: Chuyển đổi TTF sang WOFF trên C ++
item1: Để tìm hiểu thêm về tất cả những gì bạn cần để làm việc với API và thông tin cơ bản về các phông chữ sẽ giúp bạn viết mã chúng, hãy truy cập [Tài liệu](https://docs.aspose.com/font/) và chọn ngôn ngữ bạn viết mã Trong.
item2: Mở phông chữ TTF bằng phương pháp  [*Open()*](https://reference.aspose.com/font/cpp/class/aspose.font.font#ac2387bf04ccb5bac51cf37984d4ebf33).
item3: Chỉ định cài đặt đầu ra WOFF.
item4: Chuyển đổi TTF thành WOFF bằng [*SaveToFormat()*](https://reference.aspose.com/font/cpp/class/aspose.font.font#a670ea97404fd72c2e51b0e8c543c8a45) Phương thức và chuyển WOFF dưới dạng [FontSavingFormats](https://reference.aspose.com/font/cpp/namespace/aspose.font#a93d0dcc7c00f5c7027d60e14a5433c74).
---

{{<section feature2>}}
---
title: Bắt đầu với API phông chữ C ++
item1: Cài đặt từ dòng lệnh với tên `` nuget install Aspose.Font.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Font.Cpp ''.
item2: Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/font/cpp/).
item3: Xem ví dụ về việc thực hiện chức năng được đề cập trong Aspose đa nền tảng [Bộ chuyển đổi TTF sang WOFF](https://products.aspose.app/font/conversion/ttf-to-woff). Truy cập kho lưu trữ [GitHub](https://github.com/aspose-font/Aspose.Font-Documentation/tree/master/cpp-examples) của chúng tôi để nhận thêm các ví dụ mã về cách làm việc với Giải pháp Font API cho C ++.
---

{{<section codeexample>}}
---
title: Ví dụ về mã C ++ chuyển đổi TTF sang WOFF
---