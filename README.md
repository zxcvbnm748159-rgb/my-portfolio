# 👨‍💻 Resume & Portfolio — กิตติธัช ปัจพิบูลย์

เว็บไซต์ประวัติและผลงานส่วนตัว (Resume & Portfolio) สำหรับใช้สมัครงานด้านพัฒนา Web Application
สร้างด้วย HTML5, CSS3 และ JavaScript ในไฟล์ `index.html` เพียงไฟล์เดียว ไม่ต้องติดตั้งอะไรเพิ่ม

## ✨ ฟีเจอร์

- หน้าเดียวครบ: ประวัติ, ทักษะ, ผลงาน และช่องทางติดต่อ
- Responsive รองรับทั้งมือถือ แท็บเล็ต และคอมพิวเตอร์
- รองรับโหมดมืด/สว่างตามการตั้งค่าของอุปกรณ์ (`prefers-color-scheme`)
- คำนวณอายุจากวันเกิดอัตโนมัติด้วย JavaScript
- แถบทักษะมีแอนิเมชันเมื่อเลื่อนมาถึง (Intersection Observer)
- ใช้ฟอนต์ Prompt จาก Google Fonts

## 🗂️ ผลงานที่แสดงในเว็บ

| โปรเจกต์ | รายละเอียด | เทคโนโลยี |
|---|---|---|
| [Mango Detector](https://github.com/zxcvbnm748159-rgb/mango-detector) | ตรวจจับมะม่วงดิบ/สุกแบบ Real-time ผ่านกล้อง | Python, Flask, OpenCV |
| [RarePart Finder](https://github.com/zxcvbnm748159-rgb/RarePart-Finder) | เว็บซื้อขายอะไหล่หายากสำหรับรถ | HTML, CSS, JavaScript |

## 🛠️ เทคโนโลยีที่ใช้

- HTML5
- CSS3 (CSS Variables, Grid, Flexbox)
- JavaScript (Vanilla)

## 🚀 วิธีใช้งาน

**เปิดบนเครื่อง**

```bash
git clone https://github.com/zxcvbnm748159-rgb/<ชื่อ-repo-นี้>.git
cd <ชื่อ-repo-นี้>
```

จากนั้นดับเบิลคลิกไฟล์ `index.html` เพื่อเปิดในเบราว์เซอร์

**เผยแพร่ฟรีด้วย GitHub Pages**

1. ไปที่ **Settings → Pages** ของ repo
2. ที่ **Source** เลือก `Deploy from a branch`
3. เลือก branch `main` และโฟลเดอร์ `/ (root)` แล้วกด **Save**
4. รอ 1–2 นาที เว็บจะอยู่ที่ `https://zxcvbnm748159-rgb.github.io/<ชื่อ-repo-นี้>/`

## ✏️ วิธีแก้ไขข้อมูล

| ต้องการแก้ | แก้ที่ |
|---|---|
| ชื่อ / ข้อมูลส่วนตัว | ส่วน `<section id="about">` |
| ระดับทักษะ (%) | ค่า `data-w="..."` ในส่วน `#skills` |
| ผลงาน | ส่วน `<section id="projects">` (คัดลอก `<article class="card proj">` เพื่อเพิ่ม) |
| สีธีม | ตัวแปรสีใน `:root` ที่ต้นไฟล์ CSS |

## 📁 โครงสร้างไฟล์

```
.
├── index.html   # หน้าเว็บทั้งหมด (HTML + CSS + JS)
└── README.md
```

## 📬 ติดต่อ

- LinkedIn: [kittitut-puhpiboon](https://www.linkedin.com/in/kittitut-puhpiboon-b56b5a43b)
- GitHub: [zxcvbnm748159-rgb](https://github.com/zxcvbnm748159-rgb)

---

© กิตติธัช ปัจพิบูลย์
