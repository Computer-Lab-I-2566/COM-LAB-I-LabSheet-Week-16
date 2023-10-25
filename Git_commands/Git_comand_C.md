# คำสั่ง git ที่ขึ้นต้นด้วยอักษร C
## git commit
ยืนยันการเปลี่ยนแปลงไฟล์ที่ถูก add ลงใน stage โดยสามารถใส่ comment โดยการเติม -m ด้านหลัง
### ตัวอย่าง
git commit -m “change function b” 

## git clone
เป็นการก้อปปี้โปรเจคจำลองมาจากโปรเจคหลัก โดยเราจะสามารถเปลี่ยนแปลงไฟล์ในโปรเจคจำลองนี้ได้โดยที่ไม่กระทบโปรเจคหลัก (ไฟล์จำลองที่เราทำการเปลี่ยนแปลงจะเรียกว่า local repository และไฟล์หลักที่อยู่คนละที่จะเรียกว่า remote repository) 
### ![image](https://github.com/65030121natthamon/Git_A-Z_Mission_65030121/assets/144195611/a0f4da8c-8add-4cbf-8f6c-9e092d369247)


## git checkout 
เป็นคำสั่งที่ใช้สำหรับสลับ ไปยัง branch หรือ Commit ที่เราเคยสร้างไว้
#### 
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
# ![image](https://github.com/65030121natthamon/Git_A-Z_Mission_65030121/assets/144195611/62766497-211e-4534-b4c1-acbe0b095533)

# git config
การตั้งค่า Git โดยใส่ชื่อและอีเมล์ ตั้งค่าให้ git บันทึก username,email จำไว้ในเครื่องเราเอง เพื่อไม่ให้ถาม username, email ในตอนเวลาเรา pull โค้ดลงมา 
# ![image](https://github.com/65030121natthamon/Git_A-Z_Mission_65030121/assets/144195611/37c82c19-8652-4c0d-82af-b83c1b2fa9d7)
