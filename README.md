# Word Quest - GitHub Starter

เวอร์ชันเริ่มต้นสำหรับ GitHub Pages / Cloudflare Pages

## โครงสร้างไฟล์

```text
index.html
css/style.css
js/config.js
js/app.js
assets/logo.png
assets/bg-desktop.webp
```

## วิธีใช้

1. สร้าง repository ใหม่ใน GitHub เช่น `word-quest`
2. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้เข้า repository
3. ไปที่ Settings > Pages
4. Source เลือก `Deploy from a branch`
5. Branch เลือก `main` และ `/root`
6. กด Save
7. รอ GitHub สร้างลิงก์เว็บ

## รูปภาพ

ให้วางไฟล์รูปใน `assets/`

```text
assets/logo.png
assets/bg-desktop.webp
```

ถ้ายังไม่มีรูป เว็บจะแสดงโลโก้ข้อความแทน และพื้นหลังไล่สีแทน

## Supabase

ตอนนี้ยังใช้ข้อมูลตัวอย่างใน `js/config.js`
ขั้นต่อไปค่อยเชื่อม Supabase โดยเปลี่ยน:

```js
const APP_CONFIG = {
  useSupabase: true,
  supabaseUrl: 'YOUR_SUPABASE_URL',
  supabaseAnonKey: 'YOUR_SUPABASE_ANON_KEY'
};
```
