# คำสั่ง git ที่ขึ้นต้นด้วยอักษร R

    rebase : รวมการเปลี่ยนแปลงจากสาขาหนึ่งไปยังอีกสาขาหนึ่ง
    reset : ยกเลิกการเปลี่ยนแปลง
    revert : ย้อนกลับการเปลี่ยนแปลง
    rerere : จัดการการแก้ไขซ้ำ
    rebase-merge : รวมการเปลี่ยนแปลงจากสาขาหนึ่งไปยังอีกสาขาหนึ่งโดยใช้เครื่องมือ merge
    rebase-subtree : รวมการเปลี่ยนแปลงจากสาขาหนึ่งไปยังอีกสาขาหนึ่งในรูปแบบ subtree

รายละเอียดของแต่ละคำสั่งมีดังนี้

rebase

คำสั่ง rebase ใช้สำหรับรวมการเปลี่ยนแปลงจากสาขาหนึ่งไปยังอีกสาขาหนึ่ง

git rebase <source-branch> <target-branch>

ตัวอย่างเช่น หากต้องการรวมการเปลี่ยนแปลงจากสาขาชื่อ "feature" ไปยังสาขาชื่อ "master" ให้ใช้คำสั่งต่อไปนี้

git rebase feature master

reset

คำสั่ง reset ใช้สำหรับยกเลิกการเปลี่ยนแปลง

git reset <commit-hash>

ตัวอย่างเช่น หากต้องการยกเลิกการเปลี่ยนแปลงทั้งหมดจาก commit ที่มี hash เท่ากับ "abc123" ให้ใช้คำสั่งต่อไปนี้

git reset abc123

revert

คำสั่ง revert ใช้สำหรับย้อนกลับการเปลี่ยนแปลง

git revert <commit-hash>

ตัวอย่างเช่น หากต้องการย้อนกลับการเปลี่ยนแปลงทั้งหมดจาก commit ที่มี hash เท่ากับ "abc123" ให้ใช้คำสั่งต่อไปนี้

git revert abc123

rerere

คำสั่ง rerere ใช้สำหรับจัดการการแก้ไขซ้ำ

git rerere

คำสั่งนี้จะเปิดใช้งานการแก้ไขซ้ำ ซึ่งจะช่วยให้ Git จำการแก้ไขที่ซ้ำกันเพื่อให้สามารถรวมการเปลี่ยนแปลงได้เร็วขึ้น

rebase-merge

คำสั่ง rebase-merge ใช้สำหรับรวมการเปลี่ยนแปลงจากสาขาหนึ่งไปยังอีกสาขาหนึ่งโดยใช้เครื่องมือ merge

git rebase-merge <source-branch> <target-branch>

ตัวอย่างเช่น หากต้องการรวมการเปลี่ยนแปลงจากสาขาชื่อ "feature" ไปยังสาขาชื่อ "master" โดยใช้เครื่องมือ merge ให้ใช้คำสั่งต่อไปนี้

git rebase-merge feature master

rebase-subtree

คำสั่ง rebase-subtree ใช้สำหรับรวมการเปลี่ยนแปลงจากสาขาหนึ่งไปยังอีกสาขาหนึ่งในรูปแบบ subtree

git rebase-subtree <subtree-ref> <target-ref>

ตัวอย่างเช่น หากต้องการรวมการเปลี่ยนแปลงจากสาขาชื่อ "subtree" ไปยังสาขาชื่อ "master" ให้ใช้คำสั่งต่อไปนี้

git rebase-subtree subtree master

นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร R เช่น rebase-apply, rebase-interactive, rebase-merge-check, rebase-merge-continue, rebase-merge-abort, rebase-merge-skip, rebase-update, rerere-clear, rerere-resolved, rerere-update เป็นต้น

สำหรับคำสั่ง rebase นั้น สามารถใช้แทนคำสั่ง merge ได้ แต่ rebase จะรวมการเปลี่ยนแปลงจากสาขาหนึ่งไปยังอีกสาขาหนึ่งโดยอัตโนมัติ ในขณะที่ merge จะรวมการเปลี่ยนแปลงจากสาขาหนึ่งไปยังอีกสาขาหนึ่งโดยใช้เครื่องมือ merge ซึ่งอาจทำให้เกิดความซับซ้อนมากขึ้น
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/e8b4f4d9-922d-41bd-b094-f1fe81dc1fd3)
