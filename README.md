# ⛏️ TN-Minion-GR

**TN-Minion-GR** là plugin Minion tự động hóa thế hệ mới dành cho máy chủ Minecraft **Skyblock / Survival** trên nền tảng **Paper 1.21.1+ (Java 21)**, được phát triển bởi **Tài Nguyễn**.

---

## ✨ Tính năng nổi bật

- **8 chức nghiệp Minion chuyên biệt**: Thợ Mỏ, Nông Dân, Thợ Săn, Tiều Phu, Thu Gom, Thương Nhân, Bảo Mẫu, Ngư Dân.
- **Tối ưu hiệu năng server**: Chỉ hoạt động khi chunk được nạp (có người chơi ở gần) và chỉ chạy hoạt ảnh khi có người chơi quan sát, hạn chế tối đa lag server.
- **Tích hợp `KhoLuuTru` (KhoLuuTruAPI)**: Tự động chuyển vật phẩm thu hoạch/đào được thẳng vào `/kho` của chủ sở hữu (có thể bật/tắt riêng cho từng Minion trong GUI).
- **Liên kết rương chứa thông minh**: Hỗ trợ liên kết Rương (`Chest`), Rương bẫy (`Trapped Chest`) và Thùng (`Barrel`) trong bán kính 15 block.
- **Hỗ trợ kinh tế & bảo vệ vùng đất**: Tương thích **Vault**, **WorldGuard 7+**, **GriefPrevention**, **Lands**.
- **Giao diện GUI trực quan**: Cửa hàng mua Minion, bảng điều khiển xoay 4 hướng, đổi tên, hồi máu, nâng cấp cấp độ (Cấp 1 → Cấp 4).

---

## 📋 Yêu cầu hệ thống

| Thành phần | Yêu cầu |
| :--- | :--- |
| **Phiên bản Minecraft** | `1.21.1+` (Paper / Purpur / Spigot) |
| **Java** | `Java 21` trở lên |
| **Plugin hỗ trợ (Tuỳ chọn)** | `Vault`, `KhoLuuTru`, `WorldGuard`, `GriefPrevention`, `Lands` |

---

## 🚀 Cài đặt nhanh

1. Tải file `TN-Minion-GR-x.x.x.jar` mới nhất từ mục **Releases**.
2. Bỏ file `.jar` vào thư mục `plugins/` của server.
3. Khởi động lại server để plugin tự tạo các file cấu hình (`config.yml`, `store.yml`, `hooks.yml`, `minionupgrades/`, `languages/`).
4. Mở cửa hàng trong game bằng lệnh `/minion store`.

---

## 📚 Tài liệu chi tiết

- [Danh sách & Chi tiết các loại Minion](./MINIONS.md)
- [Lệnh & Phân quyền](./COMMANDS.md)
- [Nhật ký cập nhật (Changelog)](./CHANGELOG.md)
