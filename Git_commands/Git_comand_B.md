# คำสั่ง git ที่ขึ้นต้นด้วยอักษร B
## คำสั่ง "git branch" 
 git branch เริ่มต้นจากคำสั่งแรกเราจะ list branch ที่มีบน local repository กับ branch บน remote repository ด้วยคำสั่ง
### แสดงรายชื่อ branch บน local repository
git branch
git branch --list
### แสดงรายชื่อ branch ทั้ง local และ remote branch
git branch -r
### แสดงรายชื่อ branch ทั้งหมด
git branch -a
# ![git-branch-1](https://github.com/65030121natthamon/Git_A-Z_Mission_65030121/assets/144195611/3d43398d-9d86-4726-badb-43400f6b7431)
 create new git branch
ในตัวอย่างนี้เริ่มต้นมีแค่ master branch เท่านั้น

หลังจากนั้นให้ทำการสร้าง branch ขึ้นมาใหม่ด้วยคำสัง
### สร้าง branch ขึ้นมาใหม่ด้วยคำสัง
git branch [ชื่อ branch ใหม่]
# ![git-branch-2](https://github.com/65030121natthamon/Git_A-Z_Mission_65030121/assets/144195611/b347c614-72c8-43d6-bdc0-260ad50d77dc)
เมื่อสร้าง branch ใหม่แล้วจะมี pointer ที่เป็น branch และ HEAD อยู่ที่เดียวกัน
