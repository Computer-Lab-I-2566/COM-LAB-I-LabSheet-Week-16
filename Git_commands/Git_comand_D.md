# คำสั่ง git ที่ขึ้นต้นด้วยอักษร D

    diff : แสดงความแตกต่างระหว่างสองจุดในประวัติของ Git
    fetch : ดาวน์โหลดการเปลี่ยนแปลงล่าสุดจาก remote repository
    describe : แสดงคำอธิบายของ tag ที่ใกล้เคียงที่สุด
    difftool : แสดงความแตกต่างระหว่างสองไฟล์โดยใช้เครื่องมือภายนอก
    grep : ค้นหาข้อความในไฟล์หรือในประวัติของ Git
    log : แสดงประวัติของ Git
    merge : รวมการเปลี่ยนแปลงจาก branch หนึ่งเข้ากับ branch อื่น
    reset : คืนค่าไฟล์หรือ repository ไปยังจุดก่อนหน้า
    revert : ยกเลิกการเปลี่ยนแปลงก่อนหน้า

## รายละเอียดของแต่ละคำสั่งมีดังนี้

diff

คำสั่ง diff ใช้สำหรับแสดงความแตกต่างระหว่างสองจุดในประวัติของ Git

git diff <commit_hash1> <commit_hash2>

ตัวอย่างเช่น หากต้องการแสดงความแตกต่างระหว่าง commit ที่มี hash เท่ากับ "abc123" และ commit ที่มี hash เท่ากับ "def456" ให้ใช้คำสั่งต่อไปนี้

git diff abc123 def456

หรือหากต้องการแสดงความแตกต่างระหว่างไฟล์สองไฟล์ ให้ใช้คำสั่งต่อไปนี้

git diff <file1> <file2>

fetch

คำสั่ง fetch ใช้สำหรับดาวน์โหลดการเปลี่ยนแปลงล่าสุดจาก remote repository

git fetch <remote>

ตัวอย่างเช่น หากต้องการดาวน์โหลดการเปลี่ยนแปลงล่าสุดจาก remote repository ชื่อ "origin" ให้ใช้คำสั่งต่อไปนี้

git fetch origin

describe

คำสั่ง describe ใช้สำหรับแสดงคำอธิบายของ tag ที่ใกล้เคียงที่สุด

git describe

ตัวอย่างเช่น หากมี tag ชื่อ "v1.0.0" และ repository อยู่ ณ เวอร์ชัน "v1.1.0" คำสั่ง git describe จะแสดงผลลัพธ์ดังนี้

v1.1.0-dirty

difftool

คำสั่ง difftool ใช้สำหรับแสดงความแตกต่างระหว่างสองไฟล์โดยใช้เครื่องมือภายนอก

git difftool <file1> <file2>

ตัวอย่างเช่น หากต้องการแสดงความแตกต่างระหว่างไฟล์สองไฟล์โดยใช้เครื่องมือเปรียบเทียบแบบ GUI ให้ใช้คำสั่งต่อไปนี้

git difftool -g <file1> <file2>

grep

คำสั่ง grep ใช้สำหรับค้นหาข้อความในไฟล์หรือในประวัติของ Git

git grep <pattern>

ตัวอย่างเช่น หากต้องการค้นหาข้อความ "Hello world" ในไฟล์ทั้งหมด ให้ใช้คำสั่งต่อไปนี้

git grep "Hello world"

log

คำสั่ง log ใช้สำหรับแสดงประวัติของ Git

git log

ตัวอย่างเช่น หากต้องการแสดงประวัติของ Git ตั้งแต่ commit ล่าสุดจนถึง commit แรก ให้ใช้คำสั่งต่อไปนี้

git log --oneline

merge

คำสั่ง merge ใช้สำหรับรวมการเปลี่ยนแปลงจาก branch หนึ่งเข้ากับ branch อื่น

git merge <branch_name>

ตัวอย่างเช่น หากต้องการรวมการเปลี่ยนแปลงจาก branch ชื่อ "feature" เข้ากับ branch ที่กำลังทำงานอยู่ ให้ใช้คำสั่งต่อไปนี้

git merge feature

reset

คำสั่ง reset ใช้สำหรับคืนค่าไฟล์หรือ repository ไปยังจุดก่อนหน้า

git reset <commit_hash>

ตัวอย่างเช่น หากต้องการคืนค่าไฟล์ทั้งหมดไปยังจุดก่อนหน้า commit ที่มี hash เท่ากับ "abc123" ให้ใช้คำสั่งต่อไปนี้

git reset abc123

revert

คำสั่ง revert ใช้สำหรับยกเลิกการเปลี่ยนแปลงก่อนหน้า

git revert <commit_hash>

ตัวอย่างเช่น หากต้องการยกเลิกการเปลี่ยนแปลงก่อนหน้า commit ที่มี hash เท่ากับ "abc123" ให้ใช้คำสั่งต่อไปนี้

git revert abc123

นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร D เช่น daemon, describe-branches, describe-tags, diff-tree, fetch-pack, fetch-ref, fetch-tags, fetch-update-server-info, fsck, gc, grep-reflog, grep-remotes, grep-tags, init-db, init-repository, log-tree, merge-base, merge-file, merge-tool, mergetool-choose, push, rebase, reflog, show-ref, stash, tag, update-ref เป็นต้น
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/89b1e66f-eb48-4fe5-9a75-07d67d5eee63)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/ad2445b3-83d9-4c15-8f29-c2c9fb05632f)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/c10a0e04-0220-44da-9794-15e48bbdfdfa)

