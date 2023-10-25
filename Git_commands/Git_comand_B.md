# คำสั่ง git ที่ขึ้นต้นด้วยอักษร B

### git branch : สร้างหรือจัดการสาขา
### git branch (branch)  : สร้าง branch ใหม่ที่มีชื่อว่า (branch) โดยอ้างอิงจุดในอดีตตาม branch ปัจจุบัน
### git branch (branch) (start-point) : สร้าง branch ใหม่ที่มีชื่อว่า (branch) โดยอ้างอิงจุดเริ่มต้นจาก (start-point) ที่ระบุในคำสั่ง ซึ่งอาจจะเป็น branch name หรือ tag name.
### git branch -d (branch) : ลบ branch ที่ชื่อว่า (branch)
### git branch -D (branch) : ลบ branch ที่ชื่อว่า (branch) โดยไม่สนใจสถานะการ merged
### git checkout (branch)  : ย้าย branch มาอยู่ที่ (branch) พร้อมทั้งเปลี่ยนแปลงทุกอย่างที่อยู่ใน working directory ให้เป็นไปตาม (branch) ใน repository
### git checkout -b (new) (start-point)	 : สร้าง branch ใหม่ที่ชื่อว่า (new) โดยอ้างอิงจุดเริ่มต้นเป็น (start-point) จากนั้นก็ทำการ checkout
### git blame : แสดงประวัติการแก้ไขไฟล์
### git bisect : ค้นหาการคอมมิตที่ทำให้เกิดการเปลี่ยนแปลง
