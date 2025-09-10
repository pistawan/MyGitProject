
 ชื่อ: พิศตะวัน สุขเกษม 
 โจทย์: รวมงานจาก Test001 และ Test002 ด้วยการสร้าง branch แล้ว merge --- 
 สิ่งที่ได้ทำ  
 1. สร้างโปรเจกต์ใหม่บนเครื่อง - โฟลเดอร์ชื่อ MyGitProject - ใช้คำสั่ง git init เพื่อเริ่มต้น Git 
 2. เพิ่มไฟล์จากงาน Test001 ลงใน branch main - ลากไฟล์จาก test001 → มาใส่ในโฟลเดอร์โปรเจกต์ - สั่ง git add . และ git commit -m "เพิ่มงานจาก test001" 
 3. สร้าง Repository บน GitHub และเชื่อมต่อ - ตั้งชื่อว่า my-git-merge - เชื่อม repo ด้วยคำสั่ง git remote add origin ... - Push ขึ้น GitHub ด้วย git push -u origin main ### 
 4. สร้าง branch ใหม่ชื่อ FromTest2
bash
git checkout -b FromTest2


