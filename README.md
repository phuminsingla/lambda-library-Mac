# LAMBDA Board library for Arduino IDE (Unofficial)

ไลบารี่ที่ใช้ในโปรแกรม Arduino IDE เพื่อใช้งานบอร์ด LAMBDA รุ่น Lift/Basic/Plus ได้เต็มประสิทธิ์ภาพ เนื่องจากบอร์ดนี้ได้ใช้ชิฟตัวใหม่ ATmaga328pb ซึ่งมีความสามารถเพิ่มขึ้นจากรุ่นก่อนๆมาก เช่น มี UART จำนวน 2 ช่อง จากเดิมที่มีเพียงช่องเดียว สามารถใช้ Pin PE0, PE1 หรือ E0, E1

หมายเหตุ: นี่ไม่ใช่ไลบารี่จากผู้ผลิต จัดทำขึ้นเพื่อใช้งานในระหว่างที่ผู้ผลิตกำลังจัดทำไลบารี่สำหรับบอร์ดโดยเฉพาะ ผู้จัดทำปรับปรุงสำหรับ Mac OS CPU Intel และผู้ใช้ arduino v2.x.x ที่ไม่สามารถติดตั้ง lambda ได้เท่านั้น ส่วน M1 M2 ไม่มีให้ลองทำ

![1_mbD8uZDD_RCR_Lc3QPU_sw](https://github.com/phuminsingla/lambda-library-Mac/assets/5608098/f17f0627-a2d6-4736-9af3-59b53c2acc31)

# การติดตั้ง
<ul>
	<li>เปิดโปรแกรม Arduino IDE ขึ้นมา จากนั้นกดไปที่ File > Preferences</li>
	<li>ในช่อง Additional Boards Manager URLs กรอก json ด้านล่าง</li>
	<li>กดไปที่ Tool > Board > Boards Manager เลื่อนหา LAMBDA Boards กด Install รอจนกว่าจะโหลดเสร็จ จากนั้นปิดหน้าต่างไป</li>
	<li>เลือกบอร์ด เลือกพอร์ต จากนั้นทดลอง Upload ได้เลย</li>
</ul>

# json file
```
https://raw.githubusercontent.com/phuminsingla/lambda-library-Mac/master/package_lambda_kmutt.json
```

# ลิขสิทธิ์การใช้งาน
<ul>
	<li>https://github.com/maxpromer/lambda-library</li>
	<li>https://github.com/watterott/ATmega328PB-Testing</li>
	<li>http://www.atmel.com/tools/ATMELAVRTOOLCHAINFORWINDOWS.aspx</li>
	<li>http://www.ioxhop.com/</li>
	<li>https://support.arduino.cc/</li>
</ul>
