# คำสั่ง git ที่ขึ้นต้นด้วยอักษร A
add : เพิ่มไฟล์เข้าไป stage เพื่อเตรียม commit
    amend : แก้ไข commit ก่อนหน้า
    annotate : ดูรายละเอียดของ commit ก่อนหน้า
    archive : สร้างไฟล์ archive ของ commit ทั้งหมด
    apply : ย้อนกลับการเปลี่ยนแปลงของ commit ก่อนหน้า
    archive : สร้างไฟล์ archive ของ commit ทั้งหมด

## รายละเอียดของคำสั่งแต่ละคำสั่งมีดังนี้
add

ใช้สำหรับเพิ่มไฟล์เข้าไป stage เพื่อเตรียม commit ไฟล์ที่เพิ่มเข้าไป stage จะอยู่ในสถานะ "staged"

git add [ไฟล์]

ตัวอย่างการใช้งาน

git add index.html

amend

ใช้สำหรับแก้ไข commit ก่อนหน้า โดยแก้ไขข้อความ commit message และเนื้อหาของ commit

git commit --amend

ตัวอย่างการใช้งาน

git commit --amend -m "แก้ไขข้อความ commit"

annotate

ใช้สำหรับดูรายละเอียดของ commit ก่อนหน้า แสดงข้อมูลเกี่ยวกับ commit message, author, committer, และเวลาในการ commit

git annotate [commit]

ตัวอย่างการใช้งาน

git annotate HEAD

archive

ใช้สำหรับสร้างไฟล์ archive ของ commit ทั้งหมด ไฟล์ archive จะเป็นไฟล์ zip หรือ tar

git archive [branch] [ไฟล์]

ตัวอย่างการใช้งาน

git archive master index.html

apply

ใช้สำหรับย้อนกลับการเปลี่ยนแปลงของ commit ก่อนหน้า คำสั่งนี้จะย้อนกลับการเปลี่ยนแปลงของไฟล์ทั้งหมดใน commit นั้น

git apply [commit]

ตัวอย่างการใช้งาน
git apply HEAD^
![image](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/dacf6999-f6df-47c4-875a-1fb1929230be)
![image](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/6b2b8166-16bf-4532-adcd-ecece514e61c)

