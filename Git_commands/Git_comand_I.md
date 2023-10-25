# คำสั่ง git ที่ขึ้นต้นด้วยอักษร I
# Git init
คำสั่งนี้จะทำการสร้าง folder. git ขึ้นมาเพื่อเอาไว้เก็บข้อมูลที่ git (Local)
## ![image](https://github.com/65030121natthamon/Git_A-Z_Mission_65030121/assets/144195611/91640fd9-e832-49e1-ba5c-3ef18a431a76)
ในรูปคือยังไม่มี git repo ฉะนั้นแล้วเราต้อง

1.เข้าไปยัง GitHub หลังจากนั้นก็สมัครใช้งานด้วย Email ของตัวเราเอง และไปที่เมนู + มุมบนขวา และเลือกที่เมนู. new repository 
# ![image](https://github.com/65030121natthamon/Git_A-Z_Mission_65030121/assets/144195611/bdbe64d6-e347-465b-908d-9408446887a3)


2.หลังจากนั้น git จะให้เรากรอกชื่อของ Project ของเรา และคำอธิบาย สำหรับคำอธิบายไม่จำเป็นต้องกรอกก็ได้  และเลือก project ของเราเป็นแบบ private คือส่วนตัวคนอื่นเข้ามาอ่านไม่ได้ หรือว่าจะเป็นแบบ public จะเป็นแบบสาธารณะ 
# ![image](https://github.com/65030121natthamon/Git_A-Z_Mission_65030121/assets/144195611/ee1e03d7-6633-43e8-8340-660924bfdaa1)

3.หลังจากนั้น git จะแเสดงคำแนะนำให้เราว่าควรทำอะไร บ้างเป็นเมนูคำสั่ง 


4.เปิด vscode ขึ้นมาแล้วไปที่. Terminal > New Terminal    vsCode จะเปิดหน้า terminal ให้กับเรา ก็พิมพ์ตามคำสั่งที่ git ให้มาตามด้านบนได้เลย

5.พิมพ์คำสั่งตามนี้

git init
git add README.md
git commit -m "first commit"
git branch -M main

6.  หลังจากนั้นพิมพ์คำสั่ง.

git remote add origin <url project>

หลังจากนั้นก็ใช้คำสั่งเพื่ออัพไฟล์ขึ้นไปยัง git

git push -u origin main

7. เมื่อทำงานเรียบร้อยเราก็จะเห็นไฟล์ของเราบน git แล้ว 

