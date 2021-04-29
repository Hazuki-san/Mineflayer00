# Mineflayer00
A multi (?) purpose bot for MC-ZERO.NET

# อันนี้คืออะไร?
สิ่งนี่คือระบบ BOT ที่ใช้ตัว PrismarineJS ในการสร้าง บอทตัวนี้ออกแบบเพื่อให้ใช้งานกับ MC-ZERO.NET เซิร์ฟ SV Main (GUI 22) แต่สามารถใช้กับเซิร์ฟอื่นๆได้เช่นกัน (ถ้ารู้วิธีแก้)

# อ่านก่อนที่จะเริ่มใช้
ก่อนที่จะใช้งานบอทตัวนี้ โปรดแน่ใจว่า /nick นั้นเป็น ภาษาอังกฤษ เพราะ botowner จะอ่านไม่ได้!<br>
เราไม่มีส่วนรู้เห็นอะไรทั้งนั้นถ้าจะลองใช้บอทอันนี้ แอดมินแบนแล้วเราจะไม่รับผิดชอบ! ถือว่าเตือนแล้วนะ

# ใช้ยังไง?
วิธีสั่ง:<br>
- /w ชื่อบอท !bot [คำสั่ง] (สั่งแค่ตัวนั้นๆ)
- !all [คำสั่ง] (สั่งทุกตัว)

เช่น:<br>
- /w ABCDEF1 !bot route_to me (บอทจะเดินมาหาเรา)
- !all fish (ตกปลาพร้อมกันทุกตัว)

# คำสั่งทั้งหมด
clear_armor - ถอดเกราะออก<br>
click_window - ให้บอทกดไอเทมหมายเลขนั้นๆ หากมีหน้าต่างให้กด เช่น !all click_window start 50 (กดไอเทมหมายเลข 51 ในช่อง)<br>
disconnect - ให้บอทออกจากเกม<br>
drop - โยนของที่ตรงกับไอดีนั้นๆ เช่น 297 (ขนมปัง)<br>
dump - โยนของทั้งหมดที่ตรงกับไอดีนั้น เช่น 349 จะโยนปลาทุกชนิดออก<br>
equip - บอทจะใส่ของตามที่ช่องที่ถือ เช่น !bot equip 1 head (ใส่หมวกในช่องของอันแรก)<br>
experience - ดู EXP บอท<br>
fight - รุมกระทืบผู้เล่นคนนั้นๆ เช่น !all fight Hoap **! ชื่อต้องตรงทุกตัว เช่น Hoap ไม่ใช่ hoap และอยู่ในระยะที่บอทเห็นเท่านั้น !**<br>
fish - ตกปลา <br>
follow - ตามผู้เล่นคนนั้นๆ เช่น !all follow Hoap **! ชื่อต้องตรงทุกตัว เช่น Hoap ไม่ใช่ hoap และอยู่ในระยะที่บอทเห็นเท่านั้น !**<br>
food - เช็คหลอดอาหาร<br>
gear_up - ตรวจสอบเกราะที่มีอยู่ในตัว และใช้อันที่ดีที่สุด!<br>
health - ดูหลอดเลือก<br>
help - ดูคำสั่งทั้งหมด<br>
inventory - แสดงไอเทมทั้งหมดที่มีในไฟล์ JSON<br>
item_activate - ใช้ของที่ถืออยู่<br>
item_deactivate - เลิกใช้<br>
locate - ดูว่าบอทอยู่ไหน<br>
look - ให้บอทมองตรงองศาที่เราให้ เช่น !bot look 90 0 (มองตรง คอหมุนที่ 90 องศา)<br>
ping - เช็คว่าบอทแลคมั้ย<br>
route_stop - สั่งให้บอทหยุดมาที่เราบอก<br>
route_to - ให้บอทเดินไปที่ XYZ ที่เราอยู่ <br>
snipe - เปิดระบบแข่งพิมพ์ไว (ChatReaction)<br>
sudo - สั่งให้บอทพิมพ์คำความนั้นๆ<br>

# วิธีติดตั้ง
1. โหลด ZIP
2. แตกไฟลฺ์
3. เปิด CMD แล้วมาที่โฟลเดอร์ที่ตัวเองแตกไฟล์ไว้
4. แก้ index.js และ alts.txt ตามที่ตัวเองต้องการ
5. `npm install`
6. `node .`
<br>
หากมีข้อสงสัยหรือไม่แน่ใจว่าใช้ยังไง ติดต่อ `@Aoba Suzukaze#0900` ใน Discord ได้เลย
