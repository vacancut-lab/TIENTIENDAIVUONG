# Emergent Combo System

## Triết Lý

```
Combo KHÔNG được thông báo trước
Người chơi tình cờ kết hợp → hiệu ứng lạ xuất hiện
Hệ thống log: "Hiệu Ứng Chưa Được Đặt Tên Phát Sinh"
Người chơi đặt tên → tên đó vào lịch sử server
Người phát hiện buff khi dùng combo đó (luôn mạnh hơn người học lại)
```

---

## Ma Trận Combo Cặp Đôi Cơ Bản

|  | Hoả | Mộc | Thổ | Kim | Thuỷ | Lôi | Phong | Băng |
|---|---|---|---|---|---|---|---|---|
| **Hoả** | — | Cháy | Nổ | Nung | Hơi Nước | Sét Lửa | Bão Lửa | Hơi |
| **Mộc** | Cháy | — | Rễ Đất | Cưa | Lũ | Sét Thảo | Bay | Đông |
| **Thổ** | Nổ | Rễ Đất | — | Quặng | Bùn | Địa Chấn | Cát | Đóng Băng Đất |
| **Kim** | Nung | Cưa | Quặng | — | Rỉ Sét | Dẫn Điện | Kiếm Gió | Thép Băng |
| **Thuỷ** | Hơi Nước | Lũ | Bùn | Rỉ Sét | — | Sét Nước | Sóng | Băng |
| **Lôi** | Sét Lửa | Sét Thảo | Địa Chấn | Dẫn Điện | Sét Nước | — | Bão Lôi | Đóng Băng Lôi |
| **Phong** | Bão Lửa | Bay | Cát | Kiếm Gió | Sóng | Bão Lôi | — | Bão Tuyết |
| **Băng** | Hơi | Đông | Đóng Băng Đất | Thép Băng | Băng | Đóng Băng Lôi | Bão Tuyết | — |

---

## Combo Đã Biết — Ví Dụ

### Cặp Đôi

| Combo | Element | Hiệu Ứng |
|---|---|---|
| **Độc Phong Trận** | Dị Tộc (Độc) + Phong server | Phong khuếch tán Độc nhanh diện rộng, bám vào địch đang chạy trốn |
| **Hơi Nước Mù** | Hoả + Thuỷ | Sương mù chiến trường dày đặc |
| **Dẫn Điện** | Kim + Lôi | Vũ khí Kim dẫn sét → AoE điện quanh mục tiêu |
| **Bùn Lầy** | Thuỷ + Thổ | Làm chậm toàn vùng, kỵ binh gần như không di chuyển được |
| **Sóng Thần** | Thuỷ + Phong | Sóng cuốn quân tier thấp |

### Ba Chiều

| Combo | Element | Hiệu Ứng |
|---|---|---|
| **Lôi Độc Bão** | Độc + Phong + Lôi | Phong khuếch tán Độc, Lôi kích hoạt Độc nổ tung — AOE cực lớn |
| **Băng Tiêu Địa Sụt** | Băng + Thổ + Kim | Địa hình đóng băng → nâng lên → Kim xuyên phá → chôn vùi quân địch |
| **Màn Sương Mù Thiêu Đốt** | Hoả + Thuỷ + Phong | Hơi nước dày + gió cuốn → địch không nhìn thấy + bị bỏng |

### Phi Chiến Đấu

| Combo | Thế Lực | Hiệu Ứng |
|---|---|---|
| **Cartel** | Thương Hội (Độc Quyền) + Tình Báo (Thông Tin) | Kiểm soát kinh tế toàn server không cần quân đội |
| **Lương Vũ Khí Liên Minh** | Thổ (Lương) + Kim (Vũ Khí) | Quân đội Kim mạnh nhất, Thổ nuôi được đại quân lớn nhất |
| **Thiên Đạo Luật** | Pháp Gia (Lập Pháp) + Tông Môn (Công Nhận) | Vi phạm = debuff từ chính game system |

---

## Số Lượng Combo Lý Thuyết

```
8 element × 10 thế lực × 4-5 nhánh talent
× combo cặp đôi + ba chiều
× biến số nhân vật × địa hình server
        ↓
Số combo designer biết trước: ~50
Số combo người chơi sẽ tìm ra: không giới hạn
```

---

## Hệ Thống Ghi Nhận

```
Combo mới xuất hiện:
        ↓
Server log: "[Thế Lực X] và [Thế Lực Y] vừa tạo ra
            hiệu ứng chưa từng thấy tại [Tọa độ]"
        ↓
Dev nhận notification
        ↓
Quan sát:
├── Quá mạnh → nerf nhẹ qua hotfix
├── Thú vị → buff thêm, đặt tên chính thức
└── Broken → hotfix ngay (Claude Code)
        ↓
Patch note: "Độc Phong Trận — phát hiện bởi [Tên]
             Season 1, Ngày 22, Năm 220"
→ Lịch sử game do người chơi viết
```

---

## ❓ Câu Hỏi Mở

- [ ] Combo có được lưu vào Thư Viện Server — người khác xem được không?
- [ ] Buff người phát hiện combo — cụ thể bao nhiêu %?
- [ ] Combo bị nerf — người phát hiện có mất buff không?
- [ ] Có thể có combo 4 chiều không?
