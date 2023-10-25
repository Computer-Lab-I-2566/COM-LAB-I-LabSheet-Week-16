# คำสั่ง git ที่ขึ้นต้นด้วยอักษร W

    whatchanged : แสดงการเปลี่ยนแปลงตั้งแต่ครั้งล่าสุดที่ commit
    worktree : จัดการ worktree

รายละเอียดของแต่ละคำสั่งมีดังนี้

whatchanged

คำสั่ง whatchanged ใช้สำหรับแสดงการเปลี่ยนแปลงตั้งแต่ครั้งล่าสุดที่ commit

git whatchanged

คำสั่งนี้จะแสดงการเปลี่ยนแปลงทั้งหมดตั้งแต่ครั้งล่าสุดที่ commit

worktree

คำสั่ง worktree ใช้สำหรับจัดการ worktree

git worktree <command>

ตัวอย่างเช่น หากต้องการสร้าง worktree ใหม่ ให้ใช้คำสั่งต่อไปนี้

git worktree add <worktree-name> <remote-branch>

นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร W เช่น whatchanged-since, whatchanged-until, whatchanged-tree, whatchanged-tree-diff เป็นต้น

สำหรับคำสั่ง whatchanged นั้น สามารถใช้แทนคำสั่ง log ได้ แต่ whatchanged จะแสดงการเปลี่ยนแปลงทั้งหมดตั้งแต่ครั้งล่าสุดที่ commit ในขณะที่ log จะแสดงการเปลี่ยนแปลงทั้งหมดตั้งแต่ commit ที่กำหนด

ตัวอย่างการใช้งานคำสั่ง whatchanged
แสดงการเปลี่ยนแปลงทั้งหมดตั้งแต่ครั้งล่าสุดที่ commit

git whatchanged

ตัวอย่างการใช้งานคำสั่ง worktree
สร้าง worktree ใหม่ชื่อ "feature" สำหรับ branch ชื่อ "feature" บน remote ชื่อ "origin"

git worktree add feature origin/feature
แสดงรายการ worktree ทั้งหมด

git worktree list
เปลี่ยนการทำงานไปที่ worktree ชื่อ "feature"

git worktree checkout feature
ลบ worktree ชื่อ "feature"

git worktree remove feature

คำสั่ง whatchanged และ worktree เป็นคำสั่งที่มีประโยชน์สำหรับการจัดการการเปลี่ยนแปลงของไฟล์และ worktree
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/340fa1eb-3a3d-462a-92c2-1c32764108f1)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/0df37c3c-a5dc-4064-b9eb-880069507c2e)
