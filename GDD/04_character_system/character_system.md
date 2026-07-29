# Hệ Thống Nhân Vật

## Thuộc Tính Cơ Bản (Sinh Ra Đã Có)

| Thuộc Tính | Ký Hiệu | Ảnh Hưởng |
|---|---|---|
| Căn Cốt | 骨 | Nền tảng tu luyện, quyết định **trần cảnh giới** |
| Tâm Tính | 心 | Trung thành, đạo đức, ảnh hưởng loyalty |
| Trí Tuệ | 智 | Học skill nhanh hay chậm, chiến thuật |
| Thể Chất | 體 | HP, chịu đòn, sức bền hành quân |
| Thiên Duyên | 緣 | May mắn, tỷ lệ đột phá, tỷ lệ gặp cơ duyên |

---

## Cảnh Giới & Tuổi Thọ

| Cảnh Giới | Tuổi Thọ Game | Ngày Thực |
|---|---|---|
| Luyện Khí (1-9 tầng) | ~100 năm | ~10 ngày |
| Trúc Cơ | 200 năm | 20 ngày |
| Kim Đan | 500 năm | 50 ngày |
| Nguyên Anh | 1000 năm | 100 ngày |
| Hóa Thần | 2000+ năm | 200+ ngày |

### Trần Cảnh Giới Theo Căn Cốt

| Căn Cốt | Tối Đa |
|---|---|
| 1-3 sao | Trúc Cơ |
| 4-5 sao | Kim Đan |
| 6-7 sao | Nguyên Anh |
| 8-9 sao | Hóa Thần |
| 10 sao (Thiên Phàm) | Không giới hạn |

---

## Skill Tree — Heroes 3 Style

Mỗi lần lên cảnh giới → chọn **1 trong 3 skill random** từ pool class.

```
Ví dụ Tông Môn — Luyện Khí tầng 3:
┌─────────────────┬─────────────────┬─────────────────┐
│  Kiếm Ý Cơ Bản │  Độn Thuật Nhập │  Linh Lực Cảm   │
│  +15% kiếm dmg  │  Môn tốc độ +10 │  Ứng tỷ lệ đột  │
│                 │                 │  phá +5%        │
└─────────────────┴─────────────────┴─────────────────┘
Chọn 1 → lock vào slot
```

---

## Hệ Thống Role

### 7 Role Cơ Bản

| Role | Passive Pool | Đặc Điểm |
|---|---|---|
| ⚔️ Đấu Sĩ | Chịu đòn thay, Phản kích, Kiên định | Cận chiến damage ổn định |
| 🛡️ Tanker | Đại Địa Căn, Kết Giới Nhỏ | Giữ tuyến, hút damage |
| 🗡️ Sát Thủ | Ẩn Thân, Đòn Chí Mạng, Nhẹ Công | Burst damage, ám sát |
| 🏹 Xạ Thủ | Tầm Xa, Địa Hình Lợi, Ngắm Bắn | An toàn, tầm xa |
| 🔮 Pháp Sư | Linh Lực Tụ, Khuếch Đại, Nguyên Tố Cộng Hưởng | AOE, element damage |
| 💚 Phụ Trợ | Hào Quang, Cứu Chữa, Phát Hiện Ẩn | Buff/heal/hậu cần |
| 📋 Mưu Sĩ | Thống Lĩnh, Địa Lợi, Hậu Cần | Chiến thuật, chỉ huy |

### Active Skill — Phải Đi Học

Mỗi tướng chỉ có **1 Active Skill** — phải đến nơi học hoặc có Bí Kíp.

**Cách học:**
- Đến tận nơi thế lực đó học trực tiếp
- Mời Sư Phụ về dạy (tốn tài nguyên, có thể bị cướp trên đường)
- Lấy được Bí Kíp (loại C — 1 lần, tranh giành gay gắt)
- **Bắt tù nhân** → ép học skill (xem phần Tù Nhân)

---

## Role Đặc Thù

### Sinh Ra Sẵn (Thiên Phú Ẩn)
- Tỷ lệ: **1/500** nhân vật
- Không hiện thị khi mới vào — trông như role thường
- Thức tỉnh khi đủ điều kiện ngẫu nhiên
- Thông báo **toàn server** khi thức tỉnh

### Chuyển Hóa (Đủ Điều Kiện)

Cần đủ **3 lớp điều kiện:**

| Lớp | Điều Kiện |
|---|---|
| Cá Nhân | Cảnh giới tối thiểu + số trận kinh nghiệm + stat ngưỡng |
| Thế Lực | Phải có quan hệ với thế lực liên quan đồng ý truyền thừa |
| Môi Trường | Một số role chỉ chuyển hóa được ở server element phù hợp |

### Ví Dụ Role Đặc Thù

| Role | Gốc | Điều Kiện | Server |
|---|---|---|---|
| Kiếm Tiên | Đấu Sĩ | Kim Đan + 50 trận thắng + Tông Môn truyền thừa | Kim, Phong |
| Hỏa Công Sư | Xạ Thủ | Trúc Cơ + Hoả server + Đan Môn Hỏa Đan | Hoả |
| Dược Sư | Phụ Trợ | Kim Đan + Đan Môn truyền thừa + 100 đan bào chế | Mộc, Hoả |
| Ảnh Vệ | Sát Thủ | Kim Đan + Tình Báo Các + 20 nhiệm vụ bóng tối | Phong, Băng |
| Lôi Pháo Thủ | Pháp Sư | Nguyên Anh + Lôi server + Phù Lục hợp tác | Lôi |
| Thuỷ Quân Đô Đốc | Mưu Sĩ | Kim Đan + Thuỷ server + Linh Mạch Thượng | Thuỷ |
| Địa Linh Sư | Tanker | Nguyên Anh + Thổ server + Địa Long Thạch | Thổ |
| Đại Nguyên Soái | Mưu Sĩ | Trúc Cơ + Hoàng Triều + 10 trận chỉ huy liên quân | Thổ, Kim |

### Slot Giới Hạn

| Cơ Chế | Mô Tả |
|---|---|
| Slot cố định | Ví dụ: Kiếm Tiên 2 slot / server |
| Mở slot | Đánh bại người đang giữ slot trong thách đấu |
| Từ chối thách đấu | Có thể từ chối 24h nhưng -20% uy tín |
| Từ chối 3 lần | Pháp Gia tự động tước danh hiệu |

### Rớt Hạng — Giữ Một Nửa

```
Bị rớt hạng → quay về role gốc

MẤT:                          GIỮ:
├── Danh hiệu                 ├── Passive Pool đặc thù (-30%)
├── Active Skill đặc thù      ├── Cảnh giới & kinh nghiệm
└── Slot                      └── "Dư Vang" — buff ẩn
```

**Dư Vang theo role:**
- Kiếm Tiên → Dư Vang Kiếm Khí: đòn đánh có kiếm ý, địch thấy "Cựu Kiếm Tiên" giảm sĩ khí
- Dược Sư → Dư Vang Dược Hồn: đan dược dùng hiệu quả hơn 20%
- Ảnh Vệ → Dư Vang Hư Ảnh: vẫn ẩn thân ngắn hạn được

---

## Thức Tỉnh Linh Mạch

```
Nhân vật bình thường → Linh Mạch ẨN
        ↓
Đến điều kiện nhất định → Thức Tỉnh Event
        ↓
Thông báo toàn server → cả server náo loạn → tranh giành
```

**Ví dụ — Hoàng Tử Phế Z:**
- Xuất thân: Hoàng Triều, con thứ bị phế, giá trị gần như 0
- Thức Tỉnh: **Đan Đạo Thiên Phàm**
- Talent đặc biệt: mỗi lần đột phá cảnh giới → +1 Talent Point nhánh Dược

---

## Aging & Truyền Thừa

**Khi lão thành sắp chết:**
- Truyền 1 skill → đệ tử học ngay không cần level
- Để lại Di Vật → item tăng stats
- Để lại Bí Kíp → mở nhánh skill mới

**Nếu chết đột ngột (chiến trận, ám sát):**
- Mất tất cả — không kịp truyền thừa gì
- → Động lực bảo vệ nhân vật quan trọng

---

## Quan Hệ Nhân Vật

Cùng hoạt động → tích lũy Quan Hệ → mở Bond Skill:

| Loại Quan Hệ | Bond Skill |
|---|---|
| Sư Đồ | Đồ Đệ học nhanh hơn 20% |
| Huynh Đệ | Buff nhau khi cùng chiến trường |
| Tình Địch | Debuff nhau nhưng cả hai mạnh hơn khi gần |
| Ân Oán | Một bên chết → bên kia bạo phát sức mạnh |

---

## Tù Nhân — Khai Thác Skill

Tướng bị bắt trong chiến trận:

| Lựa Chọn | Kết Quả |
|---|---|
| Đòi Chuộc | Nhận tài nguyên, tướng trở về |
| Chiêu Hàng | Dụ dỗ loyalty, giữ lại phục vụ |
| **Ép Học Skill (C)** | Tình Báo + Đan Môn tra tấn → lấy được 1 phần skill, tướng gốc **tụt 1 tier skill** |
| Xử Tử | Tạo thù oán vĩnh viễn |
| Thả Không Điều Kiện | +Nhân Đức, tạo ân tình |

---

## ❓ Câu Hỏi Mở

- [ ] Số lượng slot role đặc thù cho từng loại cụ thể?
- [ ] Bond Skill có giới hạn số lượng không?
- [ ] Thiên Duyên ảnh hưởng chất lượng Cơ Duyên thế nào cụ thể?
- [ ] Tuổi thọ có hiển thị cho người chơi không?
