# Ideas Backlog

Ý tưởng chưa được thiết kế chi tiết — để dành cho các session sau.

---

## Hệ Thống Chưa Thiết Kế

| Hệ Thống | Mô Tả Ngắn | Ưu Tiên |
|---|---|---|
| **Combat System** | Turn-based? Real-time? Grid tactics? | 🔴 Cao |
| **Map Hex Chi Tiết** | Layout Tiểu Đại Lục, phân bố tài nguyên | 🔴 Cao |
| **Chiến Trường Trung Tâm Cụm** | 5 server va chạm, điểm kiểm soát | 🔴 Cao |
| **Season End & Reset** | Xếp hạng, phần thưởng, giữ gì sang season mới | 🟡 Trung |
| **Boss Cụm** | Boss xuất hiện ngày 14, buộc hợp tác tạm thời | 🟡 Trung |
| **Talent Tree Chi Tiết** | Tier 1→5 từng nhánh của tất cả thế lực | 🟡 Trung |
| **Cơ Chế Giao Thương** | Chợ, Thương Đội, tuyến đường, phí | 🟡 Trung |
| **Báo Cáo Sáng** | UI/UX luồng thông tin khi mở game | 🟢 Thấp |
| **Lệnh Điều Kiện Interface** | Bao nhiêu loại, cách đặt lệnh | 🟢 Thấp |
| **Investigation System** | Điều tra manh mối, độ chính xác, hậu quả | 🟢 Thấp |
| **Chợ Đen** | Mua bán danh tính giả, vật phẩm cấm | 🟢 Thấp |

---

## Ý Tưởng Thú Vị Chưa Được Thảo Luận

- **Lịch sử server** — ghi lại các sự kiện lớn, người chơi đọc lại được
- ~~**Phong server** — thế lực "thông tin"~~ ✅ Đã thiết kế → `02_server_system/phong_server.md`
- ~~**Băng server** — kiểm soát và làm chậm~~ ✅ Đã thiết kế → `02_server_system/bang_server.md`
- **Seasonal Events** — sự kiện đặc biệt theo "thời tiết" game
- **Liên Server Trading Post** — chợ giữa các server trong cụm
- **Espionage Missions** — nhiệm vụ tình báo có narrative riêng
- **Thiên Đạo Events** — sự kiện toàn cụm buộc tất cả hợp tác hoặc đối đầu

---

## Cơ Chế Đã Thảo Luận Nhưng Chưa Chốt Hoàn Toàn

- **Thế hệ nhân vật** — 140 năm = 3-4 thế hệ, truyền thừa liên tục
- **Di Dân Chiến Lược** — Thổ đưa dân sang server khác
- **Ngân Trang** — Thương Hội Kim server cho vay lãi suất
- **Bảo Hiểm Thương Đội** — cơ chế chi tiết
- **Phản Gián** — Tình Báo phát hiện nội gián, bẫy ngược

---

## 🏔️ CHÙM ENDGAME — "Tháp / Library" (Session 2)

> **Cảnh báo phụ thuộc:** Toàn bộ chùm này đứng trên **Combat System** + **Map Hex** + **Army System** — cả ba đều CHƯA thiết kế. Giữ ở tầng **nguyên tắc**, KHÔNG đóng chi tiết cho tới khi ba hệ nền thành hình. Nếu không sẽ phải thiết kế lại.

Chùm ý tưởng liên hoàn sinh ra khi thiết kế kinh tế Băng/Phong. Đã thống nhất về **triết lý cân bằng**, chưa thống nhất **con số & luật cụ thể**.

### Nguyên tắc cân bằng cốt lõi (đã thống nhất)

```
KHÔNG chống snowball bằng cách giảm phần thưởng.
CHỐNG snowball bằng cách ép/dụ người chơi VA CHẠM liên tục.
→ Của cải không bao giờ đứng yên đủ lâu để tích thành lợi thế bền.
→ Mọi con đường lên đỉnh đều bắt buộc hở sườn.
```

### Các mảnh ý tưởng

| Mảnh | Nội dung | Trạng thái |
|---|---|---|
| **Library (Băng Vực)** | Công trình endgame lấy cảm hứng Library of Enlightenment (Heroes 3). "Thứ không ai từ chối được". Kích hoạt khi **đủ người**. Liên kết đa khu vực → tạo **đấu trường** | Nguyên tắc |
| **Tháp / Ảo Cảnh Thí Luyện** | Đấu trường leo tầng. Có thời gian di chuyển giữa các tầng ("đến tháp tiếp theo") | Nguyên tắc |
| **Lính đánh thuê (tier quân đặc thù)** | Tier quân cao đặc biệt. Talent: **tăng năng lực đặc thù của người thắng** | Nguyên tắc |
| **Chết 2 nơi khác nhau** | Chết ở **nhà/chiến trường thật** = KHÔNG hồi sinh (vĩnh viễn, đắt). Chết trong **tháp (ảo cảnh)** = hồi sinh được, RẺ | Nguyên tắc |
| **Canh bạc "đi hay ở"** | Đăng ký quân vào đấu trường = rút khỏi phòng thủ nhà. Đi quá sớm/quá nhiều → bị đấm nhà, mất mỏ. Đi quá muộn/ít → không thắng nổi tháp | Nguyên tắc |
| **Đấm nhà = người TRONG server** | Giai đoạn đầu giới hạn "đấm nhà" trong phạm vi server gốc (chưa mở xuyên khu vực — chờ Map & Combat) | Nguyên tắc |
| **Phong bán intel** | "Ai đi ai ở" phụ thuộc tình báo. Phong thấy nhà ai trống → bán thông tin → dẫn người khác đi đấm nhà. Phong = kẻ định đoạt endgame | Nguyên tắc |
| **Mất nhà = khoản đầu tư** | Phần thưởng tháp đủ lớn để **đòi lại** nhà đã mất → người chơi dám cược nhà lấy thưởng | Nguyên tắc |
| **Ô băng bắt PK** | Chiến trường liên-sv có ô băng bắt buộc PK để lấy tài nguyên hiếm. Dày hơn ở cụm-có-Băng (nerf đúng nơi snowball) | Nguyên tắc |
| **Nerf Băng vĩ mô** | Băng bôi trơn kinh tế → cụm snowball nhanh → nerf bằng cách ép cụm đánh nhau liên tục. Băng bị kéo ra trận qua lợi ích tín dụng (phải cứu con nợ) | Nguyên tắc |

### ❓ Câu hỏi treo — phải chốt khi làm hệ nền

- [ ] **Boost người thắng**: vĩnh viễn cả season hay tạm thời/suy giảm dần? *(khuyến nghị: tạm thời — tránh snowball. Lưu ý: đây là lo ngại SNOWBALL, KHÔNG phải P2W — thưởng giành bằng PvP không vi phạm anti-P2W)*
- [ ] **Kẻ THUA tháp được gì?** Cần phần an ủi để không tay trắng → giữ cửa lật kèo. *(Đề xuất: thua tháp = mất phần thưởng + hồi quân tốn phí, KHÔNG mất quân vĩnh viễn)*
- [ ] **"Đòi lại nhà" khó tới đâu?** Phải nằm khoảng giữa: đủ khả thi để dám cược, đủ tốn kém để kẻ đấm nhà vẫn lời. 3 điều kiện giữ chặt: (1) kẻ đấm nhà giữ được thành quả một thời gian; (2) đòi lại phải TIÊU nguồn lực; (3) không phải lúc nào cũng đòi lại đủ (thủ tốt/liên minh có thể giữ)
- [ ] **Library độc quyền Băng hay công trình chung** đặt ở đất Băng? *(khuyến nghị: chung + lợi thế sân nhà — tránh Băng gánh cả kinh tế lẫn cửa endgame)*
- [ ] **"Thứ không thể từ chối" là gì?** *(khuyến nghị: tài nguyên hiếm + cơ hội/quyền, TRÁNH sức mạnh vĩnh viễn. "Không từ chối" = sức hút, không phải cưỡng bức — giữ Bế Quan chỉ là lớp hỗ trợ tài nguyên)*
- [ ] **Ngưỡng "đủ người"**: cần cơ chế hạ ngưỡng theo thời gian / báo trước lịch (tránh khoá vĩnh viễn khi server vắng)
- [ ] **Quân đăng ký rút lại được không**, hay khoá cứng tới khi đấu trường xong?
- [ ] **Mercenary** = một tier trong hệ 7 tier, hay loại quân thuê tạm đánh xong giải tán? *(loại tạm hợp "lính đánh thuê" hơn + đốt tài nguyên; nối với tín dụng Băng: vay → thuê lính → thắng trả nợ / thua vỡ nợ)*

---

## 🧬 CHỦNG TỘC + TRUYỀN THỪA + TRIẾT LÝ GAMBLE (Session 2)

> **Cảnh báo phụ thuộc:** Toàn bộ khối này về bản chất là cơ chế **Combat + Army** ("chọn tướng / item / lõi"). Đã thống nhất **định hướng**, chưa thể đóng chi tiết cho tới khi xương sống Combat thành hình. Đây là lý do Session 2 quyết định **tạm dừng faction để chốt xương sống Combat trước**.

### Kiến trúc 3 tầng (đã thống nhất)

```
SERVER (element)  = khí hậu / môi trường vật lý       (8 loại, chọn 5/cụm)
   └── CHỦNG TỘC  = nền sinh thái + ưu/nhược bẩm sinh  (Nhân / Thú / Ma — cả 3 cùng ở mỗi server)
        └── THẾ LỰC (nghề) = vai trò người chơi         (10 nghề)
```

Ba tầng trả lời 3 câu khác nhau: Server = "khí hậu quanh tôi?"; Chủng tộc = "tôi là ai, ưu/nhược gì?"; Thế lực = "tôi làm nghề gì?".

### Chủng tộc (đã thống nhất định hướng)

| Chủng | Vai trò nghề | Trục đặc biệt | Cân bằng |
|---|---|---|---|
| **Nhân Tộc** | Generalist — làm được gần hết 10 nghề | Linh hoạt, phổ thông | Khá mọi mặt, KHÔNG đỉnh mặt nào |
| **Thú Tộc** | Specialist — ~3-4 nghề | Thể chất / thần thú / hoang dã | Đỉnh một ngách, dở phần còn lại |
| **Ma Tộc** | Specialist — ~3-4 nghề | Hắc ám / cấm thuật / trả giá | Làm được thứ Nhân+Thú bị cấm |

- Mỗi chủng có **pool riêng**; pool gần cạn → **tặng quà dụ** người mới chọn phe thiếu (cơ chế MỀM: hết quà nhưng vẫn vào được, không khoá cứng). Đảm bảo mỗi server luôn đủ 3 chân sinh thái (Tam Quốc).
- Ưu tiên cân bằng khi mâu thuẫn: **cân tộc trước, cân nghề sau** (thiếu tộc = sập sinh thái, nặng hơn thiếu nghề).
- **Cần dọn:** "Dị Tộc / Thú Tộc" trong bảng 10 nghề hiện tại → Thú Tộc kéo lên tầng CHỦNG TỘC; ô nghề đó hoá thành **nghề đặc trưng Thú** (thần thú/hoang dã). Ma Tộc cần **nghề tà đạo mới**.

### Chống "ai cũng chọn nghề độc quyền" — chồng nhiều lớp phanh nhẹ

1. Slot nghề độc quyền **hiếm, khoá cứng** (đầy là đầy) — phanh chính.
2. Độc quyền đi kèm **cái giá** (Ma bị ghét/truy nã hoặc tự ăn mòn) — tự giảm nhu cầu.
3. Độc quyền **phụ thuộc nghề nền** mới sống (vòng phụ thuộc 10 mắt xích) — tham thì tự bỏ đói.
4. **Quà dụ ngược** người chọn nghề nền đang thiếu — lấp đáy sinh thái.

### Truyền Thừa Lão Tổ (thay giao diện "chọn nghề")

- Đầu game: **Lão Tổ Truyền Thừa** hỏi loạt câu tình huống → GAME gán nghề (nâng cấp của quiz 8 câu đã có). Bọc logic phân bổ trong lore "cơ duyên" thay vì thuật toán khô khan.
- **Bản chất = gamble.** Người chơi định hình xu hướng, không cầm chắc kết quả.

### Triết lý GAMBLE / HIGH-VARIANCE (đã thống nhất — quan trọng)

```
Người chơi KHÔNG bỏ cuộc khi mở đầu xấu vì "không biết phía trước có gì"
(TFT: giữ 2/3 lõi xấu vẫn chơi tiếp; ARAM: trận phế vẫn ở lại vì có thể spike lật ngược)
        ↓
Sự MƠ HỒ về tương lai + khả năng cú lật lớn = động cơ giữ chân
```

**Nhưng game 60 ngày KHÁC trận 20 phút — 3 bẫy phải xử:**
- Cú lật của tôi = cú đè kéo dài NHIỀU NGÀY với người khác → phải **lật lại được**, kẻ bị đè phải có "ván sau".
- "Trúng nâng cấp đúng" phải có **lõi kỹ năng**, không thuần hên → người thua thấy "học được", không thấy bị xử ép.
- Variance cao + thời gian dài = phân hoá cực đoan → cần **van xả** (gộp cụm reset, Tam Quốc 2 đánh 1).

**Thuốc giải đã có sẵn trong thiết kế:** Gộp cụm (ngày 31+) = "ván mới" giữa mùa; Tam Quốc 2-đánh-1 dìm kẻ dẫn đầu; đổi ngược Linh Thạch lossy = cơ chế comeback; truyền thừa gamble trong nhóm hợp mệnh = variance có khung.

**Nguyên tắc chốt:** *High-variance chỉ vui khi cú lật xảy ra cho NHIỀU người, nhiều lần — không phải một người, một lần, rồi khoá.* Không giảm gamble — mà đảm bảo MỌI kết quả gamble đều có "phía trước đáng chơi" (dùng Cơ Duyên làm "carousel" lộ dần tương lai của nghề).

### Ánh xạ nền tảng: LoL/TFT (định hướng toàn hệ)

```
CHỌN TƯỚNG  = Nghề / Chủng tộc (truyền thừa gamble)  → 03_faction + 04_character
ITEM        = Quân đội                                → 05_army
CHỌN LÕI    = Combat                                  → Map & Combat
```

Ba hệ là **tam giác khoá nhau** (đổi một đỉnh → hai đỉnh kia lệch), KHÔNG thiết kế rời được. Cú lật high-variance sống ở đỉnh **Combat** → phải chốt xương sống Combat trước khi hoàn thiện faction.

### ❓ Câu hỏi treo — chốt khi làm Combat/Army

- [ ] Gamble giới hạn trong **nhóm hợp mệnh** (đã chọn) — Cơ Duyên phải làm mỗi nghề "có phía trước hấp dẫn".
- [ ] Cú lật ("ngồi lên đầu") **vĩnh viễn hay lật lại được?** *(khuyến nghị: lật lại được)*
- [ ] Đường tới cú lật: **kỹ năng hay may rủi thuần?** *(khuyến nghị: có lõi kỹ năng)*
- [ ] High-variance áp cho **gamble nghề đầu game** (một lần) hay **cơ chế tái diễn suốt mùa?** *(khuyến nghị: tái diễn — giữ chân tốt hơn)*
- [ ] Truyền thừa **bắt buộc mọi người**, hay chỉ một con đường (có cửa thường)?
- [ ] Ma Tộc "trả giá" cụ thể: bị xã hội ghét/truy nã, tự ăn mòn (mất dân/nhân tính), hay cả hai?
