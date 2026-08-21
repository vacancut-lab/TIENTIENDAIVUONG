# Map System

## Vai Tro

Map la san khau chinh cua game. Roleplay, tai nguyen, chien tranh, ngoai giao va co duyen deu phai co vi tri tren map.

Tham chieu cam giac:

- Heroes 3: exploration, fog, resource piles/nodes, hero pathing, guards, objectives.
- Jebus Outcast: tempo mo map, tranh mo, duong thong vung, reward lon di kem rui ro.
- Call of Dragons: hanh quan thoi gian thuc, alliance, rally, chiem diem, tranh lanh tho.

---

## Nguyen Tac Map-First

| Nguyen Tac | Y Nghia |
|---|---|
| Moi thu quan trong co vi tri | Tai nguyen, di tich, NPC, hiep uoc, chien tranh deu gan voi diem/vung. |
| Duong di la quyet dinh | Di dau truoc, mo duong nao, bo node nao phai tao he qua. |
| Fog tao chinh tri | Khong biet het map -> can tinh bao, giao dich thong tin, lua dao. |
| Choke tao drama | Diem nghen buoc ngoai giao, phuc kich, bao ke, thu phi. |
| Resource guard tao tempo | Node manh can quan/tuong du luc hoac hop tac de mo. |
| Lanh tho la cau chuyen | Mat mo, giu cong, cuu vien, phan boi phai duoc nho trong lich su server. |

---

## Cau Truc Map Theo Biome

```text
Tieu Thien The Gioi
|-- Biome 1: vung can co / khoi dau
|-- Biome 2: vung roleplay xa hoi
|-- Biome 3: vung chien tranh lon / phap tac dac biet
`-- Core/Endgame: di san dai nang toa hoa
```

### Biome 1

- It nguoi hoac nhom nho.
- Tap trung khoi phuc the luc.
- Resource node nen, guard vua phai.
- Duong mo co tinh lua chon nhung khong qua trung phat.
- Cam che/vach gioi han tao muc tieu mo biome 2.

### Biome 2

- Shared map nhieu nguoi choi/the luc.
- Nhieu resource node canh tranh.
- Choke point, vung trung lap, tuyen giao thuong.
- Diem cong cong de ky hiep uoc, giao dich, phuc kich, chiem giu.
- Tu day roleplay/social tro thanh he thong chinh.

---

## Layer Map

| Layer | Chuc Nang |
|---|---|
| Dia hinh | rung, nui, song, hoang mac, bang nguyen, loi vuc... |
| Tai nguyen | mo, linh thao, linh mach, kho co, phe tich |
| Di chuyen | duong chinh, duong tat, cong dich chuyen, choke |
| The luc | can cu nguoi choi, NPC faction, vung anh huong |
| Tinh bao | fog, dau vet hanh quan, tin don, scout report |
| Co duyen | event, di tich, boss, lua chon roleplay |
| Luat biome | phap tac rieng cua vung, buff/debuff, cam che |

---

## Tile / Hex / Node

Chua chot hien thi cuoi cung la hex hay node graph. Dinh huong tam thoi:

- PC view uu tien doc chien thuat: vung, duong, node, anh huong lanh tho.
- Mobile view uu tien thao tac nhanh: danh sach node, bao cao, lenh di chuyen don gian.
- Co the dung node graph tren nen biome thay vi hex day dac neu roleplay/map readability tot hon.

Quyet dinh can chot sau khi prototype map.

---

## Resource Node

| Loai Node | Vai Tro | Rui Ro |
|---|---|---|
| Mo thuong | tai nguyen nen | bi cuop/thu phi |
| Linh Mach Ha | nang can co biome 1 | guard/PvE |
| Linh Mach Trung | tranh chap biome 2 | PvP/ngoai giao |
| Phe tich | lore + co duyen | lua chon roleplay, boss |
| Cho trung lap | giao dich | lua dao, phuc kich, thue |
| Cong/cam che | mo biome moi | can tai nguyen, hiep luc hoac nhiem vu |

---

## Movement & March

Hanh quan can lay cam giac Call of Dragons nhung khong bien thanh click war mobile.

Nguyen tac:

- di chuyen co thoi gian,
- scout co gia tri,
- duong tat di kem rui ro,
- doi quan xa nha can hau can,
- co the bi phuc kich/chan duong,
- rally/cuu vien tao drama xa hoi.

---

## Cau Hoi Mo

- [ ] Map dung hex, square, hay node graph?
- [ ] Biome 1 shared hay rieng?
- [ ] Fog of war luu theo nguoi choi, lien minh, hay the luc?
- [ ] Resource node co can vinh vien, hoi theo chu ky, hay doi trang thai?
- [ ] Co cho nguoi choi xay duong/cong de thay doi map khong?
- [ ] Hanh quan realtime hay theo tick?
