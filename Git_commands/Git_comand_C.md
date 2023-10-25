# คำสั่ง git ที่ขึ้นต้นด้วยอักษร C
## git commit
ยืนยันการเปลี่ยนแปลงไฟล์ที่ถูก add ลงใน stage โดยสามารถใส่ comment โดยการเติม -m ด้านหลัง
### ตัวอย่าง
git commit -m “change function b” 

## git clone
เป็นการก้อปปี้โปรเจคจำลองมาจากโปรเจคหลัก โดยเราจะสามารถเปลี่ยนแปลงไฟล์ในโปรเจคจำลองนี้ได้โดยที่ไม่กระทบโปรเจคหลัก (ไฟล์จำลองที่เราทำการเปลี่ยนแปลงจะเรียกว่า local repository และไฟล์หลักที่อยู่คนละที่จะเรียกว่า remote repository) 
### ตัวอย่าง git clone

## git checkout 
เป็นคำสั่งที่ใช้สำหรับสลับ ไปยัง branch หรือ Commit ที่เราเคยสร้างไว้
#### ตัวอย่าง
#### ย้ายการทำงานไปที่ Branch หรือ commit_id ที่ระบุ 
$ git checkout <branch name || commit id> 

#### สร้าง branch ชื่อ test และทำการสลับการทำงานมาที่ Branch นี้
$ git checkout -b test

####  ยกเลิกการเปลี่ยนแปลงของไฟล์ใน Working Directory
$ git checkout -- <file name>

#### เลือกแค่บางไฟล์จาก Branch อื่น เข้ามา Merge กับ Working Directory ที่กำลังทำงาน
$ git checkout <branch name> <file name>

#### คำสั่งนี้จะเหมือนคำสั่งด้านบนแต่จะมีโหมดตอบโต้กับผู้ใช้ในการเลือกสถานะของไฟล์ที่ระบุ
$ git checkout --patch <branch name> <file name>

#  git cherry-pick 
เปรียบเหมือน การที่ copy บางอย่างจาก folder หนึ่งไป paste ในอีก folder หนึ่งจะไม่ delete commit จาก branch เดิม และใน branch ที่เป็นปลายทาง ก็จะเป็น commit id ใหม่

# git config
