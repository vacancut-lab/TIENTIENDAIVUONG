# Mảnh Vỡ Đại Thiên
> PC-first Roleplay Strategy · Xianxia · World/Faction Simulation
> Có bản mobile phụ, nhưng thiết kế chính ưu tiên trải nghiệm PC và roleplay dài hơi.

---

## Cập Nhật Thiết Kế

Game này **mạnh về roleplay và PC-first**. Mobile vẫn có, nhưng không phải nền tảng định hình toàn bộ thiết kế. Mobile nên phục vụ thao tác nhanh, quản lý tài nguyên, đọc báo cáo, đặt lệnh và xử lý việc nhỏ khi người chơi không ngồi PC.

Người chơi khởi đầu bằng việc chọn một thân phận lãnh đạo để **vực dậy một thế lực suy tàn**:

- Tông Chủ / Chưởng Môn
- Hoàng Đế / Quốc Chủ
- Bang Chủ / Minh Chủ
- Gia Chủ / Tộc Trưởng
- Các vai lãnh đạo khác tùy thế lực

Tham chiếu cảm giác hệ thống vẫn là:

- **Heroes 3**: hero dẫn quân, khám phá map, resource node, skill, army tier, quyết định đường đi.
- **Jebus Outcast**: nhịp mở vùng, tranh tài nguyên, timing và map tạo drama.
- **Call of Dragons**: hành quân, liên minh, chiếm điểm, chiến tranh lãnh thổ trên world map.

Nhưng các tham chiếu này chỉ là công cụ. DNA chính là **roleplay lãnh đạo thế lực trong thế giới tiên hiệp sống**.

---

## Vision

**Mảnh Vỡ Đại Thiên** là game chiến lược roleplay tiên hiệp, nơi người chơi không bắt đầu như một cá nhân vô danh đi farm quái, mà là người kế thừa hoặc người đứng đầu một thế lực đang suy yếu trong một **Tiểu Thiên Thế Giới**.

Nơi khởi đầu là một **biome** thuộc tiểu thiên thế giới do một đại năng đã tọa hóa để lại. Người chơi phải khôi phục căn cơ, gom tài nguyên, thu phục nhân tài, ổn định nội bộ, xây quân và vượt qua các thử thách của biome đầu tiên.

Sau khi vượt qua biome 1, người chơi tiến tới **biome 2**, nơi nhiều thế lực/người chơi bắt đầu gặp nhau và roleplay trở thành trọng tâm: ngoại giao, liên minh, thù hằn, giao thương, phản bội, phân vai, chiến tranh và tranh quyền kiểm soát vùng.

---

## Triết Lý Thiết Kế

| Nguyên Tắc | Mô Tả |
|---|---|
| **Roleplay First** | Mỗi người chơi là một vai lãnh đạo có thân phận, mục tiêu, danh tiếng và hệ quả xã hội. |
| **PC-First Depth** | Giao diện và hệ thống ưu tiên chiều sâu chiến lược/roleplay trên PC; mobile là lớp phụ trợ. |
| **Faction Revival** | Core fantasy là vực dậy một tông môn/quốc gia/bang hội/gia tộc suy tàn. |
| **Biome Progression** | Game mở theo từng biome: biome 1 là căn cơ và học hệ thống; biome 2 mở roleplay giữa các bên. |
| **Map-Driven Strategy** | Bản đồ, tài nguyên, đường đi, fog, objective và lãnh thổ tạo quyết định chiến lược. |
| **Scarcity-Driven** | Tài nguyên hữu hạn tạo cạnh tranh, giao thương, liên minh và phản bội. |
| **Bế Quan / Mobile Support** | Offline/mobile hỗ trợ tài nguyên, báo cáo, lệnh điều kiện; không thay thế quyết định roleplay/map. |
| **Anti-P2W** | Không bán sức mạnh trực tiếp, không VIP bậc thang, không unit/stat độc quyền trả tiền. |

---

## Core Loop Mới

```text
Chọn vai lãnh đạo: Tông Chủ / Hoàng Đế / Bang Chủ / Gia Chủ / ...
        ->
Nhận thế lực suy tàn trong biome khởi đầu
        ->
Khôi phục căn cơ: tài nguyên, nhân tài, công trình, quân đội, nội bộ
        ->
Khám phá biome, mở fog, xử lý PvE/event/cơ duyên
        ->
Vượt ngưỡng biome 1
        ->
Tiến vào biome 2
        ->
Roleplay với các thế lực khác: ngoại giao, giao thương, liên minh, thù địch
        ->
Tranh lãnh thổ, objective, danh tiếng và quyền kiểm soát
        ->
Dùng bế quan/mobile để xử lý tài nguyên và lệnh nền
        ->
Quay lại PC để ra quyết định lớn và roleplay
```

---

## Nền Tảng Và Thiết Bị

| Nền tảng | Vai trò |
|---|---|
| **PC** | Trải nghiệm chính: roleplay, map, combat, ngoại giao, quản trị thế lực sâu. |
| **Mobile** | Trải nghiệm phụ: nhận báo cáo, đặt lệnh điều kiện, quản tài nguyên, phản hồi sự kiện nhỏ. |

Mobile không được kéo thiết kế thành idle/mobile-first. Nếu phải chọn giữa chiều sâu roleplay PC và tiện lợi mobile, ưu tiên PC.

---

## Cấu Trúc Tài Liệu

```text
GDD/
├── 00_overview.md              # Vision, roleplay, biome, bế quan
├── 02_server_system/           # 8 element server + cụm server
├── 03_faction_system/          # 5 role khởi đầu + ngành nghề Biome 2
├── 04_character_system/        # Nhân vật, tướng, role, skill
├── 05_army_system/             # Quân đội, tier quân, Di Chỉ Truyền Thừa
├── 06_resource_system/         # Tài nguyên, Linh Mạch, tiền tệ, tranh đoạt
├── 07_social_system/           # Roleplay, drama, reputation, social
├── 08_combo_system/            # Combo emergent, chờ combat/map
├── 09_monetization.md          # Anti-P2W
└── 11_map_system.md            # Map, node, movement, resource point

DISCUSSION/
├── pending_decisions.md        # Câu hỏi chưa chốt
└── ideas_backlog.md            # Ý tưởng chưa thiết kế
```

---

## Trạng Thái Thiết Kế

| Section | Trạng Thái |
|---|---|
| Roleplay PC-first DNA | ✅ Đã xác định lại |
| Mobile/Bế Quan Support | ✅ Chỉ là lớp phụ trợ |
| Biome 1 -> Biome 2 Progression | 🚧 Cần thiết kế chi tiết |
| Faction Revival Fantasy | 🚧 Cần viết thành hệ thống riêng |
| Server/Faction/Character/Army/Resource | ✅ Có framework cũ để kế thừa |
| Map System | ❌ Ưu tiên cao nhất |
| Combat System | ❌ Ưu tiên cao |
| Social/Roleplay System | 🚧 Cần nâng cấp mạnh theo biome 2 |

---

## Thứ Tự Thiết Kế Tiếp Theo

1. **Faction Revival & Starting Identity** — cách mỗi thế lực khởi đầu suy tàn, mục tiêu vực dậy, khác biệt vai lãnh đạo.
2. **Biome 1** — vùng khởi đầu của tiểu thiên thế giới, PvE/event/cơ duyên/tutorial không lộ liễu.
3. **Biome 2** — vùng gặp người chơi/thế lực khác, luật roleplay, ngoại giao, conflict, alliance.
4. **Map System** — layout Heroes 3/Jebus-style nhưng phục vụ roleplay và lãnh thổ.
5. **Combat & Army** — tướng/quân/skill/combat gắn với map và thân phận thế lực.
6. **Social & Reputation** — danh tiếng, hiệp ước, phản bội, lịch sử server, ký ức roleplay.

---

## Đóng Góp

Mọi phần mới phải giữ đúng nguyên tắc: roleplay-first, PC-first, mobile chỉ hỗ trợ, người chơi là lãnh đạo vực dậy thế lực, biome mở dần tương tác xã hội, tài nguyên khan hiếm, anti-P2W.
