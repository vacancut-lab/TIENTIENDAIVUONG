# Ban Chuan Ket Thuc Phien Hom Nay

Tai lieu nay ghi lai nhung gi da hoan thanh trong phien hien tai va cac viec con thieu de tiep tuc GDD. Neu file cu lech voi ban nay, uu tien ban nay lam moc tham chieu gan nhat.

---

## 1. Huong Thiet Ke Da Chot

- Game la PC-first roleplay strategy realtime 3D, khong phai SLG / RTS truyen thong.
- Trong tam la dieu quan, lanh dao the luc, xa hoi song, di san nhan vat, kinh te va chinh tri tren map.
- Biome 1 la vung kiet que tai nguyen, dut gay truyen thua; ve sau tro thanh Legacy Vessel / hanh trang di san.
- Biome 2 la xa hoi song, noi nguoi choi tranh di tich, tai nguyen, quyen mua quan, ngoai giao va danh tieng.
- Bo he thong season cu. Thay bang lien server theo pool, moi tran lien server dai 3-5 ngay.
- Bo hoan toan nap tien, VIP, gacha tra tien, tang toc va moi loi the tra tien.

---

## 2. Viec Da Hoan Thanh Trong Phien

### Overview
- Viet lai GDD/00_overview.md theo huong PC-first realtime 3D.
- Them khai niem Biome 1 la Legacy Vessel.
- Them Inter-Server Legacy va Inter-Server Pool.
- Bo thoi gian season cu va nhip 60 ngay.
- Bo logic monetization khoi overview.

### Character System
- Viet lai GDD/04_character_system/character_system.md.
- Chot nhan vat la di san song.
- Chot chuyen server chi giu Du Vang / Tri Thuc / Truyen Thua, khong giu danh hieu server.
- Chot nguoi choi duoc chon 1 tuong bat ky lam tuong chinh khi campaign transfer.
- Them ngu say / be quan / phong ton.
- Them co che roi slot, suy giam Du Vang, Anh Linh Dien, Bond active gioi han.
- Them loyalty / ambition / grievance / debt / stigma cho drama nhan vat.

### Army System
- Viet lai GDD/05_army_system/army_system.md.
- Chot 1 lop tuong la du.
- Chot tier 1-2 la quan nen chung, tier 3-7 mo qua Di Chi Truyen Thua.
- Chot campaign transfer giong Heroes 3: 1 tuong + it quan + hanh trang di san gioi han.
- Them node quan dac biet song song voi Di Chi Truyen Thua.
- Them vai tro combat realtime 3D: giu tuyen, escort, siege, objective, harass, boss fight.

### Resource System
- Viet lai GDD/06_resource_system/resource_system.md.
- Chot cau truc 3 tang: tai nguyen co ban, Linh Thach 3 menh gia, tai nguyen dac thu server.
- Giu doi xuoi mien phi, doi nguoc lossy.
- Them tran kinh te server va tran suc chua.
- Them nguyen tac chong rua tien / chong economy snowball.
- Gan tai nguyen voi phuc dung di tich, quan luc, giao thuong, bao ke va cuop boc.

### Social System
- Viet lai GDD/07_social_system/social_system.md.
- Chot reputation theo goc nhin, khong co diem dao duc tuyet doi.
- Giu phan boi, cuop boc, noi gian, false flag, mua chuoc, am sat NPC, tin don.
- False flag mo som va la gameplay hop le.
- Phap Gia la cong cu xa hoi / hop dong, khong phai camera toan tri.
- Them lien he lien server va Tong Thien Nhan.

### Combo System
- Viet lai GDD/08_combo_system/combo_system.md.
- Gan combo voi map 3D realtime, dia hinh, vision, timing, siege, boss fight.
- Them combo xa hoi / kinh te nhu Cartel, Bao Ke Tuyen Duong, False Flag Chain.
- Giu buff nguoi phat hien +8%, nguoi hoc lai +3%.
- Them counter combo va Thu Vien Server.

### Monetization
- Viet lai GDD/09_monetization.md thanh cam ket khong nap tien.
- Xoa huong goi 10 dong / ngay, gacha tra tien, tang toc, slot mua bang tien.

### Map System
- Viet lai GDD/11_map_system.md.
- Chot map 3D realtime PC-first.
- Chot moi server la mot vi dien co 5 vung dat chinh.
- Them Biome 1 Legacy Vessel, Biome 2 xa hoi song.
- Them Di Chi Truyen Thua, node quan dac biet, Inter-Server Map Pool, fog / dau vet / tinh bao.

---

## 3. Cac Viec Con Thieu / Can Chot

### Chuyen Server / Legacy
- Cong thuc tran suc manh khi campaign transfer.
- So quan toi da duoc mang theo khi sang server moi.
- Cac loai tai san / tri thuc / trang bi duoc mang theo va ty le hao hut.
- Cach xu ly quan tier cao khi server moi chua mo tier tuong ung.

### Character
- Cong thuc suy giam Du Vang theo thoi gian.
- Dieu kien goi tuong tu Biome 1 qua Anh Linh Dien.
- So tuong active toi da tren mot server.
- Chi phi doi Active Signature Skill.
- Co che chet / bi bat / di vat can chi tiet hon.

### Army
- Danh sach node quan dac biet mau cho Biome 2.
- Cong thuc gioi han quan luc trong transfer.
- Cach quan tier 7 ton tai ma khong pha server moi.
- Prototype combat realtime 3D cho boss, siege va objective.

### Resource
- Ty le mat khi doi nguoc Linh Thach.
- Moi server co bao nhieu tai nguyen dac thu.
- Tai nguyen dac thu reset theo vong nao.
- Tran kinh te server tinh bang power, tai san, so nguoi choi hay tong hop.

### Social
- Phi Phap Gia cho tung loai hop dong.
- Dieu tra false flag sai 30% tao hau qua gi.
- Tin don bi trace ve nguon sau bao lau va bang cach nao.
- Reputation theo goc nhin hien cong khai hay chi qua bao cao.

### Combo
- Co combo 4 chieu endgame khong.
- Dieu kien mo muc Cong Thuc trong Thu Vien Server.
- Combo xa hoi co duoc Tong Thien Nhan ghi nhan nhu combat khong.
- Buff +8% / +3% ap dung cho combo xa hoi hay chi combat.

### Map
- 5 vung dat server co can bo ten chuan khong.
- Fog luu theo nguoi choi, lien minh hay the luc.
- Node tai nguyen hoi theo chu ky, doi trang thai hay can phuc dung.
- Nguoi choi co duoc xay duong / cau / cong de thay doi map khong.
- Map lien server la chien truong rieng hay mo truc tiep tren bien gioi server.

### Faction / Server Cu
- Can dong bo GDD/03_faction_system/README.md voi huong moi.
- Can xu ly thu muc GDD/02_server_system/*: 8 server cu nen chuyen thanh vung dat / dai luc / identity map, khong con la server tach biet.
- Can cap nhat DISCUSSION/pending_decisions.md de bo cac cau hoi da chot.

---

## 4. Uu Tien Phien Sau
1. Dong bo faction system voi 5 than phan lanh dao + 8 nhom nganh moi.
2. Chuyen 8 server element cu thanh vung dat / dai luc / phap tac trong mot vi dien.
3. Thiet ke cong thuc tran suc manh transfer.
4. Prototype combat realtime 3D cho boss Biome 1 va objective Biome 2.
5. Cap nhat danh sach pending decisions.
