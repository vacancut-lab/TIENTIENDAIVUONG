# Mảnh Vỡ Đại Thiên
> Mobile Strategy Game · AFK · Xianxia Setting  
> BVQ Studio · 2026

---

## Vision

**Mảnh Vỡ Đại Thiên** là mobile game chiến lược AFK phong cách tiên hiệp, nơi mỗi người chơi là chủ một thế lực — tông môn, thế gia, hoàng triều, thương hội... — trên một tiểu đại lục (mảnh vỡ của đại thiên thế giới).

Người chơi ra quyết định chiến lược. Thuộc hạ NPC tự thực thi. Thế lực tồn tại và hoạt động kể cả khi offline.

---

## Triết Lý Thiết Kế

| Nguyên Tắc | Mô Tả |
|---|---|
| **Anti-P2W** | Chỉ 1 gói nạp duy nhất — 10 đồng/ngày. Không bán sức mạnh. |
| **Scarcity-Driven** | Tài nguyên có hạn ép người chơi chuyên môn hóa và phụ thuộc lẫn nhau. |
| **Emergent Gameplay** | Hệ thống tự tạo kết quả mà designer không lường trước. |
| **AFK Core** | Online 10-15 phút/ngày là đủ — nhưng luôn có lý do muốn online. |
| **Every Faction Matters** | Không thế lực nào là "support bị động" — mỗi bên có thứ không ai thay thế được. |
| **Roleplay First** | Mỗi nước đi phải suy nghĩ — mọi quyết định có hệ quả thật sự. |

---

## Cấu Trúc Tài Liệu

```
GDD/
├── 00_overview.md              # Game loop, season structure
├── 01_season_structure.md      # Timeline 60 ngày, phase
├── 02_server_system/           # 8 element server
├── 03_faction_system/          # 10 thế lực
├── 04_character_system/        # Nhân vật, role, skill
├── 05_army_system/             # 7 tier quân, cấp 1 vs cấp 2
├── 06_resource_system/         # Tài nguyên, Linh Mạch
├── 07_social_system/           # Drama, reputation
├── 08_combo_system/            # Emergent combo
└── 09_monetization.md          # Anti-P2W

DISCUSSION/
├── pending_decisions.md        # Câu hỏi chưa chốt
└── ideas_backlog.md            # Ý tưởng chưa thiết kế
```

---

## Trạng Thái Thiết Kế

| Section | Trạng Thái |
|---|---|
| Season Structure | ✅ Hoàn chỉnh |
| Server System (Hoả, Kim, Mộc, Thuỷ, Thổ, Lôi) | ✅ Hoàn chỉnh |
| Server System (Phong, Băng) | ✅ Framework hoàn chỉnh |
| Faction System | ✅ Framework hoàn chỉnh |
| Character System | ✅ Framework hoàn chỉnh |
| Army System | ✅ Framework hoàn chỉnh |
| Resource System | ✅ Framework hoàn chỉnh |
| Social System | ✅ Hoàn chỉnh |
| Combo System | 🚧 Framework, chưa đầy đủ |
| Monetization | ✅ Hoàn chỉnh |
| Map & Combat | ❌ Chưa thiết kế |

---

## Đóng Góp

Mỗi file có section `## ❓ Câu Hỏi Mở` — team thảo luận tại đây trước khi chốt.

Dùng GitHub Issues để track từng quyết định thiết kế lớn.
