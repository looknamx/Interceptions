เมื่อโหลดเสร็จ ให้แตกไฟล์ .zip ออกมา (แนะนำให้เอาโฟลเดอร์ไปไว้ที่หน้า Desktop จะได้หาง่ายๆ ครับ)

เปิดเข้าไปในโฟลเดอร์ที่แตกไฟล์ออกมา แล้วเข้าไปที่โฟลเดอร์ย่อยชื่อ command line installer
กดคลิกที่ช่อง Address Bar ด้านบนสุดของโฟลเดอร์ (ตรงที่บอกพาธไฟล์) เพื่อก๊อปปี้ที่อยู่โฟลเดอร์ไว้ (เช่น C:\Users...\Desktop\Interception\command line installer)
กดปุ่ม Start ของ Windows พิมพ์คำว่า cmd
ห้ามคลิกซ้ายเปิดปกติเด็ดขาด! ให้คลิกขวาที่ Command Prompt แล้วเลือก Run as administrator (เรียกใช้ในฐานะผู้ดูแลระบบ)
ในหน้าจอดำ พิมพ์คำว่า cd /d  (มีเว้นวรรค) แล้วคลิกขวาเพื่อวางที่อยู่ที่ก๊อปปี้มา เช่น:
cd /d C:\Users\xxx\Desktop\Interception\command line installer
แล้วกด Enter (ตอนนี้หน้าจอ CMD จะชี้มาที่โฟลเดอร์นี้แล้ว)
พิมพ์คำสั่งนี้ลงไปในจอดำ แล้วกด Enter:
install-interception.exe /install
ระบบจะขึ้นข้อความยืนยันว่า Interception successfully installed. (ติดตั้งสำเร็จ)

เมื่อติดตั้งเสร็จ คุณต้องทำการ Restart คอมพิวเตอร์ 1 ครั้งทันที เพื่อให้ไดรเวอร์ฝังตัวเข้าไปในระบบ Windows ครับ
