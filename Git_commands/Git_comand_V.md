# คำสั่ง git ที่ขึ้นต้นด้วยอักษร V

    version : แสดงเวอร์ชันของ Git
    verify-commit : ตรวจสอบความถูกต้องของ commit
    verify-tag : ตรวจสอบความถูกต้องของแท็ก

รายละเอียดของแต่ละคำสั่งมีดังนี้

version

คำสั่ง version ใช้สำหรับแสดงเวอร์ชันของ Git

git version

คำสั่งนี้จะแสดงเวอร์ชันของ Git ที่ติดตั้งอยู่

verify-commit

คำสั่ง verify-commit ใช้สำหรับตรวจสอบความถูกต้องของ commit

git verify-commit <commit-hash>

ตัวอย่างเช่น หากต้องการตรวจสอบความถูกต้องของ commit ที่มี hash เท่ากับ "abc123" ให้ใช้คำสั่งต่อไปนี้

git verify-commit abc123

verify-tag

คำสั่ง verify-tag ใช้สำหรับตรวจสอบความถูกต้องของแท็ก

git verify-tag <tag-name>

ตัวอย่างเช่น หากต้องการตรวจสอบความถูกต้องของแท็กชื่อ "v1.0.0" ให้ใช้คำสั่งต่อไปนี้

git verify-tag v1.0.0

นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร V เช่น verify-signature เป็นต้น

สำหรับคำสั่ง verify-commit และ verify-tag นั้น สามารถใช้แทนกันได้ แต่ verify-commit จะตรวจสอบความถูกต้องของ commit ในขณะที่ verify-tag จะตรวจสอบความถูกต้องของแท็ก

ตัวอย่างการใช้งานคำสั่ง version
แสดงเวอร์ชันของ Git

git version

ตัวอย่างการใช้งานคำสั่ง verify-commit
แสดงข้อมูลเกี่ยวกับ commit ที่มี hash เท่ากับ "abc123"

git show abc123
ตรวจสอบความถูกต้องของ commit ที่มี hash เท่ากับ "abc123"

git verify-commit abc123

ตัวอย่างการใช้งานคำสั่ง verify-tag
แสดงข้อมูลเกี่ยวกับแท็กชื่อ "v1.0.0"

git show v1.0.0
ตรวจสอบความถูกต้องของแท็กชื่อ "v1.0.0"

git verify-tag v1.0.0
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/cd60c221-d5b6-4af0-a0e6-90303f39a22b)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/32f2e394-6219-4db4-8ffd-2ddc2a5ea980)

