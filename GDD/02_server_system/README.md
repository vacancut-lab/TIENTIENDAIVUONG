# Hệ Thống Server

## Pool 8 Element

| Element | Identity | Trạng Thái |
|---|---|---|
| 🔥 Hoả | Bùng Nổ & Khan Hiếm | ✅ Hoàn chỉnh |
| ⚙️ Kim | Công Nghệ & Thực Dụng | ✅ Hoàn chỉnh |
| 🌿 Mộc | Yên Ổn & PvE | ✅ Hoàn chỉnh |
| 💧 Thuỷ | Đoàn Kết & Máu Trâu | ✅ Hoàn chỉnh |
| 🏔️ Thổ | Đông Dân & Nền Tảng | ✅ Hoàn chỉnh |
| ⚡ Lôi | Tinh Anh & Độc Lập | ✅ Hoàn chỉnh |
| 🌪️ Phong | ??? | ❌ Chưa thiết kế |
| ❄️ Băng | ??? | ❌ Chưa thiết kế |

---

## Cấu Trúc Cụm Server

- **5 server / cụm** — chọn ngẫu nhiên có kiểm soát từ pool 8
- Mỗi ngày mở 1 cụm mới
- Đảm bảo đa dạng vai trò: ít nhất 1 Sản Xuất + 1 Quân Sự + 1 Hỗ Trợ

### Quy Tắc Chọn Server Cho Cụm

```
BƯỚC 1 — Loại trừ element quá giống nhau
BƯỚC 2 — Đảm bảo có Sản Xuất + Quân Sự + Hỗ Trợ
BƯỚC 3 — Random 2 slot còn lại
BƯỚC 4 — Kiểm tra không element nào bị khắc bởi 2 element khác
```

### Ví Dụ Cụm Hợp Lệ

| Cụm | Thành Phần | Đặc Điểm |
|---|---|---|
| #001 Ngũ Hành Cơ Bản | Hoả + Kim + Mộc + Thuỷ + Thổ | Cụm lý tưởng cho server đầu — dễ học |
| #002 Phong Bạo | Lôi + Phong + Hoả + Thổ + Thuỷ | Thổ trở thành quyền lực vì ai cũng cần |
| #003 Băng Hỏa | Băng + Hoả + Kim + Mộc + Phong | Băng + Hoả đối lập cực đoan |

---

## Layout Server

### Hex Grid

- Căn cứ spawn: random đảm bảo khoảng cách tối thiểu
- Sương mù toàn map — Tình Báo & Phong có giá trị ngay ngày 1

### Linh Mạch 3 Cấp

```
LINH MẠCH HẠ (8-10 cái):
└── Gần spawn, vòng 1. Quái yếu. Linh Thạch Thường.
    Mở từ Ngày 1.

LINH MẠCH TRUNG (4-5 cái):
└── Vòng 2, tranh chấp chính. Mang thuộc tính element server.
    Nguyên liệu nâng quân cấp 2. Mở từ Ngày 5.

LINH MẠCH THƯỢNG (1 cái):
└── Trung tâm server. Quái cực mạnh — hồi sinh 3 ngày.
    Buff + Debuff lớn. Mở Ngày 8-10.
```

### Vùng Ranh Giới & Cổng Dịch Chuyển

- Giữa 2 server = vùng đệm trung lập rộng 1-2 hex
- Tài nguyên tier 2 xuất hiện ở vùng đệm
- **Thăm dò theo role thế lực**: Phong/Trinh Thám nhanh nhất, Dị Tộc phát hiện tài nguyên ẩn
- **Cổng Dịch Chuyển**: Phù Lục Đường xây tại ranh giới — tốn tài nguyên tier 3-4, 3-5 ngày xây
- Ai kiểm soát Cổng = kiểm soát giao thương xuyên server

---

## Khắc Chế Ngũ Hành

```
Mộc → Thổ → Thuỷ → Hoả → Kim → Mộc
```

Khắc chế tạo penalty **-20%** trên chiến trường.  
Lôi, Phong, Băng nằm ngoài vòng ngũ hành — counter theo cơ chế riêng.

---

## Mạnh Yếu Theo Giai Đoạn

| Phase | Mạnh Nhất | Yếu Nhất |
|---|---|---|
| Khai Hoang (Tuần 1-3) | Thổ, Kim, Mộc | Lôi, Phong |
| Tranh Bá (Tuần 4-8) | Hoả + Kim combo | Thổ (đông nhưng không tinh) |
| Chiến Tranh Lớn (Tuần 9+) | Thuỷ, Lôi, Phong | Ai không có đồng minh |

---

## ❓ Câu Hỏi Mở

- [ ] Phong server identity là gì?
- [ ] Băng server identity là gì?
- [ ] Số lượng tối đa thế lực trong 1 server: 30 hay có thể điều chỉnh?
