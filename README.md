# sitron_crud_test

โปรเจกต์นี้เป็นระบบ CRUD สำหรับจัดการข้อมูลหนัง (Movies) โดยใช้ **Node.js (Express)** เป็น backend และ **Next.js** เป็น frontend

---

## ฟีเจอร์หลัก

- ลงชื่อเข้าใช้ (Login) ด้วยระบบ JWT
- ดูรายชื่อหนังทั้งหมด
- เพิ่มหนังใหม่
- แก้ไขข้อมูลหนัง
- ลบหนัง (เฉพาะผู้ใช้ที่มีบทบาท MANAGER เท่านั้น)
- แสดงบทบาทผู้ใช้บนหน้า Dashboard
- ระบบจัดการบทบาทผู้ใช้ (MANAGER, TEAMLEADER, FLOORSTAFF)

---

## เทคโนโลยีที่ใช้

- Backend: Node.js, Express, MongoDB, Mongoose, JSON Web Token (JWT)
- Frontend: Next.js, React, Tailwind CSS, DaisyUI
- การจัดการสถานะและ Routing: React hooks, Next.js Router

---

## วิธีติดตั้งและใช้งาน

1. Clone โปรเจกต์นี้ไปยังเครื่องของคุณ

```bash
git clone https://github.com/yourusername/sitron_crud_test.git
cd sitron_crud_test
