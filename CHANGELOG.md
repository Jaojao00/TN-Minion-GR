# 📝 Nhật ký cập nhật (Changelog)

## v1.0.0

### ✨ Tính năng mới & Cải tiến
- **Minion Nông Dân (`FARMER`)**:
  - Tự động tạo khu đất trồng khi đặt/nâng cấp (`OAK_STAIRS` ngập nước dưới chân + vùng `FARMLAND` từ cấp 1 đến tối đa 4x4 ở cấp 4).
  - Bổ sung cơ chế kích thích tăng trưởng nhanh cho cây trồng chưa chín.
  - Hỗ trợ thu hoạch riêng phần quả đối với Bí ngô (`PUMPKIN`) & Dưa hấu (`MELON`), giữ nguyên thân cây và không thu hạt.
- **Minion Thương Nhân (`SELLER`)**:
  - Cập nhật giao diện & hướng dẫn **Liên kết rương đồ cần bán** (hỗ trợ cả `Chest`, `Trapped Chest` và `Barrel`).
  - Loại bỏ nút `KhoLuuTru` khỏi bảng điều khiển của Seller cho gọn và đúng chức năng.
  - Tăng tốc độ hoạt động mặc định từ `10s` lên **`5s / lần`** (giảm dần tới `2s / lần` ở cấp 4).

### 🛠️ Sửa lỗi & Tối ưu
- Gỡ bỏ cơ chế ép nạp chunk offline để tránh lỗi `Trying to schedule tick in not loaded position` và giảm tải cho server Paper 1.21.1+.
- Kiểm tra an toàn chunk hiện tại và 4 chunk lân cận trước khi thao tác block (`isBlockAndNeighborsLoaded`).
- Cập nhật lại mô tả (lore) trong Cửa hàng và vật phẩm Minion: hoạt động khi chunk được nạp (có người chơi ở gần).
