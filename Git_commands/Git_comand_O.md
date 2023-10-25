# คำสั่ง git ที่ขึ้นต้นด้วยอักษร O

    object : แสดงข้อมูลเกี่ยวกับ object
    oneline : แสดงข้อมูลเกี่ยวกับ commit แบบ one-line
    origin : แสดงข้อมูลเกี่ยวกับ remote repository ชื่อ "origin"
    out : แสดงข้อมูลเกี่ยวกับ commit
  
รายละเอียดของแต่ละคำสั่งมีดังนี้

object

คำสั่ง object ใช้สำหรับแสดงข้อมูลเกี่ยวกับ object

git object <object-hash>

ตัวอย่างเช่น หากต้องการแสดงข้อมูลเกี่ยวกับ commit ที่มี hash เท่ากับ "abc123" ให้ใช้คำสั่งต่อไปนี้

git object abc123

oneline

คำสั่ง oneline ใช้สำหรับแสดงข้อมูลเกี่ยวกับ commit แบบ one-line

git oneline <commit-hash>

ตัวอย่างเช่น หากต้องการแสดงข้อมูลเกี่ยวกับ commit ที่มี hash เท่ากับ "abc123" แบบ one-line ให้ใช้คำสั่งต่อไปนี้

git oneline abc123

origin

คำสั่ง origin ใช้สำหรับแสดงข้อมูลเกี่ยวกับ remote repository ชื่อ "origin"

git origin

ตัวอย่างเช่น หากต้องการแสดงข้อมูลเกี่ยวกับ remote repository ชื่อ "origin" ให้ใช้คำสั่งต่อไปนี้

git origin

out

คำสั่ง out ใช้สำหรับแสดงข้อมูลเกี่ยวกับ commit

git out <commit-hash>

ตัวอย่างเช่น หากต้องการแสดงข้อมูลเกี่ยวกับ commit ที่มี hash เท่ากับ "abc123" ให้ใช้คำสั่งต่อไปนี้

git out abc123


นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร O เช่น object-id, object-name, object-type, objects, oneline-patch, out-raw, push-all, pull-all เป็นต้น

สำหรับคำสั่ง oneline และ out นั้น สามารถใช้แทนกันได้ แต่ oneline จะแสดงข้อมูลเกี่ยวกับ commit แบบ one-line ในขณะที่ out จะแสดงข้อมูลเกี่ยวกับ commit แบบเต็ม
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/b971c3a2-c36a-4639-9dc2-37e9cb5f8014)
