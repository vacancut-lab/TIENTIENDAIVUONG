# Hệ Thống Xã Hội & Drama

## Triết Lý

```
Human Drama mới là thứ giữ người chơi lại
Không phải số liệu
        ↓
Mọi hành động để lại dấu vết
Mọi quyết định có hệ quả 3 tầng:
├── Tức thì (ngày đó)
├── Ngắn hạn (3-5 ngày)
└── Dài hạn (cả season)
```

---

## Các Hành Vi Con Người

### Phản Bội
```
Liên minh A + B đang đánh C
B bí mật deal với C
B quay súng bắn A từ phía sau
A sụp đổ, B + C chia tài nguyên
```

**Cơ chế:**
- Kênh ngoại giao bí mật — chat riêng không ai thấy
- Hiệp ước có thời hạn — tự hết hạn, không ràng buộc vĩnh viễn
- Danh tiếng (Reputation) — phản bội nhiều → cả server biết
- Phí phản bội — hủy sớm tốn tài nguyên nhưng vẫn làm được

### Cướp Bóc
```
Thương đội di chuyển trên map = mục tiêu
Phong server phát hiện qua trinh sát
Chặn đường, cướp 40% hàng hóa
```

**Cơ chế:**
- Thương đội chọn tuyến đường — ngắn thì nguy hiểm
- Thuê hộ tống từ thế lực quân sự → chia % lợi nhuận
- Bảo hiểm thương đội — đóng phí, mất hàng được bù một phần

### Nội Gián
```
Thế lực A cài người vào Thế lực B
Nội gián báo cáo: số quân, tài nguyên, kế hoạch tấn công
Hoặc phá hoại: đốt kho lương, mở cổng thành
```

**Cơ chế:**
- Môn đồ bí mật phái sang dưới danh nghĩa "học nghề"
- Thế lực nhận phải điều tra nội bộ để phát hiện
- Bị phát hiện → bắt, tra tấn lấy thông tin, hoặc trao trả

### False Flag / Giả Danh
```
C cướp giả danh B → A trả thù B (oan)
B mất uy tín, mất đồng minh
C thu lợi kép: hàng hóa + gây thù A-B
```

**Điều kiện thực hiện:**
- Trang phục / Phù Hiệu giả của thế lực bị giả danh
- Xóa dấu vết di chuyển (Tình Báo Các tier 3+)
- Phải ở trong địa bàn của thế lực bị giả danh

**Rủi ro nếu bị lộ:**
- Reputation: Ác Danh tăng vọt
- Pháp Gia: Lệnh Truy Nã toàn server
- Thương Hội: Bị cấm giao dịch
- Khó phục hồi trong cùng 1 season

**Điều tra:**
- Thuê Tình Báo Các: tốn tài nguyên + thời gian, kết quả **70% chính xác**
- Nhờ Pháp Gia phán xử: B có thể chứng minh ngoại phạm
- Kệ không điều tra: tiếp tục bị C lợi dụng

### Mua Chuộc & Ám Sát

**Mua chuộc tướng địch:**
- Tướng địch bất mãn → tiếp cận → trả đủ giá → đào tẩu hoặc phản bội
- Tướng trung thành → báo lại chủ → bẫy ngược

**Ám sát:**
- Phái sát thủ đến ám sát NPC tướng lĩnh quan trọng
- Thành công → thế lực địch hỗn loạn 24-48h
- Thất bại → sát thủ bị bắt, danh tính bị lộ
- **Không thể ám sát player trực tiếp** — chỉ NPC tướng lĩnh

### Tin Đồn & Thông Tin Sai
- Thế lực tung tin giả lên bảng thông báo server
- Độ tin cậy theo reputation người tung
- Thế lực chuyên tình báo có thể xác minh thật/giả

---

## Reputation System

| Hành Động | Reputation Thay Đổi |
|---|---|
| Giữ lời hứa | +Tín Nghĩa |
| Phản bội | -Tín Nghĩa, +Khét Tiếng Xảo Quyệt |
| Cướp thương đội | +Hung Danh |
| Bảo vệ thế lực yếu | +Nhân Đức |
| Ám sát bị lộ | +Ác Danh |

### Ảnh Hưởng Thực Tế

| Reputation | Hiệu Ứng |
|---|---|
| Tín Nghĩa cao | Lãi vay thấp hơn, dễ kết minh |
| Hung Danh cao | Thương đội né tuyến đường (lợi hoặc hại) |
| Ác Danh cao | NPC làng dân không hợp tác, khó chiêu mộ nhân tài |
| Nhân Đức cao | Môn đồ trung thành hơn, khó bị mua chuộc |

---

## Chính Trị Nội Bộ Liên Minh

```
Liên minh 5 thế lực
Thế lực mạnh nhất muốn làm Minh Chủ
3 thế lực nhỏ liên kết phủ quyết
Bầu chọn Minh Chủ theo số phiếu
```

**Cơ chế:**
- Liên minh có Hội Đồng — bỏ phiếu quyết định lớn
- Minh Chủ có thể tham ô quỹ chung — để lại dấu vết
- Bỏ phiếu bất tín nhiệm — lật đổ Minh Chủ
- Ly khai được — nhưng mang theo bao nhiêu tài nguyên chung là vấn đề

---

## Cầu Nối Xã Hội — Cho Người Ngại Giao Tiếp

### Tình Báo Các — Chợ Thông Tin
Mua báo cáo "Cung Cầu Thị Trường" thay vì hỏi trực tiếp:
- "Hoàng Triều: đang thiếu 200 Hồi Nguyên Đan"
- "Tông Môn: dư 50 Đột Phá Đan muốn bán"

### Thương Hội — Giao Dịch Ẩn Danh
- Đặt lệnh mua/bán không lộ danh tính
- Hai bên không biết nhau là ai cho đến khi giao dịch xong

### Pháp Gia — Môi Giới Hiệp Ước
- Đặt yêu cầu: "Tôi cần bảo vệ thương đội, trả 50 Linh Thạch/chuyến"
- Pháp Gia match với đối tác phù hợp
- Không cần chat dài dòng

### Hệ Thống Ký Hiệu Nhanh
Đặt trên map — không cần gõ:

| Ký Hiệu | Ý Nghĩa |
|---|---|
| 🤝 | Muốn hợp tác |
| ⚔️ | Thách đấu |
| 🛡️ | Cần bảo vệ |
| 💰 | Muốn mua |
| 📦 | Muốn bán |
| 🔍 | Tìm thông tin |
| ⚠️ | Cảnh báo khu vực nguy hiểm |

---

## Điểm Đặc Biệt — Tài Nguyên Có Thể Trao Đổi

### Các Hình Thức Giao Dịch

| Hình Thức | Mô Tả | Drama |
|---|---|---|
| Bán đứt | Chuyển quyền sở hữu hoàn toàn | Hối hận sau khi bán |
| Cho thuê | Quyền khai thác có thời hạn | Hết hạn bị outbid |
| Cổ phần | Nhiều thế lực cùng sở hữu | Âm mưu mua lại cổ phần |
| Thế chấp | Dùng làm đảm bảo cho vay | Không trả được → mất vị trí chiến lược |

**Ai xác nhận:** Pháp Gia — có chi phí, có thời gian xử lý.

### Các Loại Điểm Đặc Biệt

| Loại | Mô Tả | Giao Dịch |
|---|---|---|
| Điểm Khai Thác | Mỏ Huyền Tinh, Giếng Linh Khí | Cho thuê quyền khai thác |
| Truyền Thừa Võ Học | Cổ Tích có Bí Kíp — phải đến tại chỗ | Thu phí "học phí" |
| Vị Trí Địa Lý | Đèo núi, cầu sông, đỉnh cao | Thu phí thông hành |
| Điểm Linh Mạch | Buff passive, tăng theo thời gian chiếm | Tranh chấp liên tục |

---

## ❓ Câu Hỏi Mở

- [ ] Điều tra False Flag — 70% chính xác, 30% sai dẫn đến hậu quả gì?
- [ ] Tin đồn có thể bị trace về nguồn gốc không?
- [ ] Cổ phần — tỷ lệ chia lợi nhuận theo cơ chế nào?
- [ ] Pháp Gia môi giới — phí dịch vụ cụ thể bao nhiêu?
