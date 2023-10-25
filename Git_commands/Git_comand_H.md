# คำสั่ง git ที่ขึ้นต้นด้วยอักษร H

    hash-object : สร้าง hash ของไฟล์หรือข้อความ
    help : แสดงความช่วยเหลือเกี่ยวกับคำสั่ง Git
    history : แสดงประวัติของ Git
   

รายละเอียดของแต่ละคำสั่งมีดังนี้

hash-object

คำสั่ง hash-object ใช้สำหรับสร้าง hash ของไฟล์หรือข้อความ

git hash-object <file>

ตัวอย่างเช่น หากต้องการสร้าง hash ของไฟล์ชื่อ README.md ให้ใช้คำสั่งต่อไปนี้

git hash-object README.md

help

คำสั่ง help ใช้สำหรับแสดงความช่วยเหลือเกี่ยวกับคำสั่ง Git

git help <command>

ตัวอย่างเช่น หากต้องการแสดงความช่วยเหลือเกี่ยวกับคำสั่ง git checkout ให้ใช้คำสั่งต่อไปนี้

git help checkout

history

คำสั่ง history ใช้สำหรับแสดงประวัติของ Git

git history

ตัวอย่างเช่น หากต้องการแสดงประวัติของ Git ตั้งแต่ commit ล่าสุดจนถึง commit แรก ให้ใช้คำสั่งต่อไปนี้

git history --oneline


คำสั่งนี้จะสร้างไฟล์ .git ในโฟลเดอร์ปัจจุบัน ซึ่งจะทำหน้าที่เป็น repository ของ Git และสร้างไฟล์ objects/pack/pack-refs.pack และ objects/info/refs ซึ่งจะทำหน้าที่เป็นฐานข้อมูลของ Git

นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร H เช่น hash-object-file, hash-object-stdin, help-commands, help-extras, help-grep, help-revisions, help-topics, help-untracked, help-update-index, help-version เป็นต้น

สำหรับคำสั่ง hash-object นั้น สามารถใช้แทนคำสั่ง sha1sum ได้
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/f33087f4-1c0d-47a7-b86d-d3555432a430)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/f89a84b6-6b58-4be0-9d55-4f8ca91c627e)


