# BeE Bambu Studio Release

Kho lưu trữ và phát hành các bản build của **Bee Bambu Studio** dành cho **macOS** và **Windows**.

## 🚀 Tải về phiên bản mới nhất (v02.09.02.62)

Truy cập trang [Releases v02.09.02.62](https://github.com/lqdung95ntp/bee-bambu-studio-release/releases/tag/v02.09.02.62) hoặc tải trực tiếp:

| Hệ điều hành | Tệp tải về (Assets) | Dung lượng | Mô tả |
| :--- | :--- | :--- | :--- |
| **macOS** | [📥 BambuStudio_MacOS_Universal_2.9.2.62.dmg](https://github.com/lqdung95ntp/bee-bambu-studio-release/releases/download/v02.09.02.62/BambuStudio_MacOS_Universal_2.9.2.62.dmg) | ~304 MB | Bản Universal hỗ trợ chip Apple Silicon (M1/M2/M3/M4) & Intel x86_64 |

---

## 📋 Có gì mới trong bản v02.09.02.62

### 🚀 Tính năng mới (Features)
- **Tích hợp máy in Snapmaker U1:**
  - Hỗ trợ kết nối và điều khiển Snapmaker U1 qua mạng LAN.
  - Giao diện điều khiển Flutter / Webview nhúng trực tiếp trong tab Device.
  - Tùy biến hộp thoại in ấn và chuẩn hóa các macro G-code khởi động / kết thúc.
  - Hỗ trợ đổi nhiệt độ đầu đùn khuyến nghị cho filament Snapmaker.
- **Xác thực bản quyền Email (BeE STEM Solutions):**
  - Tự động kiểm tra bản quyền email tài khoản khi mở ứng dụng và sau khi đăng nhập.
  - Bảo vệ và cấp phép các tính năng nâng cao: Đổi tên máy in Bambu, Tự động bỏ qua lỗi HMS khi in (auto-retry BMCU), Gửi lệnh & in ấn Snapmaker U1.

### 🛠 Sửa lỗi & Tối ưu (Bug Fixes & Improvements)
- **Tương thích hoàn toàn macOS Intel (x86_64):**
  - Khắc phục lỗi tab Device hiển thị giao diện Fluidd trên máy Mac Intel do thiếu binary `snapmaker_control_macos_x64`.
  - Tự động nhận diện kiến trúc CPU để kích hoạt đúng dịch vụ điều khiển cục bộ.
- **Đóng gói Universal macOS:**
  - File cài đặt `.dmg` chuẩn Universal chứa đầy đủ binary thực thi cho cả Apple Silicon và Intel 64-bit.

---

## 📌 Hướng dẫn sử dụng

### macOS
1. Tải về file `BambuStudio_MacOS_Universal_2.9.2.62.dmg`.
2. Mở file `.dmg` và kéo ứng dụng vào thư mục `Applications`.
3. Nếu gặp thông báo bảo mật của macOS (*"unidentified developer"*):
   - Mở **System Settings** > **Privacy & Security**.
   - Cuộn xuống phần Security và nhấn **Open Anyway**.

---
*Dựa trên bản phát hành BambuStudio v02.09.02.62 mã nguồn mở.*
