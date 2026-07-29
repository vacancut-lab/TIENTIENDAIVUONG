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
- [ ] **"Thứ không thể từ chối" là gì?** *(khuyến nghị: tài nguyên hiếm + cơ hội/quyền, TRÁNH sức mạnh vĩnh viễn. "Không từ chối" = sức hút, không phải cưỡng bức — giữ AFK Core)*
- [ ] **Ngưỡng "đủ người"**: cần cơ chế hạ ngưỡng theo thời gian / báo trước lịch (tránh khoá vĩnh viễn khi server vắng)
- [ ] **Quân đăng ký rút lại được không**, hay khoá cứng tới khi đấu trường xong?
- [ ] **Mercenary** = một tier trong hệ 7 tier, hay loại quân thuê tạm đánh xong giải tán? *(loại tạm hợp "lính đánh thuê" hơn + đốt tài nguyên; nối với tín dụng Băng: vay → thuê lính → thắng trả nợ / thua vỡ nợ)*
