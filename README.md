# 📘 HƯỚNG DẪN SỬ DỤNG AUTHENTIQR - COMPANY PORTAL

## Dành cho Quản trị viên Công ty (Company Admin)

> **Phiên bản:** Tháng 7/2026  
> **Đối tượng:** Quản trị viên công ty sử dụng vai trò **Company Admin**  
> **Mục đích:** Hướng dẫn từng bước cách sử dụng tất cả các tính năng của hệ thống AuthentiQR

---

## 📑 MỤC LỤC

| STT | Nội dung | Trang |
|-----|----------|-------|
| 1 | [Giới thiệu tổng quan về AuthentiQR](#1-giới-thiệu-tổng-quan-về-authentiqr) | — |
| 2 | [Đăng nhập vào hệ thống](#2-đăng-nhập-vào-hệ-thống) | — |
| 3 | [Cấu trúc giao diện chính](#3-cấu-trúc-giao-diện-chính) | — |
| 4 | [Tổng quan (Dashboard)](#4-tổng-quan-dashboard) | — |
| 5 | [Quản lý mã QR](#5-quản-lý-mã-qr) | — |
| 6 | [Quản lý sản phẩm](#6-quản-lý-sản-phẩm) | — |
| 7 | [Quản lý danh mục](#7-quản-lý-danh-mục) | — |
| 8 | [Admin Scan (Quét mã QR)](#8-admin-scan-quét-mã-qr) | — |
| 9 | [Xuất file](#9-xuất-file) | — |
| 10 | [Lịch sử sửa QR](#10-lịch-sử-sửa-qr) | — |
| 11 | [Cảnh báo hàng giả](#11-cảnh-báo-hàng-giả) | — |
| 12 | [Lịch sử quét mã](#12-lịch-sử-quét-mã) | — |
| 13 | [Báo cáo & Thống kê](#13-báo-cáo--thống-kê) | — |
| 14 | [Thanh toán & Cước phí](#14-thanh-toán--cước-phí) | — |
| 15 | [Hồ sơ công ty](#15-hồ-sơ-công-ty) | — |
| 16 | [Thông báo](#16-thông-báo) | — |
| 17 | [Cài đặt hệ thống](#17-cài-đặt-hệ-thống) | — |
| 18 | [Hồ sơ cá nhân](#18-hồ-sơ-cá-nhân) | — |
| 19 | [Câu hỏi thường gặp (FAQ)](#19-câu-hỏi-thường-gặp-faq) | — |

---

## 1. Giới thiệu tổng quan về AuthentiQR

### AuthentiQR là gì?

**AuthentiQR** là hệ thống quản lý xác thực sản phẩm bằng mã QR. Hiểu đơn giản, hệ thống này giúp công ty của bạn:

- 🏷️ **Tạo mã QR** cho từng sản phẩm để khách hàng có thể quét và xác minh hàng chính hãng
- 🔍 **Theo dõi** ai đã quét mã, ở đâu, bằng thiết bị gì
- ⚠️ **Phát hiện hàng giả** khi có hành vi quét bất thường
- 📊 **Xem báo cáo** thống kê chi tiết về hoạt động quét mã
- 💰 **Quản lý chi phí** sử dụng dịch vụ

### Vai trò Company Admin có thể làm gì?

Với vai trò **Company Admin** (Quản trị viên công ty), bạn có toàn quyền quản lý:

| Quyền hạn | Mô tả |
|-----------|-------|
| Quản lý sản phẩm | Thêm, sửa, xóa sản phẩm và danh mục |
| Tạo mã QR | Tạo lô mã QR mới cho sản phẩm |
| Xem báo cáo | Xem toàn bộ thống kê và báo cáo |
| Quản lý nhân sự | Xem thông tin tài khoản trong hệ thống |
| Cài đặt hệ thống | Tùy chỉnh giao diện, thông báo, tích hợp API |
| Thanh toán | Quản lý ví tiền và hóa đơn |

---

## 2. Đăng nhập vào hệ thống

### Bước 1: Mở trình duyệt web
Mở trình duyệt web (Chrome, Firefox, Edge...) và nhập địa chỉ trang web AuthentiQR mà công ty bạn được cung cấp.

### Bước 2: Nhập thông tin đăng nhập
- **Email:** Nhập email tài khoản công ty bạn (ví dụ: `company@authentiqr.vn`)
- **Mật khẩu:** Nhập mật khẩu được cấp

### Bước 3: Nhấn nút "Đăng nhập"
Sau khi đăng nhập thành công, bạn sẽ được chuyển đến **Trang Tổng Quan (Dashboard)**.

> [!TIP]
> Nếu quên mật khẩu, hãy liên hệ với bộ phận hỗ trợ kỹ thuật để được đặt lại mật khẩu.

---

## 3. Cấu trúc giao diện chính

Sau khi đăng nhập, giao diện chính gồm 3 phần:

![Giao diện Dashboard](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/01_dashboard.png)

### 🔵 Thanh bên trái (Sidebar) — Menu điều hướng

Đây là nơi bạn chuyển giữa các trang. Menu được chia thành các nhóm:

| Nhóm | Các mục |
|------|---------|
| **HỆ THỐNG QR** | Quản lý mã QR, Quản lý sản phẩm, Quản lý danh mục, Admin Scan, Xuất file |
| **VẬN HÀNH KHO** | Lịch sử sửa QR |
| **AN NINH & BÁO CÁO** | Cảnh báo hàng giả, Lịch sử quét mã, Báo cáo & Thống kê |
| **HỆ THỐNG** | Thanh toán & Cước phí, Hồ sơ công ty, Thông báo, Cài đặt hệ thống, Hồ sơ cá nhân |

### 🔵 Thanh trên cùng (Header)

Hiển thị các thông tin quan trọng:
- **Số dư ví:** Hiển thị số tiền trong ví công ty (ví dụ: `75.773.460 đ`)
- **Tên đầu số IP:** Hiển thị địa chỉ IP kết nối
- **Ngôn ngữ:** Cho phép chuyển đổi ngôn ngữ (VI = Tiếng Việt)
- **Thông báo:** Biểu tượng chuông 🔔 hiện số thông báo chưa đọc
- **Avatar:** Nhấn vào để xem hồ sơ cá nhân hoặc đăng xuất

### 🔵 Vùng nội dung chính (Main Content)

Đây là phần chiếm diện tích lớn nhất, hiển thị nội dung của trang bạn đang xem.

---

## 4. Tổng quan (Dashboard)

> **Đường dẫn menu:** Nhấn vào **"Tổng quan"** ở thanh bên trái

Trang Tổng quan là "bảng điều khiển" chính, cho bạn cái nhìn toàn diện về hoạt động của hệ thống.

![Trang Tổng quan](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/01_dashboard.png)

### 4.1. Hai tab chính

Trang Dashboard có **2 tab** ở phía trên:

| Tab | Mô tả |
|-----|-------|
| **Tổng quan Hệ thống** | Hiển thị tổng quan hoạt động sản xuất và quét mã |
| **Chi tiết Khách hàng** | Hiển thị thông tin phân tích về khách hàng/người tiêu dùng |

### 4.2. Tab "Tổng quan Hệ thống"

#### Các thẻ thống kê nhanh (KPI Cards)

Ở phía trên cùng có 4 thẻ thông tin quan trọng:

| Thẻ | Ý nghĩa | Ví dụ |
|-----|---------|-------|
| 🖥️ **Tổng số sản phẩm** | Số sản phẩm đang kinh doanh trong hệ thống | `8` (+8.3%) |
| 📦 **Tổng số lô** | Số lô hàng đã xuất và đóng gói | `10` (+12.4%) |
| 🔄 **Tổng lượt quét** | Tổng số lần mã QR được quét bởi người dùng | `32` (+24.1%) |
| ⚠️ **Cảnh báo hàng giả** | Số cảnh báo nghi ngờ hàng giả | `2` (+200%) |

> [!NOTE]
> Các con số phần trăm (%) màu xanh lá biểu thị **tăng**, màu đỏ biểu thị **giảm** so với kỳ trước.

#### Phễu chuyển đổi Scan-to-Sale

Biểu đồ này giúp bạn theo dõi hành trình sản phẩm:
- **Sản xuất:** Tổng mã QR đã tạo (ví dụ: 2,044,962)
- **Khách quét:** Số lượt khách hàng quét mã (ví dụ: 18)
- **Khách xác nhận:** Số lượt xác nhận chính hãng thành công (ví dụ: 1)

#### Biểu đồ "Xu hướng quét mã"

- Hiển thị số lượt quét theo từng ngày trong tuần
- **Đường xanh đậm (Hợp lệ):** Lượt quét bình thường
- **Đường đỏ chấm (Nghi ngờ):** Lượt quét có dấu hiệu bất thường

#### Lượt quét gần đây

Danh sách các lần quét mã gần nhất, hiển thị:
- Tên người quét (ví dụ: "CONSUMER quét HELLOWORLD")
- Thời gian quét (ví dụ: "12 phút trước")

#### Bản đồ phân bố quét mã

Bản đồ hiển thị vị trí địa lý nơi mã QR được quét, giúp bạn biết khách hàng đang ở đâu.

#### Thư mục Cảnh báo

Hiển thị danh sách sản phẩm có cảnh báo bất thường với các mức:
- 🔴 **HIGH (Cao):** Nguy cơ cao, cần xử lý ngay
- 🟡 **MEDIUM (Trung bình):** Cần theo dõi

#### Top sản phẩm / Thùng hàng / Lô hàng được quét nhiều nhất

3 bảng xếp hạng giúp bạn biết sản phẩm nào được quét nhiều nhất.

#### Hoạt động hệ thống gần đây (LOGS)

Bảng hiển thị các hoạt động gần nhất như:
- **LOGIN:** Người dùng đăng nhập
- **LOGOUT:** Người dùng đăng xuất
- Thời gian và tài khoản thực hiện

---

## 5. Quản lý mã QR

> **Đường dẫn menu:** HỆ THỐNG QR → **Quản lý mã QR**

Đây là nơi bạn quản lý tất cả mã QR đã tạo, được sắp xếp theo từng **lô hàng**.

![Quản lý mã QR](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/02_qr_management.png)

### 5.1. Thông tin tổng quan

Phía trên trang hiển thị các thẻ thống kê:
- **2,044,962 Tổng:** Tổng số mã QR đã tạo
- **12 Đang hoạt động:** Số lô hàng đang hoạt động
- **0 Đã khóa:** Số lô bị khóa
- **10 THÙNG HÀNG:** Tổng số thùng hàng

### 5.2. Tìm kiếm mã QR

- **Ô tìm kiếm:** Gõ tên lô, mã sản phẩm để tìm nhanh
- **Nút "THÙNG HÀNG":** Lọc xem theo thùng hàng
- **Nút "Thư mục":** Lọc xem theo thư mục

### 5.3. Bảng danh sách mã QR

| Cột | Ý nghĩa |
|-----|---------|
| **Lô hàng** | Tên lô và mã lô (ví dụ: "Test Batch Dynamic Price" - BATCH-SYS-03-07-2026-2) |
| **Sản phẩm** | Tên sản phẩm liên kết (ví dụ: "Demo CoC Product") |
| **Trạng thái** | Tình trạng lô: `Mới tạo` (xanh dương) hoặc `Đang hoạt động` (xanh lá) |
| **Thùng hàng** | Số thùng hàng trong lô |
| **Sản phẩm** | Số lượng mã QR trong lô (ví dụ: 200,000; 321,709) |
| **Ngày tạo** | Ngày tạo lô hàng |
| **Thao tác** | Các nút: 👁️ Xem chi tiết, ⬇️ Tải xuống |

### 5.4. Tạo mã QR mới

1. Nhấn nút **"+ Tạo mã QR mới"** (góc phải trên)
2. Điền thông tin lô hàng theo biểu mẫu
3. Chọn sản phẩm cần liên kết
4. Nhấn **"Tạo"** để hoàn tất

### 5.5. Xuất danh sách ra Excel

Nhấn nút **"Xuất Excel"** để tải file Excel chứa toàn bộ danh sách mã QR.

---

## 6. Quản lý sản phẩm

> **Đường dẫn menu:** HỆ THỐNG QR → **Quản lý sản phẩm**

Trang này giúp bạn quản lý danh sách các sản phẩm trong hệ thống — đây là thông tin mà khách hàng sẽ thấy khi quét mã QR.

![Quản lý sản phẩm](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/03_product_management.png)

### 6.1. Tìm kiếm và lọc

- **Ô tìm kiếm:** Tìm theo tên, SKU (mã sản phẩm), hoặc danh mục
- **Lọc trạng thái:** Chọn "Tất cả" hoặc chỉ xem sản phẩm đang hoạt động

### 6.2. Cây danh mục bên trái

Bên trái có danh sách các danh mục sản phẩm. Nhấn vào danh mục để lọc sản phẩm theo nhóm:
- 📦 Tất cả sản phẩm
- Anh Longgg
- Điện thoại
- Mỹ phẩm
- Thiết bị di động

### 6.3. Bảng sản phẩm

| Cột | Ý nghĩa |
|-----|---------|
| **Sản phẩm** | Tên sản phẩm kèm hình ảnh (ví dụ: SAMSUNG, Xiaomi 17 Ultra) |
| **SKU** | Mã sản phẩm nội bộ (ví dụ: SAM-S24, SKU-001) |
| **Danh mục** | Nhóm sản phẩm thuộc về (ví dụ: ĐIỆN THOẠI, ANH LONG) |
| **Đơn vị** | Đơn vị tính (ví dụ: Cái) |
| **HSD Khuyến nghị** | Hạn sử dụng khuyến nghị (ví dụ: 24 tháng) |
| **Trạng thái** | `ĐANG HOẠT ĐỘNG` (xanh lá) |
| **Thao tác** | ✏️ Sửa, 👁️ Xem, 🗑️ Xóa |

### 6.4. Thêm sản phẩm mới

1. Nhấn nút **"+ THÊM SẢN PHẨM"** (góc phải trên)
2. Điền đầy đủ thông tin sản phẩm
3. Chọn danh mục phù hợp
4. Tải lên hình ảnh sản phẩm
5. Nhấn **"Lưu"** để hoàn tất

### 6.5. Các nút khác

- **"XUẤT DỮ LIỆU":** Tải danh sách sản phẩm ra file
- **"QUẢN LÝ DANH MỤC":** Chuyển nhanh đến trang quản lý danh mục

---

## 7. Quản lý danh mục

> **Đường dẫn menu:** HỆ THỐNG QR → **Quản lý danh mục**

Danh mục là các **nhóm** để phân loại sản phẩm (ví dụ: "Điện thoại", "Mỹ phẩm").

![Quản lý danh mục](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/04_category_management.png)

### 7.1. Bảng danh mục

| Cột | Ý nghĩa |
|-----|---------|
| **Tên danh mục** | Tên nhóm sản phẩm (ví dụ: "Điện thoại", "Mỹ phẩm") |
| **Mô tả danh mục** | Mô tả ngắn gọn (hoặc "Không có mô tả") |
| **Ngày tạo** | Ngày danh mục được tạo |
| **Thao tác** | ✏️ Sửa, 🗑️ Xóa |

### 7.2. Thêm danh mục mới

1. Nhấn nút **"+ THÊM DANH MỤC"** (góc phải trên)
2. Nhập tên danh mục
3. Nhập mô tả (không bắt buộc)
4. Nhấn **"Lưu"**

### 7.3. Tìm kiếm danh mục

Sử dụng ô **"Tìm theo tên danh mục..."** phía trên để tìm nhanh.

---

## 8. Admin Scan (Quét mã QR)

> **Đường dẫn menu:** HỆ THỐNG QR → **Admin Scan**

Trang này cho phép quản trị viên tra cứu thông tin chi tiết của một mã QR cụ thể.

![Admin Scan](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/05_admin_scan.png)

### 8.1. Hai phương thức quét

| Phương thức | Cách sử dụng |
|-------------|-------------|
| **Nhập mã** | Gõ trực tiếp mã QR (Short Code hoặc Payload) vào ô nhập liệu |
| **Camera** | Sử dụng camera máy tính/webcam để quét mã QR |

### 8.2. Cách sử dụng

1. Chọn tab **"Nhập mã"** hoặc **"Camera"**
2. Nếu chọn "Nhập mã": Gõ mã QR vào ô **"Nhập mã QR..."**
3. Nhấn nút **"Tra cứu dữ liệu"**
4. Kết quả sẽ hiển thị chi tiết thông tin mã QR bao gồm: thông tin sản phẩm, lịch sử quét, chuỗi cung ứng, cảnh báo bảo mật

> [!TIP]
> Kết quả hiển thị phụ thuộc vào cấu hình Admin Scan trong Cài đặt hệ thống. Bạn có thể bật/tắt các khối dữ liệu: Dữ liệu thô, Lịch sử quét, Chuỗi cung ứng, Cảnh báo bảo mật.

---

## 9. Xuất file

> **Đường dẫn menu:** HỆ THỐNG QR → **Xuất file**

Trang này giúp bạn tạo file Excel từ dữ liệu mã QR và theo dõi tiến độ xuất file.

![Xuất file](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/06_export.png)

### 9.1. Thẻ thống kê

| Thẻ | Ý nghĩa |
|-----|---------|
| **Tổng cộng** | Tổng số yêu cầu xuất file |
| **Đang xử lý** | Số file đang được tạo |
| **Thành công** | Số file đã tạo xong |
| **Thất bại** | Số file bị lỗi |

### 9.2. Bảng lịch sử xuất file

| Cột | Ý nghĩa |
|-----|---------|
| **Trạng thái** | Biểu tượng trạng thái (✅ thành công, ❌ thất bại, ⏳ đang xử lý) |
| **Mã Job / Loại** | Mã công việc và loại xuất file |
| **Lô hàng** | Lô hàng được xuất |
| **Số lượng QR** | Số mã QR trong file |
| **Tiến độ / Trạng thái** | Tiến độ xử lý hoặc thông báo lỗi |
| **Thời gian** | Thời điểm yêu cầu xuất file |
| **Hành động** | Tải file xuống (nếu thành công) |

### 9.3. Xuất file mới

1. Nhấn nút **"+ Xuất file mới"** (góc phải trên)
2. Chọn lô hàng cần xuất
3. Chờ hệ thống xử lý

> [!IMPORTANT]
> File được lưu tạm trên server. Nếu không tải xuống ngay, file có thể bị xóa khi server khởi động lại.

---

## 10. Lịch sử sửa QR

> **Đường dẫn menu:** VẬN HÀNH KHO → **Lịch sử sửa QR**

Trang này ghi lại toàn bộ lịch sử thay đổi thông tin của mã QR — giúp kiểm tra ai đã sửa gì, khi nào.

![Lịch sử sửa QR](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/07_qr_edit_history.png)

### 10.1. Bộ lọc tìm kiếm

| Bộ lọc | Mô tả |
|--------|-------|
| **Tìm kiếm chung** | Tìm theo nội dung, lý do thay đổi |
| **Mã QR** | Lọc theo mã lô hàng (BATCH-...) hoặc thùng (BOX-...) |
| **Trường thay đổi** | Lọc theo loại trường bị sửa |

### 10.2. Bảng lịch sử

| Cột | Ý nghĩa |
|-----|---------|
| **Thời gian** | Ngày giờ chỉnh sửa (ví dụ: 09:50:08 01/07/2026) |
| **Mã QR** | Mã QR bị sửa đổi, kèm nhãn `BATCH` (lô) hoặc `BOX` (thùng) |
| **Trường thông tin** | Trường nào bị thay đổi (ví dụ: "Sản phẩm liên kết", "Hạn sử dụng", "Xuất xứ", "Thương hiệu") |
| **Giá trị cũ** | Giá trị trước khi sửa |
| **Giá trị mới** | Giá trị sau khi sửa |
| **Lý do** | Lý do thay đổi |
| **Người sửa** | Email và ID người thực hiện |

> [!NOTE]
> Nhấn nút **"LỌC"** (màu xanh đậm) để áp dụng bộ lọc, hoặc **"XÓA LỌC"** để xóa bộ lọc.

---

## 11. Cảnh báo hàng giả

> **Đường dẫn menu:** AN NINH & BÁO CÁO → **Cảnh báo hàng giả**

Đây là trang rất quan trọng — giúp bạn phát hiện và xử lý các trường hợp mã QR bị nghi ngờ làm giả.

![Cảnh báo hàng giả](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/08_counterfeit_alerts.png)

### 11.1. Thẻ mức độ nghiêm trọng

Phía trên trang có 3 thẻ cảnh báo được phân loại theo mức độ:

| Thẻ | Mức độ | Ý nghĩa |
|-----|--------|---------|
| 🔴 **Nghiêm trọng** | Cao | Rất có thể là hàng giả, cần hành động ngay |
| 🟡 **Trung bình** | Vừa | Có dấu hiệu bất thường, cần theo dõi |
| 🔵 **Thấp** | Thấp | Có một số dấu hiệu nhẹ, có thể do lỗi người dùng |

### 11.2. Bộ lọc tìm kiếm

| Bộ lọc | Mô tả |
|--------|-------|
| **Tìm kiếm chung** | Tìm theo mã QR hoặc tên sản phẩm |
| **Mức độ nghiêm trọng** | Lọc theo mức Nghiêm trọng, Trung bình, hoặc Thấp |
| **Trạng thái xử lý** | Lọc theo trạng thái xử lý |

### 11.3. Bảng cảnh báo

| Cột | Ý nghĩa |
|-----|---------|
| **Mức độ** | Biểu tượng và màu sắc thể hiện mức nghiêm trọng |
| **Mã QR** | Mã QR bị nghi ngờ |
| **Sản phẩm** | Sản phẩm liên quan |
| **Lý do bất thường** | Nguyên nhân hệ thống phát hiện (ví dụ: quét quá nhiều lần, quét từ vị trí bất thường) |
| **Số lượt quét** | Tổng số lượt quét gây nghi ngờ |
| **Thời gian** | Thời điểm phát hiện |
| **Trạng thái** | Trạng thái xử lý (Đang chờ, Đã xử lý, v.v.) |

> [!WARNING]
> Khi nhận được cảnh báo mức **"Nghiêm trọng"**, bạn nên kiểm tra ngay và có biện pháp xử lý (liên hệ nhà phân phối, thu hồi sản phẩm nếu cần).

---

## 12. Lịch sử quét mã

> **Đường dẫn menu:** AN NINH & BÁO CÁO → **Lịch sử quét mã**

Trang này hiển thị **toàn bộ** lịch sử quét mã QR từ mọi nguồn (khách hàng, nhân viên, đại lý).

![Lịch sử quét mã](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/09_scan_history.png)

### 12.1. Thẻ thống kê

| Thẻ | Ý nghĩa |
|-----|---------|
| 📊 **Tổng lượt quét** | Tổng số lần quét (ví dụ: 32) |
| ✅ **Mã QR đã quét** | Số mã QR riêng biệt đã được quét (ví dụ: 18) |
| 🔄 **Quét lặp lại** | Số lần quét lặp cùng một mã |
| ⚠️ **Nghi ngờ bất thường** | Số lượt quét có dấu hiệu bất thường |

### 12.2. Bộ lọc chi tiết

| Bộ lọc | Mô tả |
|--------|-------|
| **Tìm kiếm mã QR** | Gõ mã QR cần tìm |
| **Loại sự kiện** | Lọc theo loại sự kiện quét |
| **Người thực hiện** | Lọc theo ai đã quét |
| **Khoảng thời gian** | Chọn khoảng thời gian từ — đến |

### 12.3. Bảng chi tiết quét

| Cột | Ý nghĩa |
|-----|---------|
| **Mã QR** | Mã QR được quét (ví dụ: SP-SYS-22-06-2026-1-1-916) |
| **Loại sự kiện** | Loại quét: `NGƯỜI TIÊU DÙNG QUÉT` (xanh dương) |
| **Vị trí** | Nơi quét (ví dụ: "Phường Tân Phú, TP Thủ Đức" hoặc địa chỉ IP) |
| **Thời gian** | Ngày giờ quét chính xác |
| **Người thực hiện** | Vai trò người quét: `NGƯỜI TIÊU DÙNG` hoặc `COMPANY_ADMIN` |
| **Thiết bị** | Loại thiết bị: 📱 Mobile hoặc 💻 Chrome |

### 12.4. Xuất dữ liệu

Nhấn nút **"XUẤT CSV"** (góc phải trên) để tải toàn bộ lịch sử quét ra file CSV.

---

## 13. Báo cáo & Thống kê

> **Đường dẫn menu:** AN NINH & BÁO CÁO → **Báo cáo & Thống kê**

Trang báo cáo tổng hợp giúp bạn đánh giá hiệu quả hệ thống và phát hiện vấn đề.

![Báo cáo & Thống kê](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/10_reports.png)

### 13.1. Thẻ thống kê tổng quan

| Thẻ | Ý nghĩa | Giá trị |
|-----|---------|---------|
| 📊 **Tổng lượt quét** | Tổng số quét toàn hệ thống | 14,280 (+18%) |
| ⚠️ **Cảnh báo hàng giả** | Số cảnh báo nghi hàng giả | 17 (-5%) |
| 📦 **Sản phẩm theo dõi** | Số sản phẩm đang giám sát | 5 (+0%) |
| ✅ **Tỷ lệ xác thực** | Tỷ lệ xác thực thành công | 97.5% (+2%) |

### 13.2. Biểu đồ "Xu hướng quét mã theo tháng"

- **Trục ngang:** Tháng 1 → Tháng 12
- **Đường xanh (Hợp lệ):** Số quét hợp lệ — tăng dần qua các tháng
- **Đường đỏ chấm (Cảnh báo):** Số quét bị cảnh báo

### 13.3. Top sản phẩm được quét

Bảng xếp hạng sản phẩm được quét nhiều nhất:
| Sản phẩm | Tỷ lệ |
|----------|--------|
| Mỹ phẩm dưỡng da cao cấp | 42% |
| Thực phẩm chức năng Omega | 28% |
| Rượu vang đỏ Pháp Reserve | 15% |
| Đồng hồ cao cấp Thụy Sĩ | 10% |
| Túi xách da thật Italy | 5% |

### 13.4. Khu vực nguy cơ cao

Bảng hiển thị các khu vực có nhiều cảnh báo hàng giả:

| Khu vực | Số cảnh báo | Mức độ | Xu hướng | Hành động |
|---------|-------------|--------|----------|-----------|
| TP. Hồ Chí Minh | 8 | 🔴 CAO | ↗️ Tăng | Xem cảnh báo |
| Hải Phòng | 5 | 🟡 TRUNG BÌNH | ↗️ Tăng | Xem cảnh báo |
| Bình Dương | 3 | 🟡 TRUNG BÌNH | ↘️ Giảm | Xem cảnh báo |
| Vũng Tàu | 1 | 🔵 THẤP | — Ổn định | Xem cảnh báo |

### 13.5. Xuất báo cáo

Nhấn nút **"Xuất Excel"** để tải báo cáo ra file Excel.

---

## 14. Thanh toán & Cước phí

> **Đường dẫn menu:** HỆ THỐNG → **Thanh toán & Cước phí**

Đây là nơi bạn quản lý tài chính, theo dõi chi phí sử dụng và nạp tiền vào ví.

![Thanh toán & Cước phí](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/11_billing.png)

### 14.1. Hình thức thanh toán

Hệ thống sử dụng phương thức **Trả cước cuối kỳ (Postpaid)**:
- Cước được tính dựa trên số mã QR tạo trong kỳ
- Hóa đơn phát hành vào cuối mỗi chu kỳ thanh toán

### 14.2. Nạp tiền ví (Demo)

- Nhập **Số tiền (VND)** và **Ghi chú** vào ô tương ứng
- Nhấn **"Xác nhận nạp tiền ví"** để nạp

### 14.3. Hóa đơn chưa trả

Hiển thị số tiền hóa đơn chưa thanh toán và số hóa đơn chờ.

### 14.4. Đơn giá chiết khấu hiện tại

| Loại mã | Giá |
|---------|-----|
| **Mã lô (BATCH)** | 10 VND / mã |
| **Mã thùng (BOX)** | 20 VND / mã |
| **Sản phẩm (PRODUCT)** | 30 VND / mã |
| **Đơn lẻ (STANDALONE)** | 40 VND / mã |

### 14.5. Phân tích biến động tài chính

- **Biểu đồ tròn:** Thể hiện cơ cấu biến động ví (Nạp ví, Phí tạo QR, Hoàn tiền, Khác)
- **Biểu đồ cột:** Lịch sử phát sinh cước hóa đơn theo tháng

### 14.6. Lịch sử hóa đơn định kỳ

Bảng hiển thị các hóa đơn đã phát hành:

| Cột | Ý nghĩa |
|-----|---------|
| **Kỳ hạn** | Chu kỳ thanh toán (ví dụ: 3/7/2026 – 4/7/2026) |
| **Số tiền** | Tổng tiền hóa đơn (ví dụ: 75.703.460đ) |
| **Trạng thái** | `Đã trả` (xanh lá) hoặc `Chưa trả` (đỏ) |
| **Thao tác** | ✅ Xong, 🖨️ In |

### 14.7. Lịch sử đợt tạo mã QR

Bảng chi tiết từng lần tạo mã QR:

| Cột | Ý nghĩa |
|-----|---------|
| **STT** | Số thứ tự |
| **Thời gian** | Ngày giờ tạo |
| **Loại mã** | `Đơn lẻ` (cam) hoặc `Sản phẩm` (xanh) |
| **Số lượng** | Số mã QR tạo |
| **Chi phí** | Chi phí phát sinh |
| **Lô / Sản phẩm** | Lô hàng liên kết |
| **Chi tiết** | Mô tả yêu cầu |

---

## 15. Hồ sơ công ty

> **Đường dẫn menu:** HỆ THỐNG → **Hồ sơ công ty**

Trang này cho phép bạn cập nhật thông tin cơ bản của công ty.

![Hồ sơ công ty](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/12_company_profile.png)

### 15.1. Các trường thông tin

| Trường | Mô tả | Ví dụ |
|--------|-------|-------|
| **Tên công ty** *(bắt buộc)* | Tên đầy đủ của công ty | System Default |
| **Mã công ty** | Mã viết tắt | SYS |
| **Email liên hệ** | Email chính thức | (trống) |
| **Số điện thoại** | Hotline | (trống) |
| **Địa chỉ** | Địa chỉ trụ sở chính | (trống) |
| **Logo công ty (URL)** | Đường dẫn logo | https://... |

### 15.2. Thông tin hệ thống (bên phải)

| Thông tin | Ý nghĩa |
|-----------|---------|
| **Tenant ID** | Mã định danh công ty trong hệ thống |
| **Ngày tham gia** | Ngày đăng ký (ví dụ: 22/6/2026) |
| **Trạng thái tài khoản** | `Đang hoạt động` (xanh lá) |

### 15.3. Cập nhật thông tin

1. Điền thông tin vào các trường tương ứng
2. Nhấn **"Lưu"** để cập nhật
3. Hoặc nhấn **"Hủy"** để bỏ thay đổi

---

## 16. Thông báo

> **Đường dẫn menu:** HỆ THỐNG → **Thông báo**

Trung tâm thông báo giúp bạn theo dõi tất cả cảnh báo và sự kiện quan trọng của hệ thống.

![Thông báo](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/13_notifications.png)

### 16.1. Thẻ thống kê

| Thẻ | Ý nghĩa |
|-----|---------|
| 🔔 **Tổng thông báo** | Tổng số thông báo nhận được (ví dụ: 8) |
| 💬 **Chưa đọc** | Số thông báo chưa đọc (ví dụ: 5) |
| ⚠️ **Cảnh báo hàng giả** | Số thông báo liên quan hàng giả |
| 🔒 **Bảo mật** | Số thông báo liên quan bảo mật |

### 16.2. Bộ lọc

- **Tìm kiếm:** Gõ từ khóa trong ô tìm kiếm
- **Lọc theo loại:** Chọn từ dropdown "Tất cả loại"
- **Lọc theo trạng thái:** Chọn "Tất cả" hoặc chỉ xem chưa đọc/đã đọc

### 16.3. Danh sách thông báo

Mỗi thông báo hiển thị:
- **Biểu tượng** 🔔 và nhãn loại (ví dụ: `THANH TOÁN`)
- **Nội dung** chi tiết
- **Thời gian** (ví dụ: "36 phút trước")
- **Chấm xanh** ● bên phải = chưa đọc

### 16.4. Các nút hành động

| Nút | Chức năng |
|-----|-----------|
| **"Đánh dấu tất cả đã đọc"** | Đánh dấu tất cả thông báo là đã đọc |
| **"Xóa đã đọc"** | Xóa các thông báo đã đọc |

---

## 17. Cài đặt hệ thống

> **Đường dẫn menu:** HỆ THỐNG → **Cài đặt hệ thống**

Đây là trang cài đặt quan trọng nhất, có **6 tab** cấu hình khác nhau.

### 17.1. Tab "Thông tin công ty" 🏢

![Thông tin công ty](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/14_settings_company.png)

Cho phép cập nhật thông tin chi tiết của công ty:

| Trường | Mô tả |
|--------|-------|
| **Tên công ty** *(bắt buộc)* | Tên đầy đủ |
| **Mã số thuế** | Mã số thuế doanh nghiệp |
| **Ngành nghề** | Lĩnh vực kinh doanh (dropdown) |
| **Địa chỉ trụ sở** | Địa chỉ chính |
| **Số điện thoại** | Hotline |
| **Website** | Trang web công ty |
| **Email liên hệ** | Email liên lạc |
| **Mô tả công ty** | Giới thiệu ngắn |

**Logo công ty** (bên phải):
- Nhấn **"Nhấn để thay đổi logo"**
- Tải lên file PNG hoặc SVG (tối đa 2MB)
- Kích thước tối ưu: 200×200px, nền trong suốt

### 17.2. Tab "Branding" 🎨 — Tùy chỉnh giao diện

![Branding](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/15_settings_branding.png)

Tùy chỉnh giao diện trang **xác thực sản phẩm** mà khách hàng nhìn thấy khi quét mã QR:

| Trường | Mô tả | Ví dụ |
|--------|-------|-------|
| **Màu chủ đạo (Primary)** | Màu chính của trang | #002a58 (xanh đậm) |
| **Màu phụ (Secondary)** | Màu phụ | #00677d (xanh lá đậm) |
| **Tiêu đề trang xác thực** | Tiêu đề trang hiển thị cho khách | "Xác Thực Sản Phẩm Chính Hãng" |
| **Thông điệp xác thực thành công** | Nội dung khi xác thực OK | "Sản phẩm này đã được xác thực..." |
| **Hotline hỗ trợ** | Số hotline hỗ trợ khách | 1800 1234 |

**Xem trước trang Consumer** (bên phải):
- Hiển thị bản xem trước giao diện theo cài đặt hiện tại
- Giúp bạn biết khách hàng sẽ thấy gì

### 17.3. Tab "Thông báo" 🔔

Bật/tắt các loại thông báo hệ thống:

| Nhóm | Mô tả |
|------|-------|
| **An ninh & Hàng giả** | Thông báo khi phát hiện hàng giả |
| **Chuỗi cung ứng** | Thông báo khi có hoạt động cung ứng |
| **Hệ thống & Dữ liệu** | Thông báo về hệ thống (lỗi, cập nhật) |
| **Quét của khách hàng** | Thông báo khi khách hàng quét mã |

### 17.4. Tab "Webhooks" 🔗

![Webhooks](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/16_settings_webhooks.png)

> [!NOTE]
> **Webhook** là gì? Đơn giản, webhook là cách để AuthentiQR tự động gửi thông báo đến hệ thống khác (ví dụ: phần mềm ERP, CRM) khi có sự kiện xảy ra.

**Quản lý Webhook Endpoints:**
- Thêm URL webhook bằng nút **"+ Thêm webhook"**
- Mỗi webhook hiển thị: URL, sự kiện đăng ký, trạng thái (HOẠT ĐỘNG/TẮT)
- Nút ▶️ để test gửi thử
- Nút 🗑️ để xóa

**Sự kiện có thể đăng ký:**

| Sự kiện | Ý nghĩa |
|---------|---------|
| `QR_CREATED` | Khi tạo mã QR mới |
| `BATCH_EXPORTED` | Khi xuất lô hàng |
| `DIST_RECEIVED` | Khi đại lý nhận hàng |
| `RETAIL_RECEIVED` | Khi nhà phân phối nhận hàng |
| `CONSUMER_VERIFIED` | Khi khách hàng quét mã |
| `COUNTERFEIT_DETECTED` | Khi phát hiện hàng giả |

### 17.5. Tab "API Keys" 🔑

![API Keys](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/17_settings_api_keys.png)

> [!NOTE]
> **API Key** là mã bảo mật cho phép phần mềm bên ngoài truy cập dữ liệu AuthentiQR. Nếu công ty bạn không dùng phần mềm tích hợp, bạn không cần quan tâm tab này.

**Quản lý API Keys:**
- Nhấn **"+ Tạo API Key mới"** để tạo khóa mới
- Mỗi key hiển thị: Tên, ngày tạo, lần dùng cuối, trạng thái
- Phạm vi quyền: `qr:read`, `scan:write`, `scan:read`, v.v.
- Nút 📋 để sao chép key
- Nút 🚫 để khóa key

**Tài liệu API:** Xem chi tiết tại `docs.authentiqr.vn/api`

### 17.6. Tab "Admin Scan" ⚙️

Cấu hình các khối dữ liệu hiển thị trên trang Admin Scan:

| Khối dữ liệu | Mô tả |
|---------------|-------|
| **Raw Data** | Dữ liệu thô của mã QR |
| **Scan History** | Lịch sử quét của mã QR |
| **Supply Chain** | Thông tin chuỗi cung ứng |
| **Security Alerts** | Cảnh báo bảo mật |

Bật/tắt từng khối bằng công tắc (toggle switch).

---

## 18. Hồ sơ cá nhân

> **Đường dẫn menu:** HỆ THỐNG → **Hồ sơ cá nhân**

Quản lý thông tin cá nhân và bảo mật tài khoản của bạn.

![Hồ sơ cá nhân](C:/Users/Ryan/.gemini/antigravity-ide/brain/6bdc8ed5-5829-4a19-a814-ea0fd4280ca1/screenshots/18_personal_profile.png)

### 18.1. Thông tin chung (bên trái)

| Trường | Mô tả | Chỉnh sửa được? |
|--------|-------|-----------------|
| **Họ và tên** | Tên hiển thị của bạn | ✅ Có |
| **Email** | Email đăng nhập | ❌ Không (khóa) |
| **Số điện thoại** | Số liên lạc cá nhân | ✅ Có |
| **Vai trò** | Quyền hạn trong hệ thống | ❌ Không (khóa) |

Nhấn **"Lưu thay đổi"** sau khi cập nhật thông tin.

### 18.2. Đổi mật khẩu (bên phải)

1. Nhập **Mật khẩu hiện tại** để xác minh
2. Nhập **Mật khẩu mới** (tối thiểu 8 ký tự)
3. Nhập **Xác nhận mật khẩu mới** (gõ lại mật khẩu mới)
4. Nhấn **"Cập nhật mật khẩu"**

> [!CAUTION]
> Sau khi đổi mật khẩu, bạn sẽ cần sử dụng mật khẩu mới cho lần đăng nhập tiếp theo. Hãy ghi nhớ hoặc lưu mật khẩu ở nơi an toàn.

---

## 19. Câu hỏi thường gặp (FAQ)

### ❓ Tôi quên mật khẩu, phải làm sao?
Liên hệ bộ phận hỗ trợ kỹ thuật hoặc quản trị viên hệ thống để được đặt lại mật khẩu.

### ❓ Làm sao biết sản phẩm đang bị làm giả?
Kiểm tra trang **"Cảnh báo hàng giả"** thường xuyên. Hệ thống sẽ tự động phát hiện và cảnh báo khi có dấu hiệu bất thường.

### ❓ Chi phí sử dụng tính như thế nào?
Chi phí dựa trên số lượng mã QR tạo ra. Xem bảng giá tại trang **"Thanh toán & Cước phí"**.

### ❓ Tôi có thể xuất dữ liệu ra file không?
Có! Hầu hết các trang đều có nút **"Xuất Excel"** hoặc **"Xuất CSV"** để tải dữ liệu.

### ❓ Webhook và API Key dùng để làm gì?
Đây là các tính năng **dành cho kỹ thuật viên**. Nếu công ty bạn muốn tích hợp AuthentiQR với phần mềm khác (ERP, CRM...), hãy liên hệ đội ngũ IT.

### ❓ Làm sao thay đổi giao diện trang xác thực sản phẩm?
Vào **Cài đặt hệ thống → Tab Branding** để thay đổi màu sắc, tiêu đề, và thông điệp.

### ❓ Tại sao số dư ví hiển thị khác với thực tế?
Kiểm tra trang **"Thông báo"** — hệ thống sẽ cảnh báo nếu có chênh lệch số dư.

### ❓ Tôi muốn thêm nhân viên vào hệ thống?
Liên hệ quản trị viên cấp cao hoặc bộ phận hỗ trợ để tạo tài khoản mới.

---

> [!TIP]
> **Mẹo sử dụng hiệu quả:**
> - 📌 Kiểm tra **Dashboard** mỗi ngày để nắm tình hình
> - 🔔 Bật thông báo để nhận cảnh báo kịp thời
> - 📊 Xem **Báo cáo & Thống kê** hàng tuần
> - ⚠️ Xử lý ngay các **Cảnh báo hàng giả** mức nghiêm trọng

---

*📞 Liên hệ hỗ trợ: Nếu cần trợ giúp, vui lòng liên hệ đội ngũ hỗ trợ AuthentiQR.*

*Tài liệu này được cập nhật lần cuối: 18/07/2026*
