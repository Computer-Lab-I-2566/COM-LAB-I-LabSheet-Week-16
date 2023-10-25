# คำสั่ง git ที่ขึ้นต้นด้วยอักษร S

    stash : เก็บการเปลี่ยนแปลงชั่วคราว
    show : แสดงข้อมูลเกี่ยวกับ commit
    status : แสดงสถานะของ repository
    stage : เพิ่มไฟล์ไปยัง staging area
    stash-apply : คืนค่าการเปลี่ยนแปลงชั่วคราว
    stash-list : แสดงรายการการเปลี่ยนแปลงชั่วคราว
    stash-pop : ลบการเปลี่ยนแปลงชั่วคราว
    stash-save : บันทึกการเปลี่ยนแปลงชั่วคราว
    stash-show : แสดงรายละเอียดการเปลี่ยนแปลงชั่วคราว
    submodule : จัดการ submodule

รายละเอียดของแต่ละคำสั่งมีดังนี้

stash

คำสั่ง stash ใช้สำหรับเก็บการเปลี่ยนแปลงชั่วคราว

git stash

คำสั่งนี้จะเก็บการเปลี่ยนแปลงทั้งหมดที่ไม่ได้ commit ไว้ใน staging area ชั่วคราว ซึ่งสามารถใช้เพื่อย้อนกลับการเปลี่ยนแปลงได้

show

คำสั่ง show ใช้สำหรับแสดงข้อมูลเกี่ยวกับ commit

git show <commit-hash>

ตัวอย่างเช่น หากต้องการแสดงข้อมูลเกี่ยวกับ commit ที่มี hash เท่ากับ "abc123" ให้ใช้คำสั่งต่อไปนี้

git show abc123

status

คำสั่ง status ใช้สำหรับแสดงสถานะของ repository

git status

คำสั่งนี้จะแสดงสถานะของไฟล์ทั้งหมดใน repository ว่ามีการเปลี่ยนแปลงหรือไม่

stage

คำสั่ง stage ใช้สำหรับเพิ่มไฟล์ไปยัง staging area

git stage <file>

ตัวอย่างเช่น หากต้องการเพิ่มไฟล์ชื่อ "README.md" ไปยัง staging area ให้ใช้คำสั่งต่อไปนี้

git stage README.md

stash-apply

คำสั่ง stash-apply ใช้สำหรับคืนค่าการเปลี่ยนแปลงชั่วคราว

git stash apply

คำสั่งนี้จะคืนค่าการเปลี่ยนแปลงชั่วคราวล่าสุดไปยัง working directory

stash-list

คำสั่ง stash-list ใช้สำหรับแสดงรายการการเปลี่ยนแปลงชั่วคราว

git stash list

คำสั่งนี้จะแสดงรายการการเปลี่ยนแปลงชั่วคราวทั้งหมด

stash-pop

คำสั่ง stash-pop ใช้สำหรับลบการเปลี่ยนแปลงชั่วคราว

git stash pop

คำสั่งนี้จะลบการเปลี่ยนแปลงชั่วคราวล่าสุดและคืนค่าไปยัง working directory

stash-save

คำสั่ง stash-save ใช้สำหรับบันทึกการเปลี่ยนแปลงชั่วคราว

git stash save <message>

คำสั่งนี้จะบันทึกการเปลี่ยนแปลงชั่วคราวและตั้งชื่อเป็นข้อความที่กำหนด

stash-show

คำสั่ง stash-show ใช้สำหรับแสดงรายละเอียดการเปลี่ยนแปลงชั่วคราว

git stash show <stash-ref>

ตัวอย่างเช่น หากต้องการแสดงรายละเอียดการเปลี่ยนแปลงชั่วคราวที่มีชื่อ "my-stash" ให้ใช้คำสั่งต่อไปนี้

git stash show my-stash

submodule

คำสั่ง submodule ใช้สำหรับจัดการ submodule

git submodule <command>

ตัวอย่างเช่น หากต้องการแสดงรายการ submodule ทั้งหมด ให้ใช้คำสั่งต่อไปนี้

git submodule list

นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร S เช่น stash-branch, stash-create, stash-drop, stash-forget, stash-pull, stash-save-patch, stash-split, stash-unstage, show-branch, show-ref, show-stash เป็นต้น

สำหรับคำสั่ง stash นั้น สามารถใช้แทนคำสั่ง save ได้ แต่ stash จะเก็บการเปลี่ยนแปลงทั้งหมดที่ไม่ได้ commit ไว้ใน staging area ชั่วคราว ในขณะที่ save จะเก็บการเปลี่ยนแปลงทั้งหมดที่ไม่ได้ commit ไว้ใน commit ใหม่
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/94e7c79e-2f9a-4da5-9134-121ff7e8fc63)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/b2a489e1-97f4-4d35-93d8-e0b2833a9472)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/fb03a40f-cfab-49d6-b29f-cad8bcaa1da1)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/03eded49-bb0d-4a60-a338-8a1dabd28a68)

