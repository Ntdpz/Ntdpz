# วิธีติดตั้ง README โปรไฟล์ NZN (Windows)

นี่คือไฟล์สำหรับ Repository: https://github.com/Ntdpz/Ntdpz

## โครงสร้างไฟล์

- README.md — เนื้อหาโปรไฟล์
- assets/hero.gif — ป้ายแนะนำตัวแบบเคลื่อนไหว
- assets/terminal.gif — Terminal animation
- assets/flow.gif — แผนภาพระบบ AI แบบเคลื่อนไหว
- assets/loop.gif — แอนิเมชันแนวคิดการพัฒนา
- assets/hero-preview.png — ภาพนิ่งของแบนเนอร์ (ไม่จำเป็นต้องอ้างจาก README)

## แนะนำ: ใช้ Git / PowerShell

1. ดาวน์โหลด ZIP และแตกไฟล์
2. เปิด PowerShell ในไดเรกทอรีที่ต้องการจัดเก็บ Repository
3. รัน:

```powershell
git clone https://github.com/Ntdpz/Ntdpz.git
cd Ntdpz
```

4. คัดลอก `README.md` และทั้งโฟลเดอร์ `assets` จาก ZIP มาวางในโฟลเดอร์ `Ntdpz` ที่ clone มา โดยอนุญาตให้แทนที่ README เดิม
5. รัน:

```powershell
git add README.md assets/
git commit -m "feat: create animated NZN profile README"
git push origin main
```

6. เปิด https://github.com/Ntdpz และรีเฟรชเพื่อดูผล

**ทางเลือก: ไม่ใช้ Git CLI**
เปิด Repository -> Add file -> Upload files แล้วลาก `README.md` และโฟลเดอร์ `assets` ที่แตกไฟล์ไว้เข้าไป จากนั้น Commit changes ตรวจสอบว่าไฟล์ถูกวางตามโครงสร้างด้านบนก่อน Commit

## ข้อควรรู้

- GIF ทั้ง 4 ไฟล์อยู่ใน Repository เอง จึงไม่ต้องพึ่งเว็บทำแอนิเมชัน
- ป้าย Shields.io และตัวนับผู้เข้าชมเป็นบริการภายนอก
- GitHub Stats อยู่ในส่วนพับเก็บ (details) เป็นทางเลือก และอาจแสดงไม่ขึ้นเมื่อบริการภายนอกขัดข้อง
- LinkedIn / Email ไม่ได้ใส่ เพราะยังไม่มีลิงก์ที่ยืนยันในคำขอนี้
- เนื้อหาและโปรเจกต์สามารถแก้ไขได้ใน README.md ทันที
