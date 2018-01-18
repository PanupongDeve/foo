# การใช้งานGitHub


| คำสั่ง       |  คำอธิบาย          | ตัวอย่าง  |
|:-------------:|:-------------:|:-----:|
| git init       |เริ่มต้นสร้างgithub บนเครื่อง | git init|
| git remote add (local) (host) | เป็นคำสั่งให้git ของ local และ host รู้จักกัน      |   git remote add origin https://github.com/PanupongDave/laravel.git |
| git add    | เพิ่มไฟล์ที่เขียนใหม่    |   git add. หรือ  git add test.txt |
| git commit | ยืนยันข้อมูลก่อนส่งไฟล์      |    git commit -m "first commit" |
| git push | อัพโหลดไฟล์ขึ้น github    |    git push origin master |
| git pull | ดาวน์โหลดไฟล์จาก github     |    git pull origin master |
| git checkout | ถ้ามี -b สร้าง branch ใหม่ ถ้าไม่มีคือการเปลี่ยน branch | git checkout -b newversion / git checkout develop |
| git fetch | ทำการตรวจสอบระหว่างlocalและhost ว่าข้อมูลตรงกันหรืิอป่าว    |    git fetch |
| git clone | โคลนgithub     |    git clone https://github.com/PanupongDave/laravelLearning.git |



