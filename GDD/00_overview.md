# Game Overview

## Core Loop

```
Chọn thế lực (quiz 8 câu)
        ↓
Xây dựng căn cứ → Khai thác tài nguyên → Chiêu mộ nhân vật
        ↓
Gacha → Thu thập môn đồ / tướng / tu sĩ
        ↓
Xuất chinh → Chiếm lãnh thổ → Mở rộng tiểu đại lục
        ↓
PvP / Liên minh → Tranh bá thiên hạ
```

## AFK Core — Gia Chủ Simulator

Người chơi = bộ não, không phải cái máy click.

- **Ra quyết định chiến lược** → NPC thuộc hạ tự thực thi
- **Offline** → thế lực vẫn hoạt động
- **Online** → điều chỉnh, quyết định lớn, xử lý sự kiện

### Vòng Lặp Hàng Ngày

| Thời Điểm | Hành Động | Thời Gian |
|---|---|---|
| Sáng | Đọc Báo Cáo Đêm, ra lệnh ngày mới | 5 phút |
| Chiều | Xử lý sự kiện phát sinh, giao thương | Tùy |
| Tối | Sự kiện server, trận lớn (báo trước 4-6h) | Nếu muốn |

### Lệnh Điều Kiện (If-Then)

Người chơi đặt lệnh trước, thuộc hạ tự xử lý:

```
IF lương thực < 200 → Thương Quan mua lương từ Thổ server
IF có thế lực lạ vào vùng đệm → Trinh Sát báo cáo + rút quân
IF Đan Môn hàng xóm giảm giá → Thương Quan mua 50 Hồi Nguyên Đan
```

Số lệnh tối đa tăng theo cấp Quản Gia: 3 → 8 → 15.

---

## Hệ Thống Thời Gian

**1 ngày thực = 10 năm game**

| Giai Đoạn | Ngày Thực | Năm Game | Nội Dung |
|---|---|---|---|
| Early Game | 1-14 | 0-140 | Nội bộ server, xây dựng |
| Season War | 15-30 | 140-300 | Chiến trường cụm SV |
| Gộp Cụm | 31-45 | 300-450 | Multi-cụm hợp nhất |
| Endgame | 46-60 | 450-600 | Quyết chiến, xếp hạng |

**1 Season = 60 ngày thực = 600 năm lịch sử game**

### Vòng Lặp Drama Leo Thang

```
LAYER 1 — Nội Bộ Server (Ngày 1-14)
"Đánh nhau trong nhà"
        ↓ Ngày 14: Cụm SV ập đến
LAYER 2 — Season War Cụm (Ngày 15-30)
"Vừa xong nội chiến → cụm SV mới xuất hiện"
        ↓ Ngày 30: Cụm mới ập đến
LAYER 3 — Gộp Cụm (Ngày 31+)
"Kẻ thù cũ → có thể thành đồng minh chống kẻ thù mới"
```

---

## Cơ Chế Cơ Duyên

Lý do muốn online — không phải farming bắt buộc.

| Loại | Mô Tả | Thời Hạn |
|---|---|---|
| **Cá Nhân** | Đệ tử phát hiện động phủ ẩn, bí kíp cổ | 12h quyết định |
| **Thế Lực** | Xây đủ tier 3 → unlock nhánh talent ẩn | Vĩnh viễn nếu bỏ qua |
| **Server** | Phế tích cổ đại xuất hiện 48h | 48h |
| **Nhân Vật Ẩn** | Điều kiện phức hợp → Ẩn Thế Cao Nhân | Random |

---

## Không Có

- ❌ Energy/Stamina system cưỡng bức
- ❌ VIP 2, VIP 3, whale trap
- ❌ Bán stat, bán unit exclusive
- ❌ Thông báo "Năng lượng đầy rồi vào nhận đi"
