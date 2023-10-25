# คำสั่ง git ที่ขึ้นต้นด้วยอักษร L

    list-files : แสดงรายการไฟล์และไดเร็กทอรีทั้งหมดใน repository
    log : แสดงประวัติของ Git
    log-graph : แสดงประวัติของ Git ในรูปแบบกราฟ
    ls-files : แสดงรายการไฟล์และไดเร็กทอรีทั้งหมดใน repository
    ls-remote : แสดงรายการ references จาก remote repository
    ls-tree : แสดงโครงสร้างของ tree
    ls-tree-oneline : แสดงโครงสร้างของ tree แบบ one-line
    ls-tree-full-name : แสดงโครงสร้างของ tree แบบ full-name

รายละเอียดของแต่ละคำสั่งมีดังนี้

list-files

คำสั่ง list-files ใช้สำหรับแสดงรายการไฟล์และไดเร็กทอรีทั้งหมดใน repository

git list-files

คำสั่งนี้จะแสดงรายการไฟล์และไดเร็กทอรีทั้งหมดใน repository

log

คำสั่ง log ใช้สำหรับแสดงประวัติของ Git

git log

คำสั่งนี้จะแสดงประวัติของ Git ตั้งแต่ commit ล่าสุดจนถึง commit แรก

log-graph

คำสั่ง log-graph ใช้สำหรับแสดงประวัติของ Git ในรูปแบบกราฟ

git log-graph

คำสั่งนี้จะแสดงประวัติของ Git ในรูปแบบกราฟ ซึ่งจะช่วยให้มองเห็นความสัมพันธ์ระหว่าง commit ต่างๆ ได้ง่ายขึ้น

ls-files

คำสั่ง ls-files ใช้สำหรับแสดงรายการไฟล์และไดเร็กทอรีทั้งหมดใน repository

git ls-files

คำสั่งนี้จะแสดงรายการไฟล์และไดเร็กทอรีทั้งหมดใน repository

ls-remote

คำสั่ง ls-remote ใช้สำหรับแสดงรายการ references จาก remote repository

git ls-remote <remote>

ตัวอย่างเช่น หากต้องการแสดงรายการ references จาก remote repository ชื่อ "origin" ให้ใช้คำสั่งต่อไปนี้

git ls-remote origin

ls-tree

คำสั่ง ls-tree ใช้สำหรับแสดงโครงสร้างของ tree

git ls-tree <tree-ish>

ตัวอย่างเช่น หากต้องการแสดงโครงสร้างของ tree ชื่อ "HEAD" ให้ใช้คำสั่งต่อไปนี้

git ls-tree HEAD

ls-tree-oneline

คำสั่ง ls-tree-oneline ใช้สำหรับแสดงโครงสร้างของ tree แบบ one-line

git ls-tree-oneline <tree-ish>

ตัวอย่างเช่น หากต้องการแสดงโครงสร้างของ tree ชื่อ "HEAD" แบบ one-line ให้ใช้คำสั่งต่อไปนี้

git ls-tree-oneline HEAD

ls-tree-full-name

คำสั่ง ls-tree-full-name ใช้สำหรับแสดงโครงสร้างของ tree แบบ full-name

git ls-tree-full-name <tree-ish>

ตัวอย่างเช่น หากต้องการแสดงโครงสร้างของ tree ชื่อ "HEAD" แบบ full-name ให้ใช้คำสั่งต่อไปนี้

git ls-tree-full-name HEAD

นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร L เช่น ls-files-by-commit, ls-files-by-history, ls-files-by-tag, ls-files-with-content, ls-tree-common, ls-tree-recursive, ls-tree-remote, ls-tree-remote-branches, ls-tree-remote-tags, ls-tree-stage เป็นต้น

สำหรับคำสั่ง list-files และ ls-files นั้น สามารถใช้แทนกันได้ แต่ ls-files เป็นคำสั่งที่ใหม่กว่า
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/3b04666f-89ae-4cfe-ad56-beb23fa24ef4)
