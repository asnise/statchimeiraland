
####DMG pre(ค่าพลังโจมตีจริงที่ออกมาจริงๆ เรานิยามให้ใหม่)* = (DMG + BonusDMG) + Armor-pier
ค่า stats | แปล + คำนวน
------------ | -------------
DMG(พลังโจมตีที่แสดงผล) | ATK + พลังโจมตีของอาวุธ + ออฟที่ลงท้ายหรือขึ้นต้นด้วย DMG *ไม่ร่วมกับออฟที่มีคำว่า resistance*
HP | HP หรือ HP + ออฟที่เป็น +HP%
DEF & Defense(พลังป้องกัน ค่าที่จะใช้ลบดาเมจแบบตรงๆ)  = DEF x DEF Bonus + (DMG reduction x DMG Resistance)
DMG Resistance | ค่าที่เอาไปลบดาเมจศัตรูตรงๆ เช่นมันตี 500 เรามี 250 = มันตีเข้า 250 - 499 มันน่าจะคิดประมาณนี้
DMG Reduction | DMG Resistance แต่เป็น % *ไม่รู้มันคิดจากอะไร*
Armor-pier(ค่าที่จะทำดเมจโดยจะไม่คิดถึงค่า Defense ศัตรู) | Armor-pier x Renetration
DMG to Travelers | ดาเมจที่กระทำต่อ NPC เช่น NPC มี DEF 1000 แล้วมีค่านี่ 500 + DMG หรือ ATK 1000 = 500 - 1000 ที่เราทำได้ต่อ NPC
Reduction DMG from Travelers | DMG Reduction แต่จะลบดาเมจได้เฉพาะ NPC

Melee Stats(ตีประชิดกายภาพอะ) & Range Stats(ปืน) *มันแยกกันนะแต่หลักการแบบเดียวกัน*

Crit | โอกาสที่ดาเมจจะ คูณ( DMG x (Crit DMG + Crit Bonus/ค่าต้าน crit ศัตรูมั้ง))  สูตรคิดโอกาสเป็น % *Crit% = Crit/10*
*Crit DMG | ค่าที่จะเอา DMG x Crit DMG ค่าสะว่า 100% คือ คูณ 2 มันจะเป็นจังหวะที่ดาเมจเพิ่มเป็นเท่าตัว ยิ่ง Crit เยอะยิ่งออกบ่อยอย่างเช่นมี DMG 1500, Crit DMG 150% ดาเมจที่ศัตรูจะได้รับตอนติดคริ = 1500(DMG) + 1500(100%) +750(50%) = 3750 ศัตรูจะได้รับ*

ค่า Bonus ฯลฯ | ค่าที่จะบวกเพิ่มตรงๆ แต่ถ้าเป็น ออฟ Melee Bonus ไปใส่ปืนมันจะเท่ากับ 0 เพราะ Melee จะใช้ได้แค่พวกตีประชิด

Weakness | ดาเมจที่จะทำโดนจุดอ่อนถ้ามี DMG 100 Weakness 100% ก็โดนจุดอ่อน 100
ค่าอื่นๆของ Range | เหมือนกับ Melee หรือด้านบนเลย

