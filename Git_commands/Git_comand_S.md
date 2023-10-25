# คำสั่ง git ที่ขึ้นต้นด้วยอักษร S
# git status
 คือคำสั่งที่แสดงสถานะของ working directory และ staging area ของ Git repository คำสั่งนี้จะแสดงรายการไฟล์ที่แก้ไข ไฟล์ที่เพิ่ม และไฟล์ที่ลบ รวมถึงไฟล์ที่ไม่ติดตาม ซึ่งหมายความว่าไฟล์เหล่านั้นไม่ได้ถูกติดตามโดย Git
คำสั่ง git status มีรูปแบบดังนี้
-
------>    git status

## สถานะของ Source Code ที่เก็บอยู่ในระบบของ Git นั้นมีดั่งนี้

Untracked เป็นสถานะที่ Source Code ถูกเพิ่มเข้ามาใหม่และยังไม่ได้ถูกเก็บไว้ในระบบของ Git
<br>
Working Directory เป็นสถานะที่กำลังมีการเปลี่ยนแปลงหรือแก้ไข Source Code หรืออาจจะเรียกสถานะนี้ว่า Modified\
<br>
Staged เป็นสถานะที่ Source Code กำลังเตรียมที่จะ Commit เพื่อยืนยันการเปลี่ยนแปลงก่อนที่จะเก็บลงในสถานะ Local Repository
<br>
Local Repository เป็นสถานะที่มีการเก็บบันทึกข้อมูลการเปลี่ยนแปลงของ Source Code ลงไปที่ Git Repository ที่เป็น Local (ที่เครื่องตัวเอง)
<br>
Remote Repository เป็นสถานะที่มีการเก็บบันทึกข้อมูลการเปลี่ยนแปลงของ Source Code ลงไปที่ Git Repository ที่เป็น Hosting (ที่เครื่องเซิร์ฟเวอร์)
