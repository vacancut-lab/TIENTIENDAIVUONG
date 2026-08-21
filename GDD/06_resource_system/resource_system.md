# Hệ Thống Tài Nguyên

> Tham khảo cấu trúc **Heroes 3** (2 tầng: tiền vạn năng + tài nguyên hiếm), nhưng tiền tệ có **ma sát** (3 mệnh giá, đổi ngược lossy, tỷ giá thả nổi) — sâu hơn Gold của Heroes 3.

---

## Cấu Trúc 2 Tầng (ánh xạ Heroes 3)

| Heroes 3 | Vai trò | Bản game |
|---|---|---|
| Gold | Tiền vạn năng | **Linh Thạch** (3 mệnh giá Hạ/Trung/Thượng) |
| Wood + Ore | Phổ thông | **Gỗ, Đá, Lương thực** (tài nguyên xây dựng cơ bản) |
| Mercury/Sulfur/Crystal/Gems | Hiếm | **Tài nguyên đặc thù theo server** (Lôi Châu, Hoả Long Cốt, Vạn Niên Hàn Thiết…) |

> Điểm mạnh hơn Heroes 3: tài nguyên hiếm **đặc trưng theo server** (không rải toàn map) → ép giao thương xuyên server → đúng **Scarcity-Driven**.

---

## Linh Thạch — Tiền Tệ 3 Mệnh Giá

```
1 Trung   = 1000 Hạ
1 Thượng  = 1000 Trung
```

**Quang phổ từ tiền tiêu → tài sản tích trữ** (không phải "cùng một tiền to nhỏ"):

| Mệnh giá | Vai trò (như Heroes 3) | Độ dồi dào |
|---|---|---|
| **Hạ** | Tiền tiêu hằng ngày (như Gold) — mọi giao dịch nhỏ | Dồi dào |
| **Trung** | Trung gian | Vừa |
| **Thượng** | Tài sản đầu tư / đầu vào **quân tier cao** (như Crystal) | **Hiếm** |

---

## Luật Đổi Mệnh Giá — Có Ma Sát

### Đổi xuôi (gom lên): MIỄN PHÍ
```
1000 Hạ → 1 Trung        1000 Trung → 1 Thượng      (không mất mát)
```

### Đổi ngược (bổ nhỏ): LOSSY (mất mát)
```
Hạ ← Thượng: mất một phần    (ví dụ 1500 Hạ : 1 Thượng — con số cần chốt)
```
- Mỗi lần đổi ngược = tài nguyên **bốc hơi** khỏi nền kinh tế → **sink tự nhiên** (đúng "tài nguyên phải chảy ra").
- **Nhà băng (Băng) đổi ngược hiệu quả hơn** nhờ kho gộp → ăn **spread**. Băng không "in tiền", nó **bán tỷ giá tốt hơn**.

### Tỷ giá đổi ngược
- **Do server Băng đặt** (có Băng trong cụm): 1 Băng = độc quyền; 2 Băng = cạnh tranh phá giá.
- **Sàn mặc định của game** (luôn tồn tại, kể cả cụm không-Băng): tỷ giá "chợ đen" tệ, làm **phanh** chống độc quyền Băng + cứu cụm không-Băng.

---

## Kho Có Giới Hạn Ô

- Kho giới hạn số ô → ai nghèo/vác nhiều **tự chọn** gom lên Thượng để đủ chỗ.
- **Gom là TỰ CHỌN, không tự động** (đúng tinh thần "không cưỡng bức").
- Hệ quả: của cải giàu bị dồn thành mệnh giá cao → **illiquid** ("đóng băng") → cầu dịch vụ đổi tiền của Băng.

---

## Cơ Chế Anti-Snowball Nội Tại

```
Bị cướp mỏ Thượng → mất nguồn Thượng → yếu đi
        ↓
Cắn răng đổi ngược (chịu lỗ) → gom đủ Thượng → mua quân tier cao SỚM → phản công
```
- Người mạnh (có mỏ, dư Thượng) không cần đổi ngược; chỉ **kẻ bị dồn** mới phải → đổi ngược **đánh thuế kẻ thua để cho họ cơ hội lật kèo** (anti-snowball, không phát đồ miễn phí).
- Vì đổi ngược lossy → mệnh giá nhỏ *biến mất dần* khỏi lưu thông → cuối season Hạ/Trung cực hiếm → khan hiếm gắt dần (hợp endgame căng).

---

## Hệ Quả Theo Cụm

- Cụm **không có Băng** → ai cũng chịu tỷ giá sàn → Thượng đắt đỏ → **lên quân tier cao chậm hơn**.
- → Mỗi cụm có "khí hậu tài chính" khác nhau → người chơi *mừng* khi cụm có Băng, *tiếc* khi không → **Every Faction Matters**.

---

## ❓ Câu Hỏi Mở

- [ ] Tỷ lệ phạt đổi ngược cụ thể (1500:1? khác?) + biên độ Băng cải thiện.
- [ ] Tầng "phổ thông" gồm mấy loại (gỗ/đá/lương riêng hay gộp)?
- [ ] Số ô kho cụ thể + có nâng cấp không.
- [ ] Linh Thạch Hạ có phải tiền cho **mọi** giao dịch, hay có loại giao dịch chỉ nhận Thượng?
