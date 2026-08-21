# Game Overview

## Design DNA

Mảnh Vỡ Đại Thiên là game **PC-first roleplay strategy** trong bối cảnh tiên hiệp. Mobile vẫn tồn tại, nhưng chỉ là bản phụ để quản lý nhanh, nhận báo cáo và đặt lệnh nền.

Trục trải nghiệm chính:

- Người chơi chọn một vai lãnh đạo: Tông Chủ, Hoàng Đế, Bang Chủ, Gia Chủ, Minh Chủ...
- Mục tiêu ban đầu là vực dậy một thế lực suy tàn trong một tiểu thiên thế giới.
- Nơi khởi đầu là **biome 1**: một tiểu thiên thế giới riêng cho từng người chơi, được hình thành từ cơ thể của một đại năng cổ xưa để mở đầu câu chuyện.
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
Khám phá biome 1: fog, node, di chỉ, quái, cơ duyên, bí mật của đại năng tọa hóa
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

### Biome 1 — Tiểu Thiên Thế Giới Riêng

Biome 1 là tiểu thiên thế giới riêng của từng người chơi, hình thành từ cơ thể một đại năng cổ xưa đã tọa hóa. Nó không chỉ là tutorial, mà là chương mở đầu của câu chuyện và thân phận lãnh đạo.

Mục tiêu của biome 1:

- giới thiệu thân phận lãnh đạo và vấn đề của thế lực
- cho người chơi khôi phục sản xuất, nhân sự, quân đội, công trình nền
- tạo lựa chọn roleplay đầu tiên: cứu ai, bỏ ai, giữ lời hứa nào, hy sinh tài nguyên nào
- mở bí mật về đại năng cổ xưa và cấu trúc tiểu thiên thế giới riêng của người chơi
- chỉ cung cấp tài nguyên cấp thấp để xây quân tier 1-2, không cho nhảy thẳng lên chiến lực cao
- có một đàn quái vật chặn cổng đủ mạnh để ép người chơi phải học cách chơi, nhưng vẫn có thể vượt sớm nếu hiểu hệ thống nhanh
- mục tiêu dài hạn là đẩy người chơi ra đại thế giới để cứu một biome đang cạn tài nguyên
- có AI Ngón Tay Vàng làm trợ lý, và nó kết nối với Tổng Thiên Nhãn để hỗ trợ các role cần tương tác cao như mật thám, drama, theo dõi biến động xã hội
- vật liệu nền ở biome 1 gồm gỗ, đá, lương thực và linh thạch cấp thấp
- boss phụ có thể tồn tại để tạo reward, lore, hoặc đường tắt, nhưng không bắt buộc
- chuẩn bị người chơi bước vào môi trường xã hội/phức tạp hơn ở biome 2
- quân tier 1-2 là quân nền giống nhau do truyền thừa đứt gãy; tier 3-7 chỉ mở ở biome 2 thông qua Di Chỉ Truyền Thừa
- mỗi di chỉ truyền thừa ban đầu là một địa điểm; người chơi có thể chiếm nhiều địa điểm, nhưng không có nghĩa đủ năng lực xây dựng hoặc phục dựng toàn bộ hệ thống của tất cả di chỉ đó

### Biome 2 — Roleplay Giữa Các Bên

Biome 2 là nơi các thế lực bắt đầu va chạm. Đây là vùng game chuyển từ khôi phục nội bộ sang xã hội sống.

Biome 2 phải có:

- nhiều thế lực/người chơi cùng tồn tại
- tài nguyên không đủ cho tất cả
- vùng trung lập, điểm nghẽn, tuyến giao thương, Linh Mạch, di chỉ
- hàng loạt Di Chỉ Truyền Thừa kiểu Heroes 3, quyết định quyền mua và phục dựng quân tier cao
- luật ngoại giao và reputation đủ mạnh để lời hứa/phản bội có hậu quả
- cơ chế để người chơi roleplay thân phận: tông chủ nói khác hoàng đế, bang chủ hành xử khác thương chủ
- các role ở Biome 2 phải là vai sống động, liên kết chặt với nhau; mỗi ngành là một role quan trọng, có cây kỹ năng riêng và càng phát triển càng mạnh nhưng cũng càng phụ thuộc vào ngành khác
- có thể nghiên cứu song song nhiều ngành, nhưng sẽ tốn rất nhiều thời gian và chi phí
- ví dụ Luyện Chế hỗ trợ các ngành cần vũ khí; kỹ sư cần bản vẽ, công nhân và nguyên liệu để thi công; không có ngành nào là phụ hoàn toàn
- ví dụ Đan Dược có thể tự túc đan dược, nhưng yếu tranh đấu; vẫn phải nhờ phe khác hỗ trợ nhiệm vụ truyền thừa, mua vật phẩm phục dựng di chỉ, hoặc đánh thuê khi cần
- người chơi có thể sống một mình nếu muốn, nhưng để tạo được hệ sinh thái mạnh thì vẫn phải phụ thuộc người khác theo kiểu trao đổi hai chiều
- tài nguyên không tự sinh ra là chính; phần lớn tăng trưởng đến từ tranh đoạt, chiếm giữ, giao thương, bảo kê và hợp tác
- nguồn tài nguyên càng hiếm càng dễ kéo theo xung đột xã hội, drama, phản bội và hiệp ước

### Khung Ngành Nghề Biome 2

Biome 2 có thể chia thành 8 nhóm ngành chính. Mỗi nhóm là một role sống động, có cây kỹ năng riêng, có ngành phụ trợ và có vị thế trong hệ sinh thái.

| Nhóm | Vai trò chính | Phụ thuộc chính | Ví dụ nghề |
|---|---|---|---|
| Chiến Đấu | đánh nhau, hộ tống, chiếm điểm | vũ khí, hậu cần, y tế | Kiếm Tu, Thể Tu |
| Công Trình | xây thành, thủ thành, phục dựng di chỉ | vật liệu, nhân lực, phù lục | Trận Pháp, Kỹ Sư |
| Luyện Chế | làm trang bị, bẫy, công cụ | quặng, linh thảo, bản vẽ | Luyện Khí, Phù Lục |
| Đan Dược | hồi phục, đột phá, nuôi quân | linh thảo, bảo vệ, thương mại | Đan Sư, Dược Sư |
| Thương Mại | vận tải, mua bán, cung ứng | an ninh, pháp lý, sản xuất | Thương Hội, Hậu Cần |
| Tình Báo | scout, ngầm, phá hoại, drama | tiền, luật, quan hệ, ngụy trang | Mật Thám, Ám Tử |
| Ngoại Giao | hiệp ước, giải quyết tranh chấp | uy tín, pháp lý, quà tặng | Pháp Gia, Ngoại Giao Quan |
| Hỗ Trợ Đặc Thù | nuôi hệ sinh thái, vùng đặc biệt | đất, dân, thủ lĩnh, bảo hộ | Ngự Thú, Linh Mộc |

### Tinh Than RP Cua Nghe Nghiep

- Mỗi ngành là một vai có ích thật sự, không phải nghề phụ.
- Mỗi ngành càng mạnh càng phụ thuộc hệ sinh thái xung quanh.
- Người chơi có thể sống một mình, nhưng muốn mạnh thì phải bước vào mạng trao đổi giữa các ngành.
- Càng đi sâu, càng bị khóa bởi tài nguyên, quan hệ, hậu cần và kỹ năng nghề khác.

### Vi Du Role

- Đan Dược có thể tự túc đan dược và nuôi sống thế lực nhỏ.
- Nhưng nếu yếu tranh đấu, muốn leo tier cao thì phải thuê phe chiến đấu làm nhiệm vụ truyền thừa.
- Muốn mua vật phẩm phục dựng di chỉ, Đan Dược cần thương hội, pháp lý hoặc thế lực bảo kê.
- Luyện Chế cần quặng, bản vẽ, thợ và người vận chuyển.
- Trận pháp cần vật liệu, nhân lực, phù lục và thời gian.
- Mật thám sống bằng thông tin khan hiếm, nên phải bám vào hậu cần, pháp lý và drama.

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
