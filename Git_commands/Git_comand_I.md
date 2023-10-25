# คำสั่ง git ที่ขึ้นต้นด้วยอักษร I

    init : สร้าง repository ใหม่
    init-db : สร้างฐานข้อมูล Git
    init-repository : สร้าง repository ใหม่
    import-tree : นำเข้าไฟล์หรือไดเร็กทอรีไปยัง Git
    index-pack : สร้าง packfile จาก index
    init-db-bare : สร้างฐานข้อมูล Git แบบเปล่า

รายละเอียดของแต่ละคำสั่งมีดังนี้

init

คำสั่ง init ใช้สำหรับสร้าง repository ใหม่

git init

คำสั่งนี้จะสร้างไฟล์ .git ในโฟลเดอร์ปัจจุบัน ซึ่งจะทำหน้าที่เป็น repository ของ Git

init-db

คำสั่ง init-db ใช้สำหรับสร้างฐานข้อมูล Git

git init-db

คำสั่งนี้จะสร้างไฟล์ objects/pack/pack-refs.pack และ objects/info/refs ซึ่งจะทำหน้าที่เป็นฐานข้อมูลของ Git

init-repository

คำสั่ง init-repository ใช้สำหรับสร้าง repository ใหม่

git init-repository

คำสั่งนี้จะสร้างไฟล์ .git ในโฟลเดอร์ปัจจุบัน ซึ่งจะทำหน้าที่เป็น repository ของ Git และสร้างไฟล์ objects/pack/pack-refs.pack และ objects/info/refs ซึ่งจะทำหน้าที่เป็นฐานข้อมูลของ Git

import-tree

คำสั่ง import-tree ใช้สำหรับนำเข้าไฟล์หรือไดเร็กทอรีไปยัง Git

git import-tree <tree-ish>

ตัวอย่างเช่น หากต้องการนำเข้าไฟล์ชื่อ README.md ไปยัง Git ให้ใช้คำสั่งต่อไปนี้

git import-tree README.md

index-pack

คำสั่ง index-pack ใช้สำหรับสร้าง packfile จาก index

git index-pack

คำสั่งนี้จะสร้าง packfile ใหม่จาก index ของ Git

init-db-bare

คำสั่ง init-db-bare ใช้สำหรับสร้างฐานข้อมูล Git แบบเปล่า

git init-db-bare

คำสั่งนี้จะสร้างไฟล์ objects/pack/pack-refs.pack และ objects/info/refs ซึ่งจะทำหน้าที่เป็นฐานข้อมูลของ Git แต่จะไม่สร้างไฟล์ .git

นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร I เช่น ignore, import-ignore, import-submodule, init-db-fsck, init-db-shared, init-db-transactional, init-repository-bare เป็นต้น

สำหรับคำสั่ง init นั้น สามารถใช้แทนคำสั่ง git init-repository ได้

![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/0af2fb57-9da9-443a-a516-a85a8bc29c00)


