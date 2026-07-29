# 🌪️ Phong Server

**Identity:** Cơ Động & Tình Báo
**Khắc:** Băng (gió thổi tan băng → vô hiệu phong toả của Băng)
**Bị khắc:** Băng (băng đóng cứng gió → vô hiệu cơ động của Phong)

> Phong và Băng là **cặp khắc chế cứng đối xứng** — nằm ngoài vòng ngũ hành. Khi gặp nhau, cả hai đều bị lột mất vũ khí signature cùng lúc → trận đấu rơi về tài nguyên/quân số thuần ("hai kỳ thủ cởi giáp").

---

## Triết Lý

```
Gió = vô hình, đi khắp nơi, chạm mọi thứ nhưng không giữ được gì
        ↓
Phong THẤY nhiều nhất, ĐI nhanh nhất — nhưng GIỮ kém nhất
        ↓
Sống bằng cơ động + thông tin + cướp đoạt, không bằng tích luỹ
```

**Cân bằng (ngoài ngũ hành → không bị -20% khắc chế):** trả giá bằng **phòng thủ giấy** (công trình/thành yếu, giữ đất kém) + **kinh tế du mục bấp bênh** (không sản xuất, không giữ được của → giàu từng cơn, không giàu bền).

**Bảng phase (từ README):** Phong yếu Khai Hoang (Tuần 1-3), mạnh Chiến Tranh Lớn (Tuần 9+).

---

## Cơ Chế Môi Trường — Bão Phong / Loạn Lưu

- Định kỳ có **bão đổi hướng gió** toàn map.
- **Gió xuôi** → quân đi cực nhanh; **gió ngược** → hành quân ì.
- Phong **dự báo & điều hướng** được gió → biến tốc độ thành vũ khí.
- Bão **thổi tan sương mù** tạm thời (liên hệ trực tiếp identity tình báo + cơ chế sương mù toàn map).

---

## Cơ Chế Tình Báo — "Thấy Vị Trí, Không Thấy Đường Đi"

Nguyên tắc trần (mô phỏng View Earth / View Air của Heroes 3, và cách H3 hiển thị quân số mờ):

> Phong thấy **VỊ TRÍ** vật thể/quân *ngay lúc này* — nhưng **KHÔNG** đọc được **ĐƯỜNG ĐI** (từ đâu tới, đích đến, tiến hay rút, ý đồ).

Gió chạm được vật cản hiện tại, nhưng không nhớ quá khứ, không đoán tương lai.

### Thang 3 cấp theo Linh Mạch

| Cấp | Tên | Thấy (mờ) | KHÔNG thấy (trần) |
|---|---|---|---|
| **Hạ** (Ngày 1) | Địa Phong Nhãn | Vị trí tài nguyên/địa hình ẩn trong vùng | Trữ lượng, loại — nhường Dị Tộc "đọc sâu" |
| **Trung** (Ngày 5) | Vân Du Nhãn | Vị trí *hiện tại* quân địch, phạm vi rộng | Đường đi — từ đâu, đến đâu, tiến/rút |
| **Thượng** (Ngày 8-10) | Thiên Phong Nhãn | Ảnh chụp vị trí *toàn server* định kỳ | Vẫn không lộ trình — chỉ loạt "ảnh tĩnh" rời rạc |

**Không giẫm chân Tình Báo Các:** Phong cho *bề rộng* (thấy khắp nơi có động tĩnh), Tình Báo Các cho *chiều sâu* (loại quân, số lượng thật, ý đồ). Bổ sung, không thay thế.

**Ở Thượng:** người chơi tự **nối các chấm** giữa hai lần quét để đoán hướng di chuyển → gameplay suy luận, đúng "Roleplay First".

### Hệ quả chiến thuật
- Khắc chế **phục kích/đánh úp về vị trí** (luôn biết địch ở đâu) — nhưng vẫn bị bất ngờ về **thời điểm & mục tiêu** (không biết đường đi). Không phá game Lôi (du kích) hay Tình Báo Các (giấu ý đồ).

---

## Kinh Tế — Cướp Đoạt (Talent Cướp Bóc)

Phong không sản xuất, không giữ được của → **sống bằng LẤY của người khác**. Người chơi Phong = tệp thích PvP, cơ hội, lướt sóng.

Cây talent cướp bóc (nhánh gợi ý — độ sâu chờ Army System):

| Nhánh | Nội dung | Đánh đổi |
|---|---|---|
| **Đoạt** | Cướp % tài nguyên cao hơn mỗi trận | Ôm nhiều → chậm → mất cơ động |
| **Tẩu** | Rút lui tức thì sau cướp, miễn truy kích | Yếu đánh trực diện |
| **Chặn** | Cắt hậu cần địch hiệu quả gấp bội | Vô dụng khi địch cắm chốt (Băng) |
| **Tiêu thụ** | Rửa/bán đồ cướp nhanh, khó truy nguồn | — |

**Cái phanh chống-OP (giữ chặt):** phòng thủ giấy + không tích luỹ được → cướp bao nhiêu cũng phải tiêu/gửi ngay → Phong "giàu nhanh rồi hết", không bao giờ giàu to. Cướp được kho lớn → không thủ nổi → phải gửi bên khác giữ hộ (→ dẫn tới Băng làm kho ký gửi).

---

## Địa Hình

### Bắt buộc
- **Đồng bằng gió lộng / thảo nguyên trống** — bão mạnh nhất, cơ động tối đa, nhưng không chỗ nấp (phòng thủ giấy).
- **Hẻm Gió (canyon hẹp)** — gió dồn tốc độ cực cao, chốt chặn chiến lược.
- **Cột Phong Tiêu / tháp quan sát tự nhiên** — đọc hướng gió sớm = lợi thế tình báo.

### Random (50%)
- **Mắt Bão vĩnh cửu** — vùng lặng gió giữa map, nơi *duy nhất* Phong mất buff; ai giữ được thì an toàn.

---

## Linh Mạch (Buff/Debuff signature)

- **Hạ:** +30% tốc độ hành quân quân trong vùng (cao nhất trong Linh Mạch Hạ). + Địa Phong Nhãn (xem bảng tình báo).
- **Trung — Thuộc Tính Phong:** Linh Thạch Phong (tiêu hao) → nâng quân cấp 2 Phong; +1 bậc tầm/tốc do thám; thổi loãng sương mù trong vùng. + Vân Du Nhãn.
- **Thượng — "Cửu Thiên Phong Mạch":**
  - BUFF: điều hướng Bão Phong toàn server; quân cấp 2 Phong miễn "gió ngược"; +20% tốc độ hành động toàn thế lực; Thiên Phong Nhãn (quét toàn map định kỳ, chỉ vị trí).
  - DEBUFF địch: thổi gió ngược vào đại quân địch → ì; "màn gió" che tình báo vùng Phong; đoàn tiếp tế địch trong bão lạc đường/tổn thất.

**Luật khi gặp Băng Thượng:** hiệu ứng "điều gió" và "điều băng" **triệt tiêu nhau** trong vùng tranh chấp (băng đóng thì gió không thổi tan được, gió thổi thì băng không đóng cứng).

---

## Quân Cấp 2 (chủ đề: tốc độ, luồn lách, cắt hậu cần)

> ⚠️ Chờ Army System hoàn thiện — bảng dưới là gợi ý gán theo thế lực.

| Thế lực | Quân cấp 2 (gợi ý) | Đặc tính |
|---|---|---|
| Tình Báo Các | Truy Phong Ảnh Vệ | Nhanh nhất game, do thám + ám sát tướng |
| Thế Gia | Ngự Phong Kỵ | Kỵ lướt gió, đánh xong rút trước khi bị phản |
| Tông Môn | Phong Linh Tán Tu | Pháp thuật tầm xa cơ động, đánh-chạy |
| Dị Tộc | Phong Dực Thú | Bay/vượt địa hình, cắt đường tiếp tế |

---

## Drama Signature — "Bán Toạ Độ"

Phong thấy vị trí mọi thế lực → **thông tin vị trí trở thành hàng hoá**. Phong bán "địch đang ở đâu" cho bên trả giá cao. Nhưng bán tin thật hay tin sai? Nói dối một lần → mất uy tín cả cụm.

Vai trò endgame (xem `DISCUSSION/ideas_backlog.md` → Chùm Endgame): Phong là **kẻ định đoạt "ai đi ai ở"** — bán tin "nhà ai đang trống" khi kẻ mạnh dồn quân vào tháp, tạo mặt trận hậu phương.

Drama phụ:
- **Không giữ nổi của cải** — cướp được kho lớn nhưng thủ dở → phải gửi Băng hoặc tiêu ngay.
- **Báo động giả** — quét thấy đại quân tụ biên giới nhưng không đọc được đường đi → hô liên minh nhầm → mang tiếng "kẻ hô hoán".
- **Kẻ chặn đường** — cả cụm ghét Phong nhưng cần thuê Phong cắt hậu cần kẻ thù chung → lính đánh thuê ai cũng cần, ai cũng đề phòng.

---

## Quan Hệ Cộng Sinh Gượng Ép: Phong ↔ Băng

```
PHONG = kẻ cướp đường, bán tin, không giữ được của
BĂNG  = người giữ đường, giữ của hộ, không đi cướp
        ↓
Phong cướp được → không thủ nổi → gửi Băng giữ
Băng giữ hộ chính đồ Phong cướp từ kẻ khác
        ↓
"Kẻ trộm" và "két sắt" buộc hợp tác — nhưng chẳng ai tin ai
```

Đối lập cả **cơ chế chiến đấu lẫn đạo đức xã hội**. Cụm có cả Phong + Băng gần như đảm bảo có cốt truyện hay. Phong cũng là **thuốc giải kinh tế** cho nhà băng Băng (cắt caravan mang đồ đi gửi, tấn công khi kho Băng đầy).

---

## ❓ Câu Hỏi Mở

- [ ] Cây talent cướp bóc đào sâu tới mức nào (chờ Army System)?
- [ ] Quân cấp 2 — xác nhận gán thế lực khi có danh sách 10 thế lực chuẩn.
- [ ] Phong Hạ nhìn tài nguyên ẩn có làm loãng vai trò Dị Tộc không? (Hướng gỡ: Phong thấy "có tài nguyên" mờ, Dị Tộc mới biết "là gì + khai thác được".)
- [ ] Tần suất & cường độ Bão Phong cụ thể.
- [ ] Cơ chế "bán toạ độ" — tin thật/giả xử lý thế nào ở tầng hệ thống?
