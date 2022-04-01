# UnitTest
643450321-2 นายก้องภพ ตาดี

#1
สร้างฟังก์ชั้น gradeCalculate โดยรับค่า score เป็น int และส่งค่ากลับเป็น string ใช้ if ในฟังก์ชั้น โดย ถ้า score มากกว่า 100 ให้ส่งค่ากลับเป็น A ถ้า score น้อยกว่า 0 ส่งค่ากลับเป็น F 
- Input score ถ้าเท่ากับ 80 ส่งค่ากลับเป็น A
- Input score ถ้าเท่ากับ 79 ส่งค่ากลับเป็น B+
- Input score ถ้าเท่ากับ 49 ส่งค่ากลับเป็น F
- Input score ถ้ามากกว่าหรือเท่ากับ 50 และ น้อยกว่า 55 ส่งค่ากลับเป็น D

#2
กำหนดตัวแปร result ในหน่วย double โดยรับค่าจาก getDistance และกำหนดค่า P1 = (3,2) P2 = (7,8) | P3 = (-3,2) P4 = (7,-8) | P5 = (-3,-2) P6 = (-7,-8) | P7 = (3,-2) P8 = (-7,8)
- Input P1 = (3,2) P2 = (7,8) เช็คว่า result เท่ากับ 7.21
- Input P3 = (-3,2) P4 = (7,-8) ทเช็คว่า result เท่ากับ 14.14 
- Input P5 = (-3,-2) P6 = (-7,-8) เช็คว่า result เท่ากับ 7.21 
- Input P7 = (3,-2) P8 = (-7,8) เช็คว่า result เท่ากับ 14.14 

#3
สร้างฟังก์ชั้น getFactorial โดยรับค่า n หน่วย int ส่งค่ากลับเป็น int และ สร้าง ตัวแปร i ในหน่วย int กับสร้าง ตัวแปร sum ในหน่วย int มีค่า เท่ากับ 1 
ใช้ for โดย ให้ i = 1 และ i <= n และ i บวกขึ้นที่ละ1 ให้ sum *= 1 และส่งค่า sum กลับ
สร้าง Method เชื่อมโยงกับ AssignmentClass กำหนด n ในหน่วย int และรับค่าจาก getFactorial
- Input n เท่ากับ 5 เช็คว่า n เท่ากับ 120
- Input n เท่ากับ 1 เช็คว่า n เท่ากับ 1
- Input n เท่ากับ 0 เช็คว่า n เท่ากับ 1
- Input n ถ้าน้อยกว่า 0 เช็คว่า n เท่ากับ

#4
สร้างฟังก์ชั้น cheackPassword โดยรับค่า password ในหน่วย string ส่งค่ากลับเป็น string ใช้ if password = "abc12345" ให้ Output ออกมาเป็น ture นอกจากนี้
ออกมาเป็น false
สร้าง Method เชื่อมโยงกับ AssignmentClass 
- Input password ในหน่วย string โดย Input ค่าเป็น abc123 เช็ค ว่า password ส่งค่ากลับเป็น false
- Input password ในหน่วย string โดย Input ค่าเป็น abc12345 ว่า password ส่งค่ากลับเป็น true
- Input password ในหน่วย string โดย Input ค่าเป็น abcdefgh เช็ค ว่า password ส่งค่ากลับเป็น false
- Input password ในหน่วย string โดย Input ค่าเป็น 12345678 ว่า password ส่งค่ากลับเป็น false
    
    
    
    
