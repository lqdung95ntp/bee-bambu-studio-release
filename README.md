# BeE Bambu Studio Release

Kho lưu trữ và phát hành các bản build của **Bee Bambu Studio** dành cho **macOS** và **Windows**.

## 🚀 Tải về phiên bản mới nhất (v02.09.01.72)

Truy cập trang [Releases v02.09.01.72](https://github.com/lqdung95ntp/bee-bambu-studio-release/releases/tag/v02.09.01.72) hoặc tải trực tiếp:

| Hệ điều hành | Tệp tải về (Assets) | Dung lượng | Mô tả |
| :--- | :--- | :--- | :--- |
| **Windows** | [📥 BambuStudio_Windows_x64_Portable_2.9.1.72.zip](https://github.com/lqdung95ntp/bee-bambu-studio-release/releases/download/v02.09.01.72/BambuStudio_Windows_x64_Portable_2.9.1.72.zip) | ~351 MB | Bản Portable cho Windows x64 (giải nén chạy ngay) |
| **macOS** | [📥 BambuStudio_MacOS_Universal_2.9.1.72.dmg](https://github.com/lqdung95ntp/bee-bambu-studio-release/releases/download/v02.09.01.72/BambuStudio_MacOS_Universal_2.9.1.72.dmg) | ~350 MB | Bản Universal hỗ trợ Apple Silicon (M1/M2/M3/M4) & Intel |

---

## 📋 Có gì mới trong bản v02.09.01.72

### 🚀 Tính năng mới (Features)
- **Tích hợp BeE Printer Farm tab (BeeFarmPanel):**
  - Hỗ trợ kết nối máy chủ Farm trực tiếp (Server URL & API Token).
  - Giao diện nhúng trạng thái định danh tài khoản, hướng dẫn kết nối và mở nhanh trên trình duyệt.
- **Hàng đợi in (Print Queue):**
  - Bổ sung nút **Send to Queue** trong hộp thoại chọn máy in (`SelectMachineDialog`).
  - Tự động giải nén và phân tích G-code metadata từ file 3MF để đẩy file in chuẩn xác vào server queue.

### 🛠 Sửa lỗi & Tối ưu (Bug Fixes & Improvements)
- **Khắc phục lỗi treo/đơ giao diện 3D trên macOS:**
  - Bổ sung cơ chế `suspend()` / `resume()` cho WebView của Farm khi chuyển tab, tránh làm nghẽn `wxEVT_IDLE` của hệ thống.
  - Tối ưu phản hồi con lăn chuột (`on_mouse_wheel`) trong `GLCanvas3D.cpp` giúp zoom mượt mà tức thì.
- **Bỏ qua cảnh báo Unsigned Studio:**
  - Tắt pop-up cảnh báo phiên bản không ký chính thức để tránh ngắt quãng thao tác in.
- **Mạng & Chuyển hướng:**
  - Hỗ trợ `CURLOPT_UNRESTRICTED_AUTH` trong tiện ích Http.

---

## 📌 Hướng dẫn sử dụng

### 1. Windows
1. Tải về file `BambuStudio_Windows_x64_Portable_2.9.1.72.zip`.
2. Giải nén file `.zip` vào thư mục mong muốn.
3. Chạy file `bambu-studio.exe` để bắt đầu sử dụng.

### 2. macOS
1. Tải về file `BambuStudio_MacOS_Universal_2.9.1.72.dmg`.
2. Mở file `.dmg` và kéo ứng dụng vào thư mục `Applications`.
3. Nếu gặp thông báo bảo mật của macOS (*"unidentified developer"*):
   - Mở **System Settings** > **Privacy & Security**.
   - Cuộn xuống phần Security và nhấn **Open Anyway**.

---
*Dựa trên bản phát hành BambuStudio v02.09.01.72 mã nguồn mở.*
