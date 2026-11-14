# 🤖 Danh sách các loại Minion

`TN-Minion-GR` cung cấp **8 loại Minion** với chức năng riêng biệt, hỗ trợ nâng cấp từ **Cấp 1** đến **Cấp 4**.

| Minion | Mã (`MinionType`) | Tốc độ mặc định | Công dụng chính |
| :--- | :--- | :--- | :--- |
| **Thợ Mỏ** | `MINER` | `5 giây / lần` | Đào các khối quặng/đá phía trước mặt theo hướng nhìn. |
| **Nông Dân** | `FARMER` | `6 giây / lần` | Tự tạo khu đất trồng, kích thích cây lớn nhanh, thu hoạch & gieo lại hạt. |
| **Thợ Săn** | `SLAYER` | `4 giây / lần` | Tấn công quái vật xung quanh và thu chiến lợi phẩm. |
| **Tiều Phu** | `LUMBERJACK` | `6 giây / lần` | Chặt cây gỗ trong khu vực và tự trồng lại mầm cây. |
| **Thu Gom** | `COLLECTOR` | `2 giây / lần` | Tự động hút các vật phẩm rơi trên mặt đất xung quanh. |
| **Thương Nhân** | `SELLER` | `5 giây / lần` | Bán vật phẩm từ rương liên kết ra tiền (`$`) cộng thẳng vào tài khoản chủ nhân. |
| **Bảo Mẫu** | `FEEDER` | `8 giây / lần` | Hồi máu và thanh thức ăn cho người chơi đứng gần. |
| **Ngư Dân** | `FISHER` | `7 giây / lần` | Tự động câu cá ở nguồn nước gần đó và thu chiến lợi phẩm. |

---

## 🌾 Chi tiết Minion Nông Dân (`FARMER`)

- **Tự động tạo khu đất**: Khi đặt xuống hoặc nâng cấp, Minion tự đặt 1 khối `OAK_STAIRS` ngập nước dưới chân và cày sẵn đất `FARMLAND` xung quanh theo bán kính cấp độ (`1x1` đến tối đa `4x4` ở cấp 4).
- **Tăng trưởng nhanh**: Kích thích cây trồng chưa chín phát triển nhanh theo cấp độ Minion.
- **Thu hoạch thông minh**:
  - Cây `Ageable` (Lúa, Cà rốt, Khoai tây, Củ dền...): Thu hoạch khi chín và tự gieo lại hạt ở cấp độ `0`.
  - Cây ra quả (Bí ngô, Dưa hấu): Chỉ thu hoạch phần **quả**, giữ nguyên thân cây và không thu hạt.
- **Lưu trữ**: Tự chuyển vào `KhoLuuTru` (nếu bật) hoặc rương liên kết.

---

## 💰 Chi tiết Minion Thương Nhân (`SELLER`)

- **Liên kết rương đồ cần bán**: Bấm vào nút `LIÊN KẾT RƯƠNG ĐỒ CẦN BÁN` trong GUI rồi chuột phải vào Rương / Rương bẫy / Thùng (`Barrel`) trong bán kính 15 block.
- **Tốc độ xử lý**: Mặc định `5 giây / lần` ở Cấp 1 (tăng tốc dần đến `2 giây / lần` ở Cấp 4).
- **Giao dịch trực tiếp**: Tiền bán được cộng thẳng qua `Vault Economy` cho chủ sở hữu (không sử dụng nút `KhoLuuTru`).
