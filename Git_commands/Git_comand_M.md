# คำสั่ง git ที่ขึ้นต้นด้วยอักษร M

    merge : รวมการเปลี่ยนแปลงจากสาขาหนึ่งไปยังอีกสาขาหนึ่ง
    merge-base : หาจุดร่วมของสอง branch
    merge-file : รวมการเปลี่ยนแปลงจากไฟล์หนึ่งไปยังอีกไฟล์หนึ่ง
    merge-tool : เลือกเครื่องมือสำหรับรวมการเปลี่ยนแปลง
    mergetool-choose : เลือกเครื่องมือสำหรับรวมการเปลี่ยนแปลง
    message : ตั้งค่าข้อความสำหรับ commit
    merge-subtree : รวมการเปลี่ยนแปลงจากสาขาหนึ่งไปยังอีกสาขาหนึ่งในรูปแบบ subtree
    merge-subtree-filter : กรองการเปลี่ยนแปลงจากสาขาหนึ่งไปยังอีกสาขาหนึ่งในรูปแบบ subtree
    merge-subtree-update : อัปเดตการเปลี่ยนแปลงจากสาขาหนึ่งไปยังอีกสาขาหนึ่งในรูปแบบ subtree

รายละเอียดของแต่ละคำสั่งมีดังนี้

merge

คำสั่ง merge ใช้สำหรับรวมการเปลี่ยนแปลงจากสาขาหนึ่งไปยังอีกสาขาหนึ่ง

git merge <branch>

ตัวอย่างเช่น หากต้องการรวมการเปลี่ยนแปลงจากสาขาชื่อ "feature" ไปยังสาขาชื่อ "master" ให้ใช้คำสั่งต่อไปนี้

git merge feature

merge-base

คำสั่ง merge-base ใช้สำหรับหาจุดร่วมของสอง branch

git merge-base <branch1> <branch2>

ตัวอย่างเช่น หากต้องการหาจุดร่วมของสาขาชื่อ "master" และ "feature" ให้ใช้คำสั่งต่อไปนี้

git merge-base master feature

merge-file

คำสั่ง merge-file ใช้สำหรับรวมการเปลี่ยนแปลงจากไฟล์หนึ่งไปยังอีกไฟล์หนึ่ง

git merge-file <file1> <file2>

ตัวอย่างเช่น หากต้องการรวมการเปลี่ยนแปลงจากไฟล์ชื่อ "README.md" ไปยังไฟล์ชื่อ "LICENSE" ให้ใช้คำสั่งต่อไปนี้

git merge-file README.md LICENSE

merge-tool

คำสั่ง merge-tool ใช้สำหรับเลือกเครื่องมือสำหรับรวมการเปลี่ยนแปลง

git merge-tool

คำสั่งนี้จะเปิดเครื่องมือสำหรับรวมการเปลี่ยนแปลง ซึ่งจะขึ้นอยู่กับการตั้งค่าของ Git

mergetool-choose

คำสั่ง mergetool-choose ใช้สำหรับเลือกเครื่องมือสำหรับรวมการเปลี่ยนแปลง

git mergetool-choose

คำสั่งนี้จะเปิดอินเทอร์เฟซผู้ใช้แบบ GUI สำหรับเลือกเครื่องมือสำหรับรวมการเปลี่ยนแปลง

message

คำสั่ง message ใช้สำหรับตั้งค่าข้อความสำหรับ commit

git message <message>

ตัวอย่างเช่น หากต้องการตั้งค่าข้อความสำหรับ commit ใหม่ ให้ใช้คำสั่งต่อไปนี้

git message "This is a new commit."

merge-subtree

คำสั่ง merge-subtree ใช้สำหรับรวมการเปลี่ยนแปลงจากสาขาหนึ่งไปยังอีกสาขาหนึ่งในรูปแบบ subtree

git merge-subtree <subtree-ref> <target-ref>

ตัวอย่างเช่น หากต้องการรวมการเปลี่ยนแปลงจากสาขาชื่อ "subtree" ไปยังสาขาชื่อ "master" ให้ใช้คำสั่งต่อไปนี้

git merge-subtree subtree master

merge-subtree-filter

คำสั่ง merge-subtree-filter ใช้สำหรับกรองการเปลี่ยนแปลงจากสาขาหนึ่งไปยังอีกสาขาหนึ่งในรูปแบบ subtree

git merge-subtree-filter <subtree-ref> <target-ref> <filter-expression>

ตัวอย่างเช่น หากต้องการรวมการเปลี่ยนแปลงจากสาขาชื่อ "subtree" ไปยังสาขาชื่อ "master" และลบไฟล์ชื่อ ".gitignore" ให้ใช้คำสั่งต่อไปนี้

git merge-subtree-filter subtree master -x .gitignore

merge-subtree-update

คำสั่ง merge-subtree-update ใช้สำหรับอัปเดตการเปลี่ยนแปลงจากสาขาหนึ่งไปยังอีกสาขาหนึ่งในรูปแบบ subtree

git merge-s
ubtree-update <subtree-ref> <target-ref>

ตัวอย่างเช่น หากต้องการอัปเดตการเปลี่ยนแปลงจากสาขาชื่อ "subtree" ไปยังสาขาชื่อ "master" ให้ใช้คำสั่งต่อไปนี้

git merge-subtree-update subtree master

นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร M เช่น merge-submodule, merge-submodule-branch, merge-submodule-update, merge-subtree-filter-index, merge-subtree-filter-tree, merge-subtree-update-index, merge-subtree-update-tree เป็นต้น

สำหรับคำสั่ง merge และ merge-file นั้น สามารถใช้แทนกันได้ แต่ merge จะรวมการเปลี่ยนแปลงจากสาขาหนึ่งไปยังอีกสาขาหนึ่งโดยอัตโนมัติ ในขณะที่ merge-file จะรวมการเปลี่ยนแปลงจากไฟล์หนึ่งไปยังอีกไฟล์หนึ่งเท่านั้น
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/3b8012ce-e40b-4c89-826f-fc2f205d313e)

![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/edbaf965-6181-4774-8a2f-dec341af4606)

