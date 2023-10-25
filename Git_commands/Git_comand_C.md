# คำสั่ง git ที่ขึ้นต้นด้วยอักษร C
## checkout 
    เปลี่ยนไปยัง branch หรือตำแหน่งของไฟล์
## clone 
    คัดลอก repository จาก remote ไปยัง local
## cherry-pick 
    เลือก commit เฉพาะมารวมกับ commit ในปัจจุบัน
## clean 
    ลบไฟล์ที่ staging area ออก
## clone 
    คัดลอก repository จาก remote ไปยัง local
## commit 
    บันทึกการเปลี่ยนแปลงของไฟล์
## config 
    ตั้งค่า git
    
## ตัวอย่างการใช้งาน
### checkout
 git checkout master
<br>
คำสั่งนี้จะเปลี่ยนไปยัง branch master
<br>
### clone
 git clone https://github.com/my-username/my-project.git 
<br>
คำสั่งนี้จะคัดลอก repository my-project จาก GitHub ไปยัง local
<br>
### cherry-pick
 git cherry-pick 13 
<br>
คำสั่งนี้จะเลือก commit ที่มีหมายเลข 13 มารวมกับ commit ในปัจจุบัน
<br>
### clean
git clean -d -f 
<br>
คำสั่งนี้จะลบไฟล์ที่ staging area ออก รวมถึงไฟล์ที่แก้ไขแล้วที่ไม่ได้อยู่ใน staging area
<br>
### commit
git commit -m "Add new project"
<br>
คำสั่งนี้จะบันทึกการเปลี่ยนแปลงของไฟล์ด้วยข้อความอธิบาย Add new project
<br>
### config
git config user.name "thanchira65030099" /
git config user.email 65030099@kmitl.ac.th
<br>
คำสั่งนี้จะตั้งค่าชื่อผู้ใช้และอีเมลสำหรับ git
![image](https://github.com/ThanchiraCharakhon099/Git_A-Z_Mission_65030099/assets/144195708/8f803c24-b735-4f97-b629-ec269bbc4b88)

