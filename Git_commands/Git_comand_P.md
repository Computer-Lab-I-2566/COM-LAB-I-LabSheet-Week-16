# คำสั่ง git ที่ขึ้นต้นด้วยอักษร P
patch : สร้าง patch จาก commit
    push : อัปโหลดการเปลี่ยนแปลงไปยัง remote repository
    pull : ดึงการเปลี่ยนแปลงจาก remote repository
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
