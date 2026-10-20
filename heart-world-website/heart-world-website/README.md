# Our Little Heart World

เว็บ static HTML/CSS/JS ไม่ต้องติดตั้ง dependencies

## เปิดใน VS Code
1. แตกไฟล์ ZIP
2. เปิดโฟลเดอร์ `heart-world-website` ใน VS Code
3. เปิด `index.html` ในเบราว์เซอร์ หรือใช้ส่วนขยาย Live Server
4. วิดีโอจะเล่นตามลำดับ `assets/video/1.mp4` ถึง `assets/video/8.mp4` เมื่อกดเล่นคลิปแรก คลิปถัดไปจะเล่นต่อโดยอัตโนมัติ
5. เพลงประกอบอยู่ที่ `assets/song.mp3` โดยเริ่มก่อนวิดีโอ 3 วินาที เสียงวิดีโอตั้งไว้ที่ 20% และเพลงที่ 40%

## กล่องของขวัญครบรอบ
- คลิกหีบสมบัติแล้วกรอกรหัสผ่าน `Pr0mlovejib` (ตัวพิมพ์เล็ก/ใหญ่ต้องตรงกัน)
- หากวิดีโอยังไม่พร้อม ฉากห้องนั่งเล่นจะแสดงข้อความแทนเครื่องเล่น

## Deploy บน Vercel
1. อัปโหลดโฟลเดอร์นี้ขึ้น GitHub
2. ใน Vercel เลือก Add New Project แล้ว Import repository
3. Framework Preset เลือก Other
4. Build Command และ Output Directory เว้นว่างไว้ (หรือใช้ค่าเริ่มต้นที่ Vercel ตรวจพบ)
5. กด Deploy
