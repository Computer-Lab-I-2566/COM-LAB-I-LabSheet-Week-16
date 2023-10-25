# คำสั่ง git ที่ขึ้นต้นด้วยอักษร O

    object : แสดงข้อมูลเกี่ยวกับ object
    oneline : แสดงข้อมูลเกี่ยวกับ commit แบบ one-line
    origin : แสดงข้อมูลเกี่ยวกับ remote repository ชื่อ "origin"
    out : แสดงข้อมูลเกี่ยวกับ commit
    patch : สร้าง patch จาก commit
    push : อัปโหลดการเปลี่ยนแปลงไปยัง remote repository
    pull : ดึงการเปลี่ยนแปลงจาก remote repository

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

patch

คำสั่ง patch ใช้สำหรับสร้าง patch จาก commit

git patch <commit-hash>

ตัวอย่างเช่น หากต้องการสร้าง patch จาก commit ที่มี hash เท่ากับ "abc123" ให้ใช้คำสั่งต่อไปนี้

git patch abc123

push

คำสั่ง push ใช้สำหรับอัปโหลดการเปลี่ยนแปลงไปยัง remote repository

git push <remote> <branch>

ตัวอย่างเช่น หากต้องการอัปโหลดการเปลี่ยนแปลงไปยัง remote repository ชื่อ "origin" และสาขาชื่อ "master" ให้ใช้คำสั่งต่อไปนี้

git push origin master

pull

คำสั่ง pull ใช้สำหรับดึงการเปลี่ยนแปลงจาก remote repository

git pull <remote> <branch>

ตัวอย่างเช่น หากต้องการดึงการเปลี่ยนแปลงจาก remote repository ชื่อ "origin" และสาขาชื่อ "master" ให้ใช้คำสั่งต่อไปนี้

git pull origin master

นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร O เช่น object-id, object-name, object-type, objects, oneline-patch, out-raw, push-all, pull-all เป็นต้น

สำหรับคำสั่ง oneline และ out นั้น สามารถใช้แทนกันได้ แต่ oneline จะแสดงข้อมูลเกี่ยวกับ commit แบบ one-line ในขณะที่ out จะแสดงข้อมูลเกี่ยวกับ commit แบบเต็ม
