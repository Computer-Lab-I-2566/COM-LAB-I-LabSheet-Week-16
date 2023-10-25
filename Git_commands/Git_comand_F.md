# คำสั่ง git ที่ขึ้นต้นด้วยอักษร F
fetch-pack : ดาวน์โหลดการเปลี่ยนแปลงจาก remote repository
fetch-ref : ดาวน์โหลด references จาก remote repository
fetch-tags : ดาวน์โหลด tags จาก remote repository
fetch-update-server-info : ดาวน์โหลดข้อมูลเกี่ยวกับ remote repository
fetch : ดาวน์โหลดการเปลี่ยนแปลงล่าสุดจาก remote repository
รายละเอียดของแต่ละคำสั่งมีดังนี้

fetch-pack

คำสั่ง fetch-pack ใช้สำหรับดาวน์โหลดการเปลี่ยนแปลงจาก remote repository

git fetch-pack <remote>

ตัวอย่างเช่น หากต้องการดาวน์โหลดการเปลี่ยนแปลงล่าสุดจาก remote repository ชื่อ "origin" ให้ใช้คำสั่งต่อไปนี้

git fetch-pack origin

fetch-ref

คำสั่ง fetch-ref ใช้สำหรับดาวน์โหลด references จาก remote repository

git fetch-ref <remote> <ref>

ตัวอย่างเช่น หากต้องการดาวน์โหลด reference ชื่อ "refs/heads/master" จาก remote repository ชื่อ "origin" ให้ใช้คำสั่งต่อไปนี้

git fetch-ref origin refs/heads/master

fetch-tags

คำสั่ง fetch-tags ใช้สำหรับดาวน์โหลด tags จาก remote repository

git fetch-tags <remote>

ตัวอย่างเช่น หากต้องการดาวน์โหลด tags จาก remote repository ชื่อ "origin" ให้ใช้คำสั่งต่อไปนี้

git fetch-tags origin

fetch-update-server-info

คำสั่ง fetch-update-server-info ใช้สำหรับดาวน์โหลดข้อมูลเกี่ยวกับ remote repository

git fetch-update-server-info <remote>

ตัวอย่างเช่น หากต้องการดาวน์โหลดข้อมูลเกี่ยวกับ remote repository ชื่อ "origin" ให้ใช้คำสั่งต่อไปนี้

git fetch-update-server-info origin
fetch

คำสั่ง fetch ใช้สำหรับดาวน์โหลดการเปลี่ยนแปลงล่าสุดจาก remote repository

git fetch <remote>

ตัวอย่างเช่น หากต้องการดาวน์โหลดการเปลี่ยนแปลงล่าสุดจาก remote repository ชื่อ "origin" ให้ใช้คำสั่งต่อไปนี้

git fetch origin

นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร Fเช่น  fetch-all, fetch-prune, fetch-tags-all, fetch-update-shallow, fetch-update-shallow-and-prune, fetch-update-tags, fetch-update-tags-shallow, fetch-update-tags-shallow-and-prune, fetch-update-shallow-and-tags, fetch-update-shallow-and-tags-shallow, fetch-update-shallow-and-tags-shallow-and-prune, fetch-update-shallow-tags, fetch-update-shallow-tags-and-prune, fetch-update-tags-and-prune, fetch-update-tags-shallow-and-prune, fetch-update-shallow-tags-and-prune, fetch-update-shallow-and-tags-shallow, fetch-update-shallow-and-tags-shallow-and-prune, fetch-update-shallow-tags-shallow, fetch-update-shallow-tags-shallow-and-prune, fetch-update-shallow-tags-and-prune, fetch-update-shallow-tags-shallow-and-prune, fetch-update-shallow-tags-shallow-and-prune เป็นต้น

สำหรับคำสั่ง fetch-pack และ fetch-ref นั้น สามารถใช้แทนคำสั่ง git fetch ได้ แต่จะไม่ดาวน์โหลด tags มาด้วย หากต้องการดาวน์โหลด tags ด้วย ให้ใช้คำสั่ง git fetch --tags

![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/276ab9ae-e49c-4480-8ee2-d1c6e24acefd)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/f08e10bb-3041-4160-a663-9df0eeffcddc)


