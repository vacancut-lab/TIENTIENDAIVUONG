# Game Overview

## Design DNA

Mảnh Vỡ Đại Thiên là game **PC-first roleplay strategy** trong bối cảnh tiên hiệp. Mobile vẫn tồn tại, nhưng chỉ là bản phụ để quản lý nhanh, nhận báo cáo và đặt lệnh nền.

Trục trải nghiệm chính:

- Người chơi chọn một vai lãnh đạo: Tông Chủ, Hoàng Đế, Bang Chủ, Gia Chủ, Minh Chủ...
- Mục tiêu ban đầu là vực dậy một thế lực suy tàn trong một tiểu thiên thế giới.
- Nơi khởi đầu là **biome 1**: một vùng/cõi thuộc tiểu thiên thế giới của một đại năng đã tọa hóa.
- Sau khi vượt qua biome 1, người chơi tiến vào **biome 2**, nơi các thế lực bắt đầu gặp nhau và roleplay là trọng tâm.

Tham chiếu hệ thống:

- **Heroes 3**: tướng dẫn quân, khám phá map, resource node, skill/build, army tier.
- **Jebus Outcast**: nhịp mở vùng, tranh tài nguyên, timing, map tạo drama và tempo.
- **Call of Dragons**: hành quân, liên minh, chiếm điểm, tranh lãnh thổ trên world map.

Các tham chiếu này không thay thế DNA chính: **roleplay lãnh đạo thế lực**.

---

## Core Fantasy

Người chơi không phải một nhân vật đi farm quái. Người chơi là người đứng đầu hoặc người kế thừa một thế lực đang rơi vào suy tàn.

Ví dụ vai khởi đầu:

| Vai | Fantasy | Trọng tâm |
|---|---|---|
| Tông Chủ / Chưởng Môn | Khôi phục tông môn đổ nát | đệ tử, truyền thừa, linh mạch, pháp hội |
| Hoàng Đế / Quốc Chủ | Vực lại hoàng triều suy vi | dân, luật, quân đội, chư hầu |
| Bang Chủ / Minh Chủ | Dựng lại bang phái/liên minh | nhân mạch, địa bàn, nghĩa khí, đấu đá |
| Gia Chủ / Tộc Trưởng | Cứu gia tộc khỏi diệt vong | huyết mạch, hôn nhân, tài sản, danh vọng |
| Thương Chủ / Các Chủ | Tái lập mạng lưới thương hội | tuyến đường, kho, nợ, bảo kê |

Mỗi vai cần có khác biệt roleplay, quan hệ xã hội, tài nguyên khởi đầu, điểm yếu và con đường vực dậy riêng.

---

## Core Loop

```text
Chọn vai lãnh đạo + thế lực suy tàn
        ->
Tỉnh dậy/tiếp quản trong biome 1 của tiểu thiên thế giới
        ->
Khôi phục căn cơ: tài nguyên, nhân tài, công trình, quân đội, nội bộ
        ->
Khám phá biome 1: fog, node, di tích, quái, cơ duyên, bí mật của đại năng tọa hóa
        ->
Vượt ngưỡng biome 1: đủ lực / đủ danh vọng / mở cổng / phá phong ấn
        ->
Tiến vào biome 2
        ->
Roleplay với thế lực/người chơi khác: ngoại giao, hiệp ước, giao thương, thù hằn
        ->
Tranh lãnh thổ, objective, tài nguyên hiếm, danh tiếng
        ->
Dùng mobile/bế quan để xử lý tài nguyên và lệnh nền khi không ngồi PC
        ->
Quay lại PC để ra quyết định lớn, tham gia roleplay và chiến tranh
```

---

## Biome Progression

### Biome 1 — Căn Cơ Cá Nhân/Thế Lực

Biome 1 là vùng khởi đầu tương đối khép kín, thuộc tiểu thiên thế giới do một đại năng đã tọa hóa để lại. Nó không chỉ là tutorial, mà là chương đầu của roleplay.

Mục tiêu của biome 1:

- giới thiệu thân phận lãnh đạo và vấn đề của thế lực
- cho người chơi khôi phục sản xuất, nhân sự, quân đội, công trình nền
- tạo lựa chọn roleplay đầu tiên: cứu ai, bỏ ai, giữ lời hứa nào, hy sinh tài nguyên nào
- mở bí mật về đại năng tọa hóa và cấu trúc tiểu thiên thế giới
- chuẩn bị người chơi bước vào môi trường xã hội/phức tạp hơn ở biome 2

### Biome 2 — Roleplay Giữa Các Bên

Biome 2 là nơi các thế lực bắt đầu va chạm. Đây là vùng game chuyển từ khôi phục nội bộ sang xã hội sống.

Biome 2 phải có:

- nhiều thế lực/người chơi cùng tồn tại
- tài nguyên không đủ cho tất cả
- vùng trung lập, điểm nghẽn, tuyến giao thương, Linh Mạch, di tích
- luật ngoại giao và reputation đủ mạnh để lời hứa/phản bội có hậu quả
- cơ chế để người chơi roleplay thân phận: tông chủ nói khác hoàng đế, bang chủ hành xử khác thương chủ

---

## PC Và Mobile

| Nền tảng | Vai trò |
|---|---|
| PC | Trải nghiệm chính: map, roleplay, ngoại giao, combat, quản trị sâu. |
| Mobile | Trợ lý phụ: báo cáo, tài nguyên, lệnh điều kiện, phản hồi sự kiện nhỏ. |

Mobile không được buộc game thành idle game. Nếu một hệ thống cần chiều sâu roleplay hoặc quyết định chiến lược lớn, thiết kế ưu tiên PC.

---

## Bế Quan / Resource Operations

Bế Quan là trạng thái người chơi không trực tiếp điều hành từng thao tác nhỏ. Nó giống việc lão tổ bế quan: thế lực vẫn vận hành theo lệnh đã đặt, nhưng không tự sinh ra chiến thắng.

Được phép tự động hóa:

| Nhóm | Ví dụ |
|---|---|
| Sản xuất | thu hoạch tài nguyên, vận hành mỏ, luyện đan/luyện khí nền |
| Hậu cần | chuyển kho, nuôi quân, sửa công trình |
| Lệnh điều kiện | mua khi thiếu, rút khi nguy hiểm, báo cáo khi bị scout |
| Báo cáo | tóm tắt biến động biome/map/social khi người chơi quay lại |

Không được biến thành:

```text
offline lâu -> tự mạnh -> thắng người chơi đang roleplay/đánh map
```

---

## Hệ Thống Thời Gian

**1 ngày thực = 10 năm game**

| Giai Đoạn | Ngày Thực | Năm Game | Nội Dung |
|---|---|---|---|
| Early Game | 1-14 | 0-140 | Biome 1, vực dậy căn cơ thế lực |
| Season War | 15-30 | 140-300 | Biome 2, bắt đầu roleplay/liên minh/tranh chấp |
| Gộp Cụm | 31-45 | 300-450 | Mở vùng lớn hơn, thế lực cũ gặp trật tự mới |
| Endgame | 46-60 | 450-600 | Quyết chiến danh vọng, lãnh thổ, di sản season |

Thời lượng season vẫn có thể giữ 60 ngày, nhưng cần kiểm tra lại sau khi Biome 1 và Biome 2 được thiết kế cụ thể.

---

## Không Có

- Mobile-first idle game
- AFK là core thắng thua
- Người chơi chỉ là một hero đi farm quái
- Combat tách rời roleplay/map kiểu bấm Start rồi nhận thưởng
- VIP 2, VIP 3, bán stat, bán unit exclusive