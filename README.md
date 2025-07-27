# 💼 IT Support Request Flow (Power Automate)

ระบบสั่งงาน IT ที่พัฒนาด้วย **Power Automate** เชื่อมโยงกับ Microsoft Form, SharePoint, Planner และ Excel Online เพื่อให้การแจ้งงานและติดตามงานเป็นไปอย่างอัตโนมัติและมีประสิทธิภาพ

## 📁 รายละเอียดไฟล์

| โฟลเดอร์ | เนื้อหา |
|----------|---------|
| `it-support-flow/` | ไฟล์ `.zip` ที่ Export มาจาก Power Automate Flow สำหรับระบบแจ้งงาน IT Support ภายในองค์กร |

## 🧠 ฟังก์ชันหลักของ Flow นี้

✅ รับข้อมูลจาก **Microsoft Forms**  
✅ ส่งต่อข้อมูลเข้าระบบ **SharePoint (List)** เพื่อเก็บข้อมูล  
✅ เชื่อมต่อ **Planner** เพื่อสร้าง Task ให้ทีม IT  
✅ อัปเดตสถานะ/การตอบกลับอัตโนมัติผ่าน **Outlook Email**  
✅ ส่งออกข้อมูลไปยัง **Excel Online** สำหรับสรุปข้อมูลใน Power BI

## 🔧 สิ่งที่ใช้ในระบบนี้

- Microsoft Power Automate
- Microsoft Forms
- SharePoint Online
- Planner
- Excel Online (Office Scripts)
- Power BI (สำหรับ Dashboard)

## 📦 การนำเข้า Flow

1. ไปที่ [Power Automate](https://make.powerautomate.com/)
2. เลือกเมนู **Solutions** > Import solution
3. เลือกไฟล์ `.zip` ที่อยู่ในโฟลเดอร์ `it-support-flow`
4. ตรวจสอบ Connection และแก้ไขตามความเหมาะสมขององค์กรคุณ

## 👨‍💻 ผู้พัฒนา

- ชื่อ: Nuttakit Kraiphan
- ตำแหน่ง: IT Support / Power Platform Developer
- อีเมล: 

---

