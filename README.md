<div align="center">

# ⛏️ TN-Minion-GR

### Hệ thống Minion tự động thông minh cho server Skyblock / Survival

*Phát triển bởi **Tài Dev Nguyễn** • **TeamJaoMC Store***

![Version](https://img.shields.io/badge/VERSION-1.0.0-2ea44f?style=for-the-badge)
![Minecraft](https://img.shields.io/badge/MINECRAFT-1.21.1%2B-3fb950?style=for-the-badge)
![Java](https://img.shields.io/badge/JAVA-21%2B-ed8b00?style=for-the-badge&logo=openjdk&logoColor=white)

![Paper](https://img.shields.io/badge/Paper-Supported-007ec6?style=flat-square)
![KhoLuuTru](https://img.shields.io/badge/TN--KhoLuuTru-Integrated-8957e5?style=flat-square)
![Vault](https://img.shields.io/badge/Economy-Vault-d29922?style=flat-square)
![WorldGuard](https://img.shields.io/badge/Protection-WorldGuard%207%2B-0e8a16?style=flat-square)
![License](https://img.shields.io/badge/License-Private-d73a49?style=flat-square)

[📥 Tải xuống](https://github.com/Jaojao00/TN-Minion-GR/releases) • [🌟 Tính năng](#-tính-năng-nổi-bật) • [🤖 Minions](./MINIONS.md) • [⌨️ Lệnh & Quyền](./COMMANDS.md) • [💎 TN-KhoLuuTru](https://github.com/Jaojao00/kholuutru) • [📝 Changelog](./CHANGELOG.md)

</div>

---

## 📖 Giới Thiệu

**TN-Minion-GR** là plugin Minion tự động hóa thế hệ mới dành cho máy chủ Minecraft **Paper / Purpur / Spigot 1.21.1+**. Các Minion sẽ thay bạn đào khoáng sản, trồng & thu hoạch nông sản, chặt gỗ, săn quái, câu cá, gom đồ, hồi phục và tự động bán vật phẩm kiếm tiền (`$`) qua giao diện GUI trực quan.

Plugin được tối ưu hiệu năng cao (chỉ hoạt động khi chunk được nạp, chỉ chạy hoạt ảnh khi có người chơi quan sát) và kết nối trực tiếp với hệ thống **[TN-KhoLuuTru](https://github.com/Jaojao00/kholuutru)** giúp vật phẩm thu được bay thẳng vào `/kho` của người chơi.

---

## 🌟 Tính năng nổi bật

- **8 chức nghiệp Minion chuyên biệt**: Thợ Mỏ (`MINER`), Nông Dân (`FARMER`), Thợ Săn (`SLAYER`), Tiều Phu (`LUMBERJACK`), Thu Gom (`COLLECTOR`), Thương Nhân (`SELLER`), Bảo Mẫu (`FEEDER`), Ngư Dân (`FISHER`).
- **Tích hợp [TN-KhoLuuTru](https://github.com/Jaojao00/kholuutru)**: Tự động chuyển nông sản, khoáng sản, gỗ, cá... thẳng vào kho ảo `/kho` (có nút Bật/Tắt riêng cho từng Minion trong GUI).
- **Nông Dân thông minh**: Tự tạo khu đất `FARMLAND` + `OAK_STAIRS` ngập nước dưới chân (`1x1` đến `4x4`), kích thích cây lớn nhanh, thu hoạch riêng quả Bí ngô / Dưa hấu mà không phá thân hay thu hạt.
- **Thương Nhân tiện lợi**: Liên kết trực tiếp với Rương / Rương bẫy / Thùng (`Barrel`) chứa đồ cần bán và cộng tiền thẳng qua `Vault`.
- **An toàn & Tối ưu**: Tương thích **WorldGuard 7+**, **GriefPrevention**, **Lands**, kiểm tra an toàn chunk lân cận để tránh lag server.
- **Tùy biến linh hoạt**: Cửa hàng GUI, xoay 4 hướng, đổi tên, hồi máu, nâng cấp **Cấp 1 → Cấp 4** và hỗ trợ đa ngôn ngữ (`languages/vi.yml`).

---

## 📋 Yêu cầu hệ thống

| Thành phần | Yêu cầu |
| :--- | :--- |
| **Phiên bản Minecraft** | `1.21.1+` (Paper / Purpur / Spigot) |
| **Java** | `Java 21` trở lên |
| **Kinh tế (Khuyên dùng)** | `Vault` + plugin Economy (EssentialsX, CMI...) |
| **Kho ảo (Tuỳ chọn)** | [TN-KhoLuuTru](https://github.com/Jaojao00/kholuutru) |
| **Bảo vệ vùng đất (Tuỳ chọn)** | `WorldGuard 7+`, `GriefPrevention`, `Lands` |

---

## 🚀 Cài đặt nhanh

1. Tải file `TN-Minion-GR-x.x.x.jar` mới nhất tại mục **[Releases](https://github.com/Jaojao00/TN-Minion-GR/releases)**.
2. Bỏ file `.jar` vào thư mục `plugins/` của server (cài thêm **[TN-KhoLuuTru](https://github.com/Jaojao00/kholuutru)** nếu muốn dùng tính năng gửi thẳng vào `/kho`).
3. Khởi động lại server để plugin tự tạo các file cấu hình.
4. Vào game và gõ `/minion store` để mở cửa hàng Minion.

---

## 📚 Tài liệu chi tiết

- 🤖 [Danh sách & Chi tiết các loại Minion](./MINIONS.md)
- ⌨️ [Lệnh & Phân quyền](./COMMANDS.md)
- 📝 [Nhật ký cập nhật (Changelog)](./CHANGELOG.md)
- 💎 [Plugin kết nối: TN-KhoLuuTru](https://github.com/Jaojao00/kholuutru)
