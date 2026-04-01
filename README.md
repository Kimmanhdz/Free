# 🌟 Super Self Bot - Tuan Haii 🌟

**Super Self Bot** là một công cụ mạnh mẽ được thiết kế để tối ưu hóa trải nghiệm cá nhân trên Discord. Với giao diện hiện đại và các tính năng tự động hóa thông minh, giúp bạn quản lý profile, cày cuốc các bot giải trí và quản trị server một cách hiệu quả nhất.

---

## 🚀 Tính năng nổi bật

### 🎭 Custom Profile Modern
Thay đổi diện mạo tài khoản của bạn với hệ thống tùy chỉnh chuyên sâu:
* **Auto Change Custom Status:** Tự động xoay vòng trạng thái văn bản theo danh sách từ `customstatus.txt`.
* **Custom Stream Box:** Hiển thị trạng thái "Streaming" chuyên nghiệp với tiêu đề, mô tả và hình ảnh tùy chỉnh từ `stream.txt`.
* **Rich Presence:** Tích hợp hiển thị thông tin chi tiết qua Application ID để làm nổi bật Profile cá nhân.

### 🎮 Automation & Farming
Hỗ trợ treo máy (AFK) thông minh để tối ưu hóa tài nguyên:
* **Auto Farm Exp ($farm):** Tự động gửi tin nhắn kèm emoji ngẫu nhiên để cày Level/Exp cho các bot như **OwO**, Dank Memer mà không bị hệ thống quét.
* **Voice treo máy ($voice):** Tự động tham gia và duy trì hiện diện trong phòng voice 24/7, hỗ trợ giả lập trạng thái Live/Camera để cày giờ hoặc level voice.

### 💣 Server Management (Nuke Mode)
* **$nuke:** Tính năng dọn dẹp và tái cấu trúc nhanh chóng dành cho quản trị viên. Tự động xóa kênh cũ, tạo kênh mới hàng loạt và gửi thông báo qua Webhook với tốc độ cực cao.

---

## 🛠 Danh sách lệnh (Commands)

| Lệnh | Mô tả |
| :--- | :--- |
| `$menu` | **Mở bảng điều khiển.** Hiển thị toàn bộ menu hướng dẫn và danh sách tính năng. |
| `$farm` | **Bật/Tắt cày Exp.** Tự động spam tin nhắn thông minh để treo chat kiếm exp. |
| `$voice [ID]` | **Treo Voice.** Tham gia vào kênh Voice chỉ định và giữ trạng thái online 24/7. |
| `$nuke [Link]` | **Nuke Server.** Xóa sạch các kênh hiện tại và tạo hàng loạt kênh mới kèm Webhook spam. |

---

## 📋 Hướng dẫn cài đặt & Cấu hình

1.  **Cài đặt thư viện hỗ trợ:**
    ```bash
    pip install requests websocket-client
    ```
2.  **Cấu hình các file dữ liệu:**
    * `config.txt`: Điền `token`, `application_id`, và bật/tắt các chế độ `stream`, `autochangecustomstatus`.
    * `customstatus.txt`: Mỗi dòng là một trạng thái bạn muốn bot tự động đổi.
    * `stream.txt`: Cấu hình các dòng chữ (line1, line2, line3) và link ảnh cho Stream Box.
3.  **Khởi động:**
    ```bash
    python main.py
    ```

---


## 👨‍💻 Thông tin tác giả
* **Developer:** Tuan Haii
* **Project:** Super Self Bot - Ultimate Discord Tool

> [!IMPORTANT]
> **Bảo mật:** Tuyệt đối không chia sẻ mã **Token** của bạn cho bất kỳ ai. Token là chìa khóa toàn quyền truy cập vào tài khoản của bạn!

---