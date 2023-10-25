# คำสั่ง git ที่ขึ้นต้นด้วยอักษร Z

    zgrep : ค้นหาข้อความในไฟล์ที่เก็บ Git

รายละเอียดของแต่ละคำสั่งมีดังนี้

zgrep

คำสั่ง zgrep ใช้สำหรับค้นหาข้อความในไฟล์ที่เก็บ Git

git zgrep <pattern> <file>

ตัวอย่างเช่น หากต้องการค้นหาข้อความ "Hello, world!" ในไฟล์ชื่อ "README.md" ให้ใช้คำสั่งต่อไปนี้

git zgrep "Hello, world!" README.md

นอกจากคำสั่งเหล่านี้แล้ว ยังมีคำสั่งอื่นๆ ที่ขึ้นต้นด้วยอักษร Z เช่น zgrep-all, zgrep-before, zgrep-after, zgrep-count, zgrep-extended, zgrep-fixed-strings, zgrep-ignore-case, zgrep-invert-match, zgrep-line-number, zgrep-no-filename, zgrep-only-matching, zgrep-print0, zgrep-quiet, zgrep-recursive, zgrep-skip, zgrep-word-regexp เป็นต้น

สำหรับคำสั่ง zgrep นั้น สามารถใช้แทนคำสั่ง grep ได้ แต่ zgrep จะค้นหาข้อความในไฟล์ที่เก็บ Git ในขณะที่ grep จะค้นหาข้อความในไฟล์ธรรมดา

ตัวอย่างการใช้งานคำสั่ง zgrep
ค้นหาข้อความ "Hello, world!" ในไฟล์ชื่อ "README.md"

git zgrep "Hello, world!" README.md
ค้นหาข้อความ "Hello, world!" ในไฟล์ทั้งหมดในไดเร็กทอรีปัจจุบัน

git zgrep "Hello, world!" .
ค้นหาข้อความ "Hello, world!" ในไฟล์ทั้งหมดในไดเร็กทอรีปัจจุบันและย่อย

git zgrep "Hello, world!" --recursive .

คำสั่ง zgrep เป็นคำสั่งที่มีประโยชน์สำหรับการค้นหาข้อความในไฟล์ที่เก็บ Git
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/2daa04c2-3c3b-4e32-8357-d7c45fde436d)
