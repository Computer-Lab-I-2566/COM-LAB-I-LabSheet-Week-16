# คำสั่ง git ที่ขึ้นต้นด้วยอักษร M
## Git Merge

เป็นคำสั่งที่ใช้ในการรวม Branch หรือ Commit ทั้งสองเข้าด้วยกัน
ตัวอย่างเราจะอยู่ที่ Branch Master และต้องการ Merge Branch Feature เข้ามาทำงานร่วมด้วย การ Merge แบบ No Fast Forward จะเรียกอีกอย่างหนึ่งว่า 3-Way Merge

           #รวม branch master กับ branch feature แบบ no fast forward
           $git merge --no-ff feature#รวม branch master กับ branch feature แบบ fast forward
           $git merge feature
# ![image](https://github.com/65030121natthamon/Git_A-Z_Mission_65030121/assets/144195611/b361bb17-dd6e-4da8-9f9b-13e5708f1c80)
