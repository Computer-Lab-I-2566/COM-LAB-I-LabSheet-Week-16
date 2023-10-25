# คำสั่ง git ที่ขึ้นต้นด้วยอักษร U

    unstage : ยกเลิกการเพิ่มไฟล์ไปยัง staging area
    update-index : อัปเดตสถานะของไฟล์ใน staging area
    update-ref : อัปเดตค่าของ ref
    unpack-file : แยกไฟล์ออกจาก commit

รายละเอียดของแต่ละคำสั่งมีดังนี้

unstage

คำสั่ง unstage ใช้สำหรับยกเลิกการเพิ่มไฟล์ไปยัง staging area

git unstage <file>

ตัวอย่างเช่น หากต้องการยกเลิกการเพิ่มไฟล์ชื่อ "README.md" ไปยัง staging area ให้ใช้คำสั่งต่อไปนี้

git unstage README.md

update-index

คำสั่ง update-index ใช้สำหรับอัปเดตสถานะของไฟล์ใน staging area

git update-index <file>

ตัวอย่างเช่น หากต้องการอัปเดตสถานะของไฟล์ชื่อ "README.md" ใน staging area ให้ใช้คำสั่งต่อไปนี้

git update-index README.md

update-ref

คำสั่ง update-ref ใช้สำหรับอัปเดตค่าของ ref

git update-ref <ref> <new-value>

ตัวอย่างเช่น หากต้องการอัปเดตค่าของ ref ชื่อ "HEAD" เป็น commit ที่มี hash เท่ากับ "abc123" ให้ใช้คำสั่งต่อไปนี้

git update-ref HEAD abc123

unpack-file

คำสั่ง unpack-file ใช้สำหรับแยกไฟล์ออกจาก commit

git unpack-file <commit-hash> <file>

ตัวอย่างเช่น หากต้องการแยกไฟล์ชื่อ "README.md" ออกจาก commit ที่มี hash เท่ากับ "abc123" ให้ใช้คำสั่งต่อไปนี้

git unpack-file abc123 README.md

นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร U เช่น unpack-objects, update-shallow, update-submodule-index, update-submodule-summary เป็นต้น

สำหรับคำสั่ง update-index นั้น สามารถใช้แทนคำสั่ง add ได้ แต่ update-index จะอัปเดตสถานะของไฟล์ใน staging area ในขณะที่ add จะเพิ่มไฟล์ไปยัง staging area โดยไม่อัปเดตสถานะ

ตัวอย่างการใช้งานคำสั่ง unstage
เพิ่มไฟล์ชื่อ "README.md" ไปยัง staging area

git add README.md
แสดงสถานะของไฟล์ใน staging area

git status
ยกเลิกการเพิ่มไฟล์ชื่อ "README.md" ไปยัง staging area

git unstage README.md
แสดงสถานะของไฟล์ใน staging area

git status

ตัวอย่างการใช้งานคำสั่ง update-index

# เปลี่ยนเนื้อหาของไฟล์ชื่อ "README.md"
echo "This is a new README" > README.md

# แสดงสถานะของไฟล์ใน staging area
git status

# อัปเดตสถานะของไฟล์ชื่อ "README.md" ใน staging area
git update-index README.md

# แสดงสถานะของไฟล์ใน staging area
git status

ตัวอย่างการใช้งานคำสั่ง update-ref
แสดงค่าของ ref ชื่อ "HEAD"

git rev-parse HEAD
อัปเดตค่าของ ref ชื่อ "HEAD" เป็น commit ที่มี hash เท่ากับ "abc123"

git update-ref HEAD abc123
แสดงค่าของ ref ชื่อ "HEAD"

git rev-parse HEAD

ตัวอย่างการใช้งานคำสั่ง unpack-file
แสดงเนื้อหาของไฟล์ชื่อ "README.md" ใน commit ที่มี hash เท่ากับ "abc123"

git show abc123:README.md
แยกไฟล์ชื่อ "README.md" ออกจาก commit ที่มี hash เท่ากับ "abc123"

git unpack-file abc123 README.md
แสดงเนื้อหาของไฟล์ชื่อ "README.md"


![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/2e8d40e5-ca69-4eb8-baac-8ae53ef00405)
