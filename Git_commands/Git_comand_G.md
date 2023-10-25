# คำสั่ง git ที่ขึ้นต้นด้วยอักษร G

    grep : ค้นหาข้อความในไฟล์หรือในประวัติของ Git
    git-gui : อินเทอร์เฟซผู้ใช้แบบ GUI สำหรับ Git
    gitk : อินเทอร์เฟซผู้ใช้แบบ GUI สำหรับ Git
    git-receive-pack : รับการเปลี่ยนแปลงจาก remote repository
    git-shell : รันคำสั่ง Git ผ่านเชลล์อื่น
    git-upload-pack : อัปโหลดการเปลี่ยนแปลงไปยัง remote repository

รายละเอียดของแต่ละคำสั่งมีดังนี้

grep

คำสั่ง grep ใช้สำหรับค้นหาข้อความในไฟล์หรือในประวัติของ Git

git grep <pattern>

ตัวอย่างเช่น หากต้องการค้นหาข้อความ "Hello world" ในไฟล์ทั้งหมด ให้ใช้คำสั่งต่อไปนี้

git grep "Hello world"

git-gui

คำสั่ง git-gui ใช้สำหรับเปิดอินเทอร์เฟซผู้ใช้แบบ GUI สำหรับ Git

git gui

gitk

คำสั่ง gitk ใช้สำหรับเปิดอินเทอร์เฟซผู้ใช้แบบ GUI สำหรับ Git

gitk

git-receive-pack

คำสั่ง git-receive-pack ใช้สำหรับรับการเปลี่ยนแปลงจาก remote repository

git-receive-pack <port>

ตัวอย่างเช่น หากต้องการรับการเปลี่ยนแปลงจาก remote repository ผ่านพอร์ต 2222 ให้ใช้คำสั่งต่อไปนี้

git-receive-pack 2222

git-shell

คำสั่ง git-shell ใช้สำหรับรันคำสั่ง Git ผ่านเชลล์อื่น

git shell

git-upload-pack

คำสั่ง git-upload-pack ใช้สำหรับอัปโหลดการเปลี่ยนแปลงไปยัง remote repository

git-upload-pack <port>

ตัวอย่างเช่น หากต้องการอัปโหลดการเปลี่ยนแปลงไปยัง remote repository ผ่านพอร์ต 2222 ให้ใช้คำสั่งต่อไปนี้

git-upload-pack 2222

นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร G เช่น gc, grep-reflog, grep-remotes, grep-tags, init-db, init-repository, log-tree, merge-base, merge-file, merge-tool, mergetool-choose, push, rebase, reflog, show-ref, stash, tag, update-ref, worktree เป็นต้น

สำหรับคำสั่ง git-gui และ gitk นั้น สามารถใช้แทนกันได้ แต่ git-gui มีฟังก์ชันการทำงานมากกว่า gitk
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/d620e17f-0f49-4d80-a8a5-9594a18e391d)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/c588dd5f-c1e9-4e02-9640-12e4bb4c2950)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/91c556c7-2671-4956-a11f-29ba262c2f6b)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/d873571d-9557-4bcb-ad1b-b9077e87a869)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/11bbe3e1-e79a-42c7-a753-5ccf478aeeac)
