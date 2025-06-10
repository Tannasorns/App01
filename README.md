# 🛡️ Phishing Education Website

เว็บไซต์การศึกษาเพื่อสร้างความตระหนักรู้เกี่ยวกับการโจมตี Phishing และความปลอดภัยไซเบอร์

## 📋 คุณสมบัติ

- หน้าแสดงคำเตือนการโจมตี Phishing
- ข้อมูลการศึกษาเกี่ยวกับความปลอดภัยไซเบอร์
- การออกแบบ Responsive Design
- เนื้อหาภาษาไทยที่เข้าใจง่าย

## 🚀 การ Deploy ไปยัง Vercel

### วิธีที่ 1: ผ่าน Git Repository
1. สร้าง repository ใหม่บน GitHub
2. Push โค้ดขึ้น GitHub
3. เข้าไปที่ [vercel.com](https://vercel.com)
4. เชื่อมต่อกับ GitHub account
5. Import repository และ deploy

### วิธีที่ 2: ผ่าน Vercel CLI
```bash
# ติดตั้ง Vercel CLI
npm i -g vercel

# Login เข้า Vercel
vercel login

# Deploy โปรเจกต์
vercel

# Deploy แบบ production
vercel --prod
```

## 🔧 การรันโปรเจกต์ในเครื่อง

```bash
# ติดตั้ง dependencies
npm install

# รันเซิร์ฟเวอร์ในเครื่อง
npm run dev
```

## 📁 โครงสร้างไฟล์

```
├── index.html          # หน้าหลักแสดงการศึกษา Phishing
├── Mslogin.html        # หน้าจำลอง Microsoft Login
├── vercel.json         # การตั้งค่า Vercel
├── package.json        # ข้อมูลโปรเจกต์และ dependencies
└── README.md           # เอกสารโปรเจกต์
```

## 🌐 Live Demo

เมื่อ deploy เสร็จแล้ว เว็บไซต์จะสามารถเข้าถึงได้ที่ URL ที่ Vercel สร้างให้

## ⚠️ หมายเหตุ

เว็บไซต์นี้สร้างขึ้นเพื่อการศึกษาเท่านั้น เพื่อสร้างความตระหนักรู้เกี่ยวกับความปลอดภัยไซเบอร์