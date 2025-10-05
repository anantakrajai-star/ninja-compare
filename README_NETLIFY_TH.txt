
Math Ninja Compare — v22 (Netlify Deploy Pack)

วิธีใช้งานกับ Netlify Drop:
1) แตกไฟล์ zip นี้ จะได้โฟลเดอร์ MathNinjaCompare_v22_Netlify
2) เปิดเว็บแอป Netlify แล้วไปที่หน้า "Drop" (drag-and-drop)
3) ลาก/วางทั้งโฟลเดอร์ MathNinjaCompare_v22_Netlify ลงไป (ต้องมีไฟล์ index.html อยู่รากโฟลเดอร์)
4) รอให้ Deploy เสร็จ จะได้ลิงก์เว็บไซต์พร้อมใช้งาน

หมายเหตุ:
• ใส่ไฟล์ index.html ไว้ที่รากเสมอ (Netlify จะหา index.html อัตโนมัติ)
• มีไฟล์ 404.html เป็นสำรองหน้าเดียวกับ index.html เพื่อกัน reload แล้วหลงทาง (SPA fallback)
• ไฟล์นี้เป็น single-file app (ภาพ/เสียงฝังในตัว) จึงไม่ต้องมีทรัพยากรอื่น

Dropbox:
• Dropbox ไม่รองรับการ "รันเว็บ" HTML ผ่านลิงก์แชร์โดยตรง (จะเปิดเป็นตัวดูไฟล์/ดาวน์โหลดแทน)
• วิธีใช้กับ Dropbox: ให้แชร์เป็นไฟล์ให้ดาวน์โหลด แล้วเปิดแบบออฟไลน์บนเบราว์เซอร์ หรือใช้ Netlify สำหรับเล่นออนไลน์

อัปเดตแพ็ก: 2025-10-03T19:33:48
