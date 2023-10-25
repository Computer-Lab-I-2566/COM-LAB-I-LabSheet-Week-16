# คำสั่ง git ที่ขึ้นต้นด้วยอักษร T

    tag : สร้างแท็ก
    tag-create : สร้างแท็ก
    tag-list : แสดงรายการแท็ก
    tag-name-filter : กรองรายการแท็กตามชื่อ
    tag-remove : ลบแท็ก
    tag-rename : เปลี่ยนชื่อแท็ก
    tag-verify : ตรวจสอบความถูกต้องของแท็ก

รายละเอียดของแต่ละคำสั่งมีดังนี้

tag

คำสั่ง tag ใช้สำหรับสร้างแท็ก

git tag <tag-name>

ตัวอย่างเช่น หากต้องการสร้างแท็กชื่อ "v1.0.0" ให้ใช้คำสั่งต่อไปนี้

git tag v1.0.0

tag-create

คำสั่ง tag-create ใช้สำหรับสร้างแท็ก

git tag-create <tag-name> <commit-hash>

ตัวอย่างเช่น หากต้องการสร้างแท็กชื่อ "v1.0.0" สำหรับ commit ที่มี hash เท่ากับ "abc123" ให้ใช้คำสั่งต่อไปนี้

git tag-create v1.0.0 abc123

tag-list

คำสั่ง tag-list ใช้สำหรับแสดงรายการแท็ก

git tag-list

คำสั่งนี้จะแสดงรายการแท็กทั้งหมด

tag-name-filter

คำสั่ง tag-name-filter ใช้สำหรับกรองรายการแท็กตามชื่อ

git tag-name-filter <pattern>

ตัวอย่างเช่น หากต้องการแสดงรายการแท็กที่เริ่มต้นด้วยตัวอักษร "v" ให้ใช้คำสั่งต่อไปนี้

git tag-name-filter v

tag-remove

คำสั่ง tag-remove ใช้สำหรับลบแท็ก

git tag-remove <tag-name>

ตัวอย่างเช่น หากต้องการลบแท็กชื่อ "v1.0.0" ให้ใช้คำสั่งต่อไปนี้

git tag-remove v1.0.0

tag-rename

คำสั่ง tag-rename ใช้สำหรับเปลี่ยนชื่อแท็ก

git tag-rename <old-tag-name> <new-tag-name>

ตัวอย่างเช่น หากต้องการเปลี่ยนชื่อแท็กชื่อ "v1.0.0" เป็น "v2.0.0" ให้ใช้คำสั่งต่อไปนี้

git tag-rename v1.0.0 v2.0.0

tag-verify

คำสั่ง tag-verify ใช้สำหรับตรวจสอบความถูกต้องของแท็ก

git tag-verify <tag-name>

ตัวอย่างเช่น หากต้องการตรวจสอบความถูกต้องของแท็กชื่อ "v1.0.0" ให้ใช้คำสั่งต่อไปนี้

git tag-verify v1.0.0

นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร T เช่น tag-annotate, tag-bump, tag-edit, tag-fetch, tag-merge, tag-push, tag-show, tag-shallow, tag-sign, tag-submodule, tag-untag เป็นต้น

สำหรับคำสั่ง tag และ tag-create นั้น สามารถใช้แทนกันได้ แต่ tag จะสร้างแท็กโดยใช้ commit ล่าสุด ในขณะที่ tag-create จะสร้างแท็กโดยใช้ commit ที่ระบุ

ตัวอย่างการใช้งานคำสั่ง tag
สร้างแท็กชื่อ "v1.0.0"

git tag v1.0.0
สร้างแท็กชื่อ "v1.0.0" สำหรับ commit ที่มี hash เท่ากับ "abc123"

git tag v1.0.0 abc123
แสดงรายการแท็กทั้งหมด

git tag-list
แสดงรายการแท็กที่เริ่มต้นด้วยตัวอักษร "v"

git tag-name-filter v
ลบแท็กชื่อ "v1.0.0"

git tag-remove v1.0.0
เปลี่ยนชื่อแท็กชื่อ "v1.0.0" เป็น "v2.0.0"

git tag-rename v1.0.0 v2.0.0
ตรวจสอบความถูกต้องของแท็กชื่อ "v1.0.0"

git tag-verify v1.0.0
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/41bf7bc7-b72d-41f8-a34f-b67d43556165)
![list-tags-with-description](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/e8a2bbeb-db20-4459-b63b-7432ee89397c)
![ไม่มีชื่อ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/1644242a-6662-454f-aa29-67863a7281fc)
![1623994663-103268](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/53ccaebb-2c43-4b5a-a788-e071ef532b3b)
