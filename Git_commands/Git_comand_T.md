# คำสั่ง git ที่ขึ้นต้นด้วยอักษร T
## Git Tag
เป็นคำสั่งที่ใช้แสดงและสร้าง Tag ขึ้นที่จุด commit นั้น


          $git tag         #แสดงแท็กทั้งหมด
          $git tag -n99    #แสดงแท็กทั้งหมดพร้อมข้อความ
          $git tag v1.0.0                   #สร้างแท็กชื่อ v1.0.0
          $git tag v1.0.1 -m "Tag Message"  #สร้างแท็กชื่อ v1.0.0 พร้อมระบุข้อความ
          $git tag --delete v1.0.0          #ลบแท็กชื่อ               
          $git push origin <tag name> #ส่งแท็กขึ้นไปที่ Remote Repository 
          $git push origin --tags     #ส่งแท็กทั้งหมดขึ้นไปที่ Remote Repository
          $git push --delete origin <tag name> #ลบแท็กที่              Remote Repository
