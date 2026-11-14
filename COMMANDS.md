# ⌨️ Lệnh & Phân quyền

Lệnh chính: `/minion` (tên gọi khác: `/minions`, `/tnminion`, `/robot`)

---

## 👤 Lệnh người chơi (`tnminion.use`)

| Lệnh | Mô tả |
| :--- | :--- |
| `/minion help` | Xem danh sách hướng dẫn lệnh |
| `/minion about` | Xem thông tin phiên bản plugin & số Minion đang hoạt động |
| `/minion store` | Mở cửa hàng mua Minion |

---

## 🛡️ Lệnh quản trị viên (`tnminion.admin`)

| Lệnh | Mô tả |
| :--- | :--- |
| `/minion give <người_chơi> <loại> [cấp_độ]` | Trao Minion cho người chơi với loại và cấp độ chỉ định |
| `/minion list` | Xem danh sách toàn bộ Minion đang hoạt động kèm tọa độ |
| `/minion remove [x] [y] [z]` | Xóa Minion tại vị trí đang đứng hoặc tọa độ chỉ định |
| `/minion cleanup` | Dọn dẹp các Minion lỗi khỏi hệ thống |
| `/minion reload` | Tải lại cấu hình, ngôn ngữ và bảng nâng cấp của plugin |

---

## 🔑 Phân quyền (Permissions)

| Permission | Mặc định | Mô tả |
| :--- | :--- | :--- |
| `tnminion.use` | `true` (Tất cả người chơi) | Cho phép sử dụng lệnh cơ bản và tương tác Minion |
| `tnminion.admin` | `op` | Toàn quyền quản trị Minion |
