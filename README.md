# Website Templates สำหรับ TikTok Developer App

ไฟล์เหล่านี้ใช้สำหรับ verify domain ใน TikTok Developer Portal

## ไฟล์ที่มี

- `index.html` - หน้าหลัก
- `terms.html` - Terms of Service
- `privacy.html` - Privacy Policy
- `contact.html` - Contact page

## วิธีใช้งาน

### ตัวเลือก 1: Deploy บน GitHub Pages (ฟรี)

1. สร้าง repository ใหม่บน GitHub
2. อัปโหลดไฟล์ทั้งหมดใน folder นี้
3. ไปที่ Settings > Pages
4. เลือก branch: main, folder: / (root)
5. Save
6. รอสักครู่ เว็บจะพร้อมใช้งานที่ `https://yourusername.github.io/repo-name`

### ตัวเลือก 2: Deploy บน Vercel (ฟรี)

1. ไปที่ https://vercel.com
2. Sign up ด้วย GitHub
3. Import repository
4. Deploy
5. รับ URL: `https://your-project.vercel.app`

### ตัวเลือก 3: Deploy บน Netlify (ฟรี)

1. ไปที่ https://netlify.com
2. Sign up
3. Drag & drop folder นี้
4. รับ URL: `https://your-site.netlify.app`

### ตัวเลือก 4: ใช้ Web Hosting ของคุณเอง

1. อัปโหลดไฟล์ทั้งหมดไปที่ root directory
2. ตรวจสอบว่าเข้าถึงได้ที่:
   - `https://yourdomain.com/`
   - `https://yourdomain.com/terms.html`
   - `https://yourdomain.com/privacy.html`

## การ Verify Domain ใน TikTok

หลังจาก deploy เว็บแล้ว:

1. ไปที่ TikTok Developer Portal
2. เลือก App ของคุณ
3. ไปที่ "URL properties"
4. คลิก "Verify URL properties"
5. เลือกวิธี verify:
   - **DNS Verification**: เพิ่ม TXT record ใน DNS
   - **HTML File Verification**: ดาวน์โหลดไฟล์และอัปโหลดไปที่เว็บ

## แก้ไขข้อมูล

แก้ไขข้อมูลต่อไปนี้ให้ตรงกับของคุณ:

- Email: `support@bottiktok.com` → อีเมลจริงของคุณ
- Domain: `bottiktok.com` → domain จริงของคุณ
- ชื่อแอป: "TikTok Upload Bot" → ชื่อแอปของคุณ

## หมายเหตุ

- ไฟล์เหล่านี้เป็นเพียงตัวอย่าง
- คุณควรปรับแต่งเนื้อหาให้เหมาะสมกับแอปของคุณ
- ตรวจสอบให้แน่ใจว่า Terms และ Privacy Policy ถูกต้องตามกฎหมาย
