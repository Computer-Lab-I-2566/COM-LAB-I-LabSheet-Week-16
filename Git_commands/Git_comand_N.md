# คำสั่ง git ที่ขึ้นต้นด้วยอักษร N

    new-branch : สร้างสาขาใหม่
    notes : จัดการบันทึกย่อ
    notes-add : เพิ่มบันทึกย่อ
    notes-commit : บันทึกย่อเป็น commit
    notes-find : ค้นหาบันทึกย่อ
    notes-for-commit : แสดงบันทึกย่อสำหรับ commit
    notes-merge : รวมบันทึกย่อ
    notes-remove : ลบบันทึกย่อ
    notes-show : แสดงบันทึกย่อ
    notes-update : อัปเดตบันทึกย่อ

รายละเอียดของแต่ละคำสั่งมีดังนี้

new-branch

คำสั่ง new-branch ใช้สำหรับสร้างสาขาใหม่

git new-branch <branch-name>

ตัวอย่างเช่น หากต้องการสร้างสาขาใหม่ชื่อ "feature" ให้ใช้คำสั่งต่อไปนี้

git new-branch feature

notes

คำสั่ง notes ใช้สำหรับจัดการบันทึกย่อ

git notes <command>

ตัวอย่างเช่น หากต้องการแสดงบันทึกย่อทั้งหมด ให้ใช้คำสั่งต่อไปนี้

git notes

notes-add

คำสั่ง notes-add ใช้สำหรับเพิ่มบันทึกย่อ

git notes add <commit-hash> <message>

ตัวอย่างเช่น หากต้องการเพิ่มบันทึกย่อสำหรับ commit ที่มี hash เท่ากับ "abc123" ให้ใช้คำสั่งต่อไปนี้

git notes add abc123 "This is a note for commit abc123."

notes-commit

คำสั่ง notes-commit ใช้สำหรับบันทึกย่อเป็น commit

git notes commit <notes-ref>

ตัวอย่างเช่น หากต้องการบันทึกย่อเป็น commit ให้ใช้คำสั่งต่อไปนี้

git notes commit notes/feature

notes-find

คำสั่ง notes-find ใช้สำหรับค้นหาบันทึกย่อ

git notes find <pattern>

ตัวอย่างเช่น หากต้องการค้นหาบันทึกย่อที่ตรงกับข้อความ "feature" ให้ใช้คำสั่งต่อไปนี้

git notes find feature

notes-for-commit

คำสั่ง notes-for-commit ใช้สำหรับแสดงบันทึกย่อสำหรับ commit

git notes for-commit <commit-hash>

ตัวอย่างเช่น หากต้องการแสดงบันทึกย่อสำหรับ commit ที่มี hash เท่ากับ "abc123" ให้ใช้คำสั่งต่อไปนี้

git notes for-commit abc123

notes-merge

คำสั่ง notes-merge ใช้สำหรับรวมบันทึกย่อ

git notes merge <source-ref> <target-ref>

ตัวอย่างเช่น หากต้องการรวมบันทึกย่อจากสาขาชื่อ "feature" ไปยังสาขาชื่อ "master" ให้ใช้คำสั่งต่อไปนี้

git notes merge feature master

notes-remove

คำสั่ง notes-remove ใช้สำหรับลบบันทึกย่อ

git notes remove <notes-ref>

ตัวอย่างเช่น หากต้องการลบบันทึกย่อชื่อ "notes/feature" ให้ใช้คำสั่งต่อไปนี้

git notes remove notes/feature

notes-show

คำสั่ง notes-show ใช้สำหรับแสดงบันทึกย่อ

git notes show <notes-ref>

ตัวอย่างเช่น หากต้องการแสดงบันทึกย่อชื่อ "notes/feature" ให้ใช้คำสั่งต่อไปนี้

git notes show notes/feature

notes-update

คำสั่ง notes-update ใช้สำหรับอัปเดตบันทึกย่อ

git notes update <notes-ref> <message>

ตัวอย่างเช่น หากต้องการอัปเดตบันทึกย่อชื่อ "notes/feature" ให้ใช้คำสั่งต่อไปนี้

git notes update notes/feature "This is an updated note for commit abc123."

นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร N เช่น notes-ref-exists, notes-ref-is-empty, notes-ref-name, notes-ref-rewrite, notes-ref-update เป็นต้น

สำหรับคำสั่ง new-branch นั้น สามารถใช้แทนคำสั่ง branch ได้

![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/12f15c29-05b6-46b9-bf6a-261cbb6254d1)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/fc592a0a-de5f-4d51-b076-5bb5b57ffbf1)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/5e71d370-5b24-460e-b142-ebacc501b343)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/a6115ab8-bb04-49fe-ba3e-c566937ecccd)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/a29bd948-acbb-42f4-8d3c-cb80f006c1bf)
