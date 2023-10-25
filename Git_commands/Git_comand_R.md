# คำสั่ง git ที่ขึ้นต้นด้วยอักษร R
# git reset
คือคำสั่งที่ใช้ย้อนกลับการเปลี่ยนแปลงใน Git repository ของคุณ สามารถใช้เพื่อรีเซ็ตสถานะของ working directory, staging area หรือ commit history

# ตัวอย่างการใช้งานคำสั่ง git reset

#### ยกเลิกการ stage ไฟล์ `README.md`
git reset HEAD README.md

#### ยกเลิกการเปลี่ยนแปลงใน working directory
git reset --hard

#### รีเซ็ต repository ไปยัง commit ก่อนหน้า
git reset --hard HEAD~1

#### ยกเลิกการ merge
git reset --merge
