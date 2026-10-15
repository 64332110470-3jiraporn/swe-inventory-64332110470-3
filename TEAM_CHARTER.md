## สมาชิกและบทบาท

| ชื่อ | GitHub Username | บทบาท |
|---|---|---|
| จิราภร สีสาวแห 64332110470-3 | 64332110470-3jiraporn | Product Owner / Developer |
| AI Assistant | - | Scrum Master / Developer (review) |

## Branching Strategy

ใช้ GitHub Flow:
- `main` branch ต้อง deploy ได้เสมอ ห้าม commit โดยตรง
- ทุก feature ใหม่ต้องสร้าง branch ชื่อ `feat/<issue-number>-<short-name>`
- ทุก PR ต้องผ่าน review ก่อน merge
  - ทำคนเดียว: AI ในบท reviewer review ตามสี่มุมของขั้นที่ 8 และวางผลลงใน PR
  - จากนั้นฉันจะตอบทุกข้อก่อน merge ���อง

## WIP limit

- คอลัมน์ In Progress มีการ์ดพร้อมกันได้ไม่เกิน 1 ใบ
- เมื่อการ์ดเต็ม WIP limit ห้ามลากการ์ดใหม่เข้ามา
- ให้ทำการ์ดเดิมให้เสร็จ หรือ review PR ที่ค้างใน In Review ก่อน
- ปรับ WIP limit ระหว่าง sprint ได้ แต่ต้องเขียนเหตุผลกำกับไว้ท้ายหัวข้อนี้

## Sprint Goal (Sprint 1)

ส่งมอบระบบสต็อกสินค้าแบบ command-line ที่ใช้งานได้จริง โดยทำ story หลักให้ผ่าน acceptance criteria และ merge ผ่าน PR ตาม GitHub Flow

## AI Usage Policy

- ใช้ AI ช่วยเขียน draft code และ draft commit message ได้
- ทุก commit message ที่ AI generate ต้องอ่านและแก้ให้ตรงกับ diff จริงก่อน commit
- ห้าม copy code จาก AI โดยไม่อ่านและทำความเข้าใจก่อน
- ใช้เฉพาะ AI ที่ไม่มีค่าใช้จ่าย ไม่บังคับซื้อ subscription
