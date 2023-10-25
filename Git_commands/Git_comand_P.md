# คำสั่ง git ที่ขึ้นต้นด้วยอักษร P
# git push
<br>
#### เพื่อส่งไฟล์ขึ้นไปที่ Repository บน Git (Remote)
<br>
git push <remote_name> <branch_name> // ตัวอย่าง git push origin master
<br>
  
#### เพื่อลบ Branch บน Repository บน Git (Remote)
  <br>
git push origin --delete <branch_name>
<br>
  
#### คำสั่งเพื่อส่งไฟล์ขึ้นไปที่ Repository บน Git (Remote) โดยอ้างอิง Tag
  <br>
git push origin <tag_name> // แบบระบุ tag
  <br>
git push origin --tags // tag ทั้งหมด
  
# git pull
คำสั่งดึงไฟล์ หรืออัพเดท Source Code ภายในเครื่อง (Local) ให้ตรงกับ Repository (Remote) โดยคำสั่ง git pull นั้นจะทำการ git fetch และ git merge ไปด้วย
<br>

git pull <remote_name> <branch_name> // ตัวอย่าง git pull origin master
