# คำสั่ง git ที่ขึ้นต้นด้วยอักษร C

    checkout : เปลี่ยน branch หรือย้ายจาก branch หนึ่งไปอีก branch
    cherry-pick : เลือก commit เฉพาะมารวมเข้ากับ branch ที่กำลังทำงานอยู่
    clone : สร้างสำเนาของ repository ที่มีอยู่
    commit : บันทึกการเปลี่ยนแปลงทั้งหมดใน stage ไปยัง repository
    config : ตั้งค่าตัวเลือกและค่าเริ่มต้นสำหรับ Git

## รายละเอียดของแต่ละคำสั่งมีดังนี้

checkout

คำสั่ง checkout ใช้สำหรับเปลี่ยน branch หรือย้ายจาก branch หนึ่งไปอีก branch

git checkout <branch_name>

ตัวอย่างเช่น หากต้องการเปลี่ยนเป็น branch ชื่อ "master" ให้ใช้คำสั่งต่อไปนี้

git checkout master

หรือหากต้องการย้ายจาก branch ชื่อ "feature" ไปยัง branch ชื่อ "master" ให้ใช้คำสั่งต่อไปนี้

git checkout master -- <feature>

cherry-pick

คำสั่ง cherry-pick ใช้สำหรับเลือก commit เฉพาะมารวมเข้ากับ branch ที่กำลังทำงานอยู่

git cherry-pick <commit_hash>

ตัวอย่างเช่น หากต้องการเลือก commit ที่มี hash เท่ากับ "abc123" มารวมเข้ากับ branch ที่กำลังทำงานอยู่ ให้ใช้คำสั่งต่อไปนี้

git cherry-pick abc123

clone

คำสั่ง clone ใช้สำหรับสร้างสำเนาของ repository ที่มีอยู่

git clone <url>

ตัวอย่างเช่น หากต้องการสร้างสำเนาของ repository ชื่อ "my-repo" ที่อยู่บน GitHub ให้ใช้คำสั่งต่อไปนี้

git clone https://github.com/my-username/my-repo.git

commit

คำสั่ง commit ใช้สำหรับบันทึกการเปลี่ยนแปลงทั้งหมดใน stage ไปยัง repository

git commit -m <message>

ตัวอย่างเช่น หากต้องการบันทึกการเปลี่ยนแปลงทั้งหมดใน stage พร้อมข้อความอธิบายว่าการเปลี่ยนแปลงนั้นคืออะไร ให้ใช้คำสั่งต่อไปนี้

git commit -m "Add new feature"

config

คำสั่ง config ใช้สำหรับตั้งค่าตัวเลือกและค่าเริ่มต้นสำหรับ Git

git config <option> <value>

ตัวอย่างเช่น หากต้องการตั้งค่าชื่อผู้ใช้สำหรับ Git ให้ใช้คำสั่งต่อไปนี้

git config user.name "Your Name"

หรือหากต้องการตั้งค่าอีเมลสำหรับ Git ให้ใช้คำสั่งต่อไปนี้

git config user.email "your-email@example.com"

## นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร C เช่น clean, clone-tool, commit-graph, commit-message, commit-patch, commit-tree, describe, diff, fetch, grep, hash-object, init, merge, merge-base, merge-file, merge-tool, mergetool-choose, pull, remote, reset, revert, show-ref, stash, tag, update-index, worktree เป็นต้น

![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/367cb3cd-1bce-417a-8e7a-c433efa95214)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/b60cf692-daed-4d78-abd8-097b4c3a4858)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/0d70c392-955f-4bcb-9c33-dbdc38206fdb)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/6105eb03-a2fe-4259-b4aa-2b0e23146398)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/42b2392a-ccd7-4fd1-8ae5-10f863fd45f5)

