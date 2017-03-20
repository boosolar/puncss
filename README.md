# punCSS  Framework

## ติดตั้ง

    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge, chrome=1">
    <meta name="viewport" content="width=device-width, initial-scale=1">


    <link rel="stylesheet" type="text/css" href="https://boosolar.github.io/puncss/css/main.min.css" >
    <link rel="stylesheet" type="text/css" href="https://boosolar.github.io/puncss/css/black.min.css" >

## fonts
ใช้ [Roboto](https://fonts.google.com/specimen/Roboto?selection.family=Roboto:300,300i,400,400i,500,500i,700,700i)

### Font size
ค่าเริ่มต้นคือ 14px

## Reset
ใช้ [Normalize.css](https://github.com/boosolar/normalize.css)


## Prefix
pun-   สำหรับไฟล์ pun-black.css ,pun-white.css


## Icons
ใช้ FontIcons จาก IcoMoon, Font Awesome, Material Icons ที่ https://boosolar.github.io/fonts/
ในชื่อ pun-icons

# Layouts and Responsive

ใส่ -xs -s -m -l -xl ต่อท้าย เพื่อระบุการแสดงผลในแต่ละขนาดหน้าจอ  หากไม่ใส่ จะหมายถึงทุกหน้าจอ
    

## viewsport size
ขนาดใหญ่จะทับขนาดเล็กกว่า
ประกอบไปด้วย
 - xs หน้าจอเล็กมาก  0 - all
 - s  หน้าจอเล็ก     576px - all
 - m  หน้าจอกลาง    768px - all
 - l  หน้าจอใหญ่     992px - all
 - xl หน้าจอใหญ่มาก  1200px - all


## Container size
 - xs กว้าง 100%
 - s  กว้าง 540px
 - m  กว้าง 720px
 - l  กว้าง 960px
 - xl กว้าง 1140px
 
### Class
 - .container
 - .container-full
 - .container-over
 
## Grid System
ใช้ชื่อขนาดหน้าจอ xs s m l xl ตามด้วยตัวเลขขนาด


### Class
 - xs0 ถึง xl12         กำหนดขนาดด้วย flex-grow
 - xs-0 ถึง xl-12       กำหนดขนาดด้วย flex-shrink
 - xs1-12 ถึง xl12-12   กำหนดขนาดด้วย width
 
### ตำแหน่ง
 อ้างอิงจำนวนตาม Grid System
 - index-12 ถึง index12     สำหรับจัดตำแหน่งก่อนหลัง
 - z-index-12 ถึง z-index12 สำหรับจัดตำแหน่งการทับกัน
 ใส่ -xs -s -m -l -xl ต่อท้ายได้เพื่อระบุการแสดงผลในแต่ละขนาดหน้าจอ  หากไม่ใส่ จะหมายถึงทุกหน้าจอ
 
## การจัดตำแหน่ง และการจัดเรียง

### Class
- .row 
- .rows
- .col
- .cols

ส่วนขยาย ใช้ต่อท้าย .row , .rows , .col , .cols
- -left     กำหนดให้ tag ภายใน ชิดซ้าย
- -right    กำหนดให้ tag ภายใน ชิดขวา
- -top      กำหนดให้ tag ภายใน ชิดบน
- -bottom   กำหนดให้ tag ภายใน ชิดล่าง
- -mid      กำหนดให้ tag ภายใน อยู่กึ่งกลาง
- -mid-h    กำหนดให้ tag ภายใน อยู่กึ่งกลาง ด้านสูง
- -mid-w    กำหนดให้ tag ภายใน อยู่กึ่งกลาง ด้านกว้าง

ใส่ -xs -s -m -l -xl ต่อท้ายได้ส่วนขยาย เพื่อระบุการแสดงผลในแต่ละขนาดหน้าจอ  หากไม่ใส่ จะหมายถึงทุกหน้าจอ

## เงา
ขนาดเงา 0 1 2 3 4 6 8 16 24 ตาม [Material design– Elevation & shadows](https://material.io/guidelines/material-design/elevation-shadows.html)


class
 - .lv0 ถึง .lv24

## Color
กำหนดสีตาม [Material design colors Style](https://material.io/guidelines/style/color.html#)
รหัสสี 50 100 200 300 400 500 600 700 800 900 a1 a2 a3 a4

### สีพื้นหลัง 
black.css, white.css

### Class
 - .color-50 ถึง .color-a4 ตามรหัสสี หรือตามที่ตั้งค่า
 - .bg สีพื้นหลัง เช่นเดียวกับ body
 - .bg1 สีพื้นหลัง สีอ่อนสุด
 - .bg2 สีพื้นหลัง กลาง
 - .bg3 สีพื้นหลัง สีเข้มสุด
 
 - .txt1 สีตัวอักษร หลัก เข้มสุด เป็นค่าเริ่มต้น
 - .txt2 สีตัวอักษร กลาง 
 - .txt3 สีตัวอักษร สีอ่อนสุด
 
 - .icon สีไอคอนขณะทำงาน

 - .bg-glass สีพื้นหลังโปรงใส
 - .txt-glass สีตัวอักษรโปรงใส
 
 - .info-color  สีพื้นหลัง ตัวอักษร ขอบ สำหรับ info 
 - .info-bg     สีพื้นหลังสำหรับ info 
 - .info-txt    สีตัวอักษรสำหรับ  info
 - .info-border สีขอบสำหรับ  info
 
 - .warning-color  สีพื้นหลัง ตัวอักษร ขอบ สำหรับ warning 
 - .warning-bg     สีพื้นหลังสำหรับ warning 
 - .warning-txt    สีตัวอักษรสำหรับ  warning
 - .warning-border สีขอบสำหรับ  warning
 
 - .success-color  สีพื้นหลัง ตัวอักษร ขอบ สำหรับ success 
 - .success-bg     สีพื้นหลังสำหรับ success 
 - .success-txt    สีตัวอักษรสำหรับ  success
 - .success-border สีขอบสำหรับ  success
 
 - .error-color  สีพื้นหลัง ตัวอักษร ขอบ สำหรับ error 
 - .error-bg     สีพื้นหลังสำหรับ error 
 - .error-txt    สีตัวอักษรสำหรับ  error
 - .error-border สีขอบสำหรับ  error
 
ส่วนขยายสำหรับ .bg .bg1 .bg2 .bg3
 - -txt เปลี่ยนสีตัวอักษร ให้เป็น สีพื้นหลัง เช่น .bg-txt
 
ส่วนขยายสำหรับ .txt1 .txt2 .txt3
 - -bg เปลี่ยนสีพื้นหลัง ให้เป็น สีตัวอักษร






