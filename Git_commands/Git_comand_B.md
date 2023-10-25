# คำสั่ง git ที่ขึ้นต้นด้วยอักษร B
 branch : สร้างหรือเปลี่ยน branch
    bisect : ค้นหา commit ที่ทำให้เกิดปัญหา
    blame : ดูประวัติการแก้ไขของไฟล์
    branch

## รายละเอียดของคำสั่งแต่ละคำสั่งมีดังนี้

branch

ใช้สำหรับสร้างหรือเปลี่ยน branch คำสั่งนี้จะสร้าง branch ใหม่ขึ้นมา หรือเปลี่ยนการทำงานไปที่ branch อื่น

git branch [ชื่อสาขา]
![image](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/88e1c3f4-a844-409d-8041-1c196cd1bbf3)

ตัวอย่างการใช้งาน

git branch master
bisect

![image](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/6373bda2-d853-4574-af7a-8444d09d93ce)

ใช้สำหรับค้นหา commit ที่ทำให้เกิดปัญหา คำสั่งนี้จะแบ่งประวัติของ repository ออกเป็นสองส่วน แล้วทำการทดสอบ commit ในแต่ละส่วนจนกว่าจะพบ commit ที่ทำให้เกิดปัญหา

git bisect start [commit-bad] [commit-good]

ตัวอย่างการใช้งาน

git bisect start HEAD^ HEAD

blame

ใช้สำหรับดูประวัติการแก้ไขของไฟล์ คำสั่งนี้จะแสดงข้อมูลเกี่ยวกับผู้แก้ไขและเวลาในการแก้ไขแต่ละบรรทัด

git blame [ไฟล์]

ตัวอย่างการใช้งาน

git blame index.html

branch

คำสั่ง branch เป็นคำสั่งพื้นฐานของ Git ที่ใช้สำหรับสร้างหรือเปลี่ยน branch คำสั่งนี้สามารถสร้าง branch ใหม่ขึ้นมา หรือเปลี่ยนการทำงานไปที่ branch อื่น

git branch [ชื่อสาขา]

ตัวอย่างการใช้งาน

git branch master

คำสั่ง branch สามารถใช้ร่วมกับคำสั่ง checkout เพื่อเปลี่ยนการทำงานไปที่ branch อื่นได้

git checkout [ชื่อสาขา]

ตัวอย่างการใช้งาน

git checkout master

คำสั่ง branch ยังสามารถใช้ในการตรวจสอบว่า branch ใดมีการเปลี่ยนแปลงล่าสุดได้

git branch -vv

ตัวอย่างการใช้งาน

* master  321456789abcdef (HEAD -> origin/master, origin/HEAD)
   * feature  321456789abcdef (origin/feature)
   * bugfix   321456789abcdef (origin/bugfix)

คำสั่ง branch เป็นคำสั่งที่มีประโยชน์ในการติดตามการทำงานบนโครงการขนาดใหญ่ที่มีหลายสาขา
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/a5791ce6-accf-4847-8d63-d7d51520bd22)
![ภาพ](https://github.com/AnchisaPhetnoi/Git_A-Z_Mission_65030289/assets/144197034/2c3c9393-cbcb-4159-ad14-7339f3440f2d)

