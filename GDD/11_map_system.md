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

- La tieu thien the gioi rieng cua tung nguoi choi.
- Duoc hinh thanh tu co the mot dai nang co xua, tao cam giac biem kich va di san cuoi cung.
- Chi co tai nguyen cap thap de xay dung quan doi tier 1-2.
- Tap trung khoi phuc the luc ban dau, khong co tham vong mo vang tuan dau.
- Co mot dan quai vat chan cong du manh de lam kho player, giong quái chan cong trong Jebus Outcast.
- Player nao nam ro he thong co the out som; biome khong giu nguoi choi lau hon can thiet.
- Toan bo biome 1 chi chua tai nguyen cap 1 phuc vu xay dung va lam quen game.
- Bai toan thiet ke la ep nguoi choi som ro biome nay de sang dai the gioi, noi co the cuu biome dang can tai nguyen.
- AI Ngon Tay Vang co the phoi hop voi Tong Thien Nhan de tao bao cao, goi y, canh bao drama va ho tro cac role co tinh tuong tac cao.
- Tai nguyen cap 1 gom go, da, luong thuc va linh thach cap thap.
- Resource node nen, guard vua phai.
- Duong mo co tinh lua chon nhung khong qua trung phat.
- Cam che/vach gioi han tao muc tieu mo biome 2.

### Biome 2

- Shared map nhieu nguoi choi/the luc.
- Nhieu resource node canh tranh.
- Choke point, vung trung lap, tuyen giao thuong.
- Diem cong cong de ky hiep uoc, giao dich, phuc kich, chiem giu.
- Di chi truyen thua la cac dia diem co the chiem; chiem nhieu dia diem khong co nghia la du nang luc phuc dung toan bo.
- Moi di chi la mot node co vai tro rieng, co the keo theo chuoi phu tro va xung dot lien hoan.
- Di chi nao cung co the mat quyen mua/ho tro neu bi cuop, tao drama giong Heroes 3.
- Tai nguyen Biome 2 khong chi tu sinh. Chung den tu mo, di chi, thuong doi, bao ke, cuop boc, tranh chap va hop tac.
- Resource cung cap cho moi nganh deu co hai nguon: tu sinh va tranh doat.
- Tu day roleplay/social tro thanh he thong chinh.

### Role Dong Trong Biome 2

Biome 2 khong chay theo class co dinh. Moi role phai la mot nghe song, co quan he mau thit voi cac nghe khac.

| Role | Chuc nang | Phu thuoc | Co the ho tro |
|---|---|---|---|
| Kinh Doanh / Thuong Hoi | tai chinh, van tai, roi kinh te | bao ve, san xuat, phap ly | tat ca cac nganh |
| Khí Dao | vu khi, phap bao, trang bi | kim loai, ban ve, cong nhan | kiem, thuong, tran, the |
| Phù Lục | phong an, buff, ha che | vat lieu, tri thuc, nguoi ve | tran phap, ngoai giao, bao ve |
| Trận Pháp | quan tran, thanh tri, phuc thu | phu luc, van tai, nhan luc | hoang trieu, the gia |
| Mật Thám | thong tin, cai nguoi, false flag | tien bac, phap ly, tinh bao | moi role khac |

Người chơi co the theo song song nhieu nganh, nhung moi nganh deu co cay ky nang rieng va yeu cau dien tich / thoi gian / nhan luc.

### Vi Du: Dan Dao Trong Biome 2

Dan dao co the tu tuc ve dan duoc, hoi phuc va dot pha, nhung yeu trong tranh dau.

- Dan Dao co the dong goi san pham, ban dan, giu nguon song cho the luc.
- Khi muon noi len tier cao, Dan Dao can phe khac cung cap vat pham phuc dung di chi, nguyen lieu hiem, bao ve luc luong va dich vu chien dau.
- Dan Dao co the mot minh song duoc, nhung muon tao he sinh thai manh phai ket noi voi Kiem, Tran, Phu, Thuong, Mat Tham va Hoang Trieu.
- Neu muon khai thac mot thanh tri truyen thua, Dan Dao co the phai thue phe chien dau danh giam, phe thuong mai cung cap huu canh, phe phap ly bao chong phan boi.

### Nguon Tai Nguyen Biome 2

| Nguon | Cach co | Drama |
|---|---|---|
| Tu sinh | mo, ruong, linh mach, event | on dinh, nhung khong du cho cuoc dua lon |
| Tranh doat | cuop mo, chiem di chi, chan duong | nhiet, xung dot, can lien minh |
| Thuong mai | mua ban, hop dong, bao ve | tao giao dich va loi ich qua lai |
| Di chi | phuc dung, mo khoa tier cao | tranh quyen, tranh co so, tranh nhan su |
| Quan he | vuot qua ngoai giao, danh tieng | tao le thuoc va chup mu nao |

### Dau Ra Cua Tinh Trang Thieu Thon

- Neu chi tu sinh, game se thanh idle va mat drama.
- Neu chi tranh doat, game se thanh chaos va khong ben vung.
- Nen phai co ca hai: noi song thap, tranh doat cao, va thuong mai de boi tron xung dot.

### Cay Ky Nang Nganh Nghiep

Moi nganh co cay ky nang rieng. Phat trien cang cao thi cang manh, nhung cung cang phu thuoc vao mot mang luoi ho tro xung quanh.

| Nganh | Cay ky nang | Phu thuoc |
|---|---|---|
| Dan Dao | hoi phuc, dot pha, tan duoc, che tao dan | linh thao, bao ve, giao dich |
| Kiem Dao | don dau, xuyen pha, chem tuong | vo khi, trang bi, hau can |
| Tran Phap | thu thanh, khong che khu vuc, van hanh doan the | nhan luc, phu luc, vat lieu |
| Phu Luc | phong an, debuff, ngoai giao canh bao | vat lieu, ky su, bao ve |
| Thuong Hoi | van tai, nhu cau thi truong, tai chinh | an ninh, phap ly, san xuat |

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

- **De xuat mac dinh:** node graph tren nen biome ve tay/procedural, co duong noi ro nhu Jebus template.
- PC view uu tien doc chien thuat: vung, duong, node, anh huong lanh tho.
- Mobile view uu tien thao tac nhanh: danh sach node, bao cao, lenh di chuyen don gian.
- Hex/square chi dung lam lop tinh toan an neu can do khoang cach, khong bat buoc hien day dac.

Quyet dinh can chot sau khi prototype map.

---

## Biome 1 Layout De Xuat

Biome 1 la "man khoi dau" cua mot the luc, nhung duoc dat trong khung tien truyen rieng cua tung nguoi choi. Map can tao cam giac co do cua dai nang toa hoa dang mo lai tung lop.

~~~text
Can Cu Suy Tan
   |-- vung san xuat nen
   |-- vung nhan su / cuu dan / cuu de tu
   |-- vung di tich nho
   |-- choke bi phong an
   '-- cong sang Biome 2
~~~

| Vung | Vai Tro | Drama Can Tao |
|---|---|---|
| Can cu suy tan | noi nguoi choi quan tri the luc | thieu nhan luc, kho hong, noi bo chia phe |
| Vong tai nguyen nen | mo, ruong, linh thao cap thap | chon node nao truoc anh huong tempo |
| Di tich nho | lore dai nang + co duyen | lay reward nhanh hay giu loi hua voi NPC |
| Vung nguy hiem | guard, quai, phap tac biome | can tuong/quan dung role, khong farm vo nao |
| Choke phong an | cua ra biome 2 | can danh vong, tai nguyen, hoac quyet dinh hy sinh |
| Cong chan | dan quai vat can cong | ep player hoc chuan, co the out som neu manh |

### Thi Luyen Cong

- Cong ra biome la mot thi luyen cua dai nang, nhung bi ngu trang thanh mot dan quai vat can cong.
- Moi cong/co thong co mot boss rieng va mot cot truyen rieng.
- Danh bai boss la co the di ngay, khong can giu vung hay lam them chuoi phong an.
- Gia tri cua cong la day nhanh nguoi choi ra dai the gioi, khong phai giu ho trong biome 1.
- Boss phu co the ton tai de cho reward, lore, hoac duong tat, nhung khong bat buoc.

Biome 1 co the rieng theo nguoi choi hoac theo cum nho, nhung phai bao dam nguoi choi duoc xay identity truoc khi bi cuon vao chinh tri biome 2.

---

## Biome 2 Layout De Xuat

Biome 2 la ban do xa hoi. Tai day map phai bat nguoi choi nhin thay nhau, can nhau va so nhau.

| Vung/Node | Chuc Nang | He Qua Roleplay |
|---|---|---|
| Cho trung lap | mua ban cong khai/an danh | tin dung, lua dao, cam van |
| Linh Mach Trung | nguon nang cap quan/tuong | lien minh tam thoi, chien tranh tranh chap |
| Deo/cau/cong | choke giao thong | thu phi, bao ke, phuc kich, hiep uoc qua duong |
| Di tich lon | objective nhieu ben | chia loot, phan boi, tranh quyen uu tien |
| Vung xam | khong ai so huu ro | noi Tinh Bao/Thuc Luc ngam hoat dong |
| Dat cu tru NPC | dan, mon do, thuong doi | reputation co gia tri thuc te |

Map Biome 2 khong nen thiet ke de tat ca cung du tai nguyen. Thieu hut co chu y la dong co cho giao thuong, ngoai giao, cuop boc va lien minh.

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

### Lenh Hanh Quan

| Lenh | Dung Khi Nao | Rui Ro |
|---|---|---|
| Scout | mo fog, tim dau vet | bi bat scout, lo y do |
| March | di chuyen quan/tai nguyen | bi chan duong, ton hau can |
| Escort | ho tong thuong doi/NPC | cham hon, ton phi |
| Ambush | phuc kich tai choke/vung xam | that bai thi lo danh tinh |
| Rally | tap hop lien minh danh objective | can thoi gian bao truoc, de bi tinh bao phat hien |
| Retreat Condition | lenh nen khi vang mat | chi giam thiet hai, khong tu tao chien thang |

---

## Cau Hoi Mo

- [ ] Map dung hex, square, hay node graph?
- [ ] Biome 1 shared hay rieng?
- [ ] Fog of war luu theo nguoi choi, lien minh, hay the luc?
- [ ] Resource node co can vinh vien, hoi theo chu ky, hay doi trang thai?
- [ ] Co cho nguoi choi xay duong/cong de thay doi map khong?
- [ ] Hanh quan realtime hay theo tick?
