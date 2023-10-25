# คำสั่ง git ที่ขึ้นต้นด้วยอักษร P
## git push 
คือ ส่งการเปลี่ยนแปลงของไฟล์ไปบน remote repository
## git pull 
คือการ remote ไฟล์มายัง local โดยคำสั่ง git pull นั้นจะทำการ git fetch และ git merge ไปด้วย โดยเราจะมักเห็นใช้ git pull –rebase เพื่อทำการเปลี่ยนฐานแทนการ merge
## git push --force
ใช้เพื่อบังคับการอัพโหลดการ commit โดยทับการ commit ใน remote repository.
## git push --all
ใช้เพื่อส่งทุก branch ไปยัง remote repository.
## git push origin --delete <branch-name>
ใช้เพื่อลบ branch จาก remote repository.
## git pull --rebase
ใช้เพื่อดึงการเปลี่ยนแปลงจาก remote repository และรวมกับ branch ปัจจุบันโดยใช้ rebase แทนการ merge.
## git push origin --tags
ใช้เพื่อส่งแท็ก (tags) ไปยัง remote repository.
## git prune
ใช้เพื่อลบอ้างอิง (refs) ที่ไม่ได้ใช้งานจาก local repository.
