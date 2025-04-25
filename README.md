# PetSpa
Chatmongkhon Jaemjaeng 6631503009

ชื่อ - นามสกุล (Full Name): Chatmongkhon Jaemjaeng 

รหัสนักศึกษา (Student ID): 6631503009 

ตอนเรียน (Section) : 1

ชื่อแอป (App Name): PetSpa

Framework ที่ใช้ (Framework Used): React Native / อื่น ๆ

ลิงก์ GitHub Repository: https://github.com/march009/PetSpa

ลิงก์ไฟล์ติดตั้ง (APK/IPA): -


----------------------------------------------------------------

# 1. การออกแบบแอป | App Concept and Design (2 คะแนน / 2 pts)

1.1 ผู้ใช้งานเป้าหมาย | User Personas

Persona 1:

ชื่อ: ใบตอง

อายุ: 21 ปี

อาชีพ: นักศึกษา

ความต้องการ: ต้องการแอปที่ช่วยจองอาบน้ำและรับส่งสัตว์เลี้ยงได้ง่าย รวดเร็ว มี UI ที่น่ารักและใช้งานง่าย

Persona 2:

ชื่อ: พีช

อายุ: 25 ปี

อาชีพ: พนักงานบริษัท

ความต้องการ: ต้องการจองอาบน้ำให้สัตว์เลี้ยงโดยไม่ต้องเดินทางเอง และสามารถยกเลิกได้ง่ายหากไม่สะดวก

1.2 เป้าหมายของแอป | App Goals

ช่วยให้ผู้ใช้สามารถจองบริการอาบน้ำสัตว์เลี้ยงได้สะดวก

มี UI ที่เรียบง่าย ทันสมัย และใช้งานง่าย

รองรับการแสดงผลสถานะการจอง และยกเลิกได้ในคลิกเดียว

1.3 โครงร่างหน้าจอ / Mockup (คำอธิบาย 3 หน้า)

หน้า Home: มี Navigation Bar ด้านบน และปุ่มไปยังหน้าจอง / รายการจอง / สมัครสมาชิก

หน้า Booking: มีฟอร์มกรอกชื่อสัตว์เลี้ยง, วันที่, ที่อยู่รับส่ง และปุ่ม "ยืนยันการจอง"

หน้า My Bookings: แสดงรายการจองทั้งหมด พร้อมปุ่ม “ยกเลิก” ใต้แต่ละรายการ

1.4 การไหลของผู้ใช้งาน | User Flow

เปิดแอป > เข้าหน้าหลัก > สมัครสมาชิก > เลือก “จองบริการ” > กรอกข้อมูลสัตว์เลี้ยงและวันที่ > กด “ยืนยันการจอง” > ดูรายการในหน้า “การจองของฉัน”

----------------------------------------------------------------

# 2. การพัฒนาแอป | App Implementation (4 คะแนน / 4 pts)
2.1 รายละเอียดการพัฒนา | Development Details

เครื่องมือที่ใช้ / Tools used:

- React Native
- Expo
- Package: Provider, SharedPreferences, React-Navigation
2.2 ฟังก์ชันที่พัฒนา | Features Implemented
Checklist:

- [x] ตกลง / ยกเลิก การจองได้
- [x] สามารถดูประวัติการจอง
- [ ] ซิงก์กับ Firebase
2.3 ภาพหน้าจอแอป | App Screenshots
แนบภาพหรือ URL (Attach images or image links):
![image](https://github.com/user-attachments/assets/5c4af180-e0ea-4eda-b904-7e946433028d)
![image](https://github.com/user-attachments/assets/b77890a0-79da-4da5-8082-20b3c9d1907d)
![image](https://github.com/user-attachments/assets/df2d08c1-d24f-4361-a034-e7a3d6d85f78)



----------------------------------------------------------------

# 3. การ Build และติดตั้งแอป | Deployment (2 คะแนน / 2 pts)
3.1 ประเภท Build | Build Type

[x] Debug
[ ] Release
3.2 แพลตฟอร์มที่ทดสอบ | Platform Tested

[x] Android
[ ] iOS

3.3 ไฟล์ README และวิธีติดตั้ง | README & Install Guide
แนบไฟล์หรือคำอธิบายการติดตั้งแอป | Insert steps

1. Scan npx expo start เพื่อเปิดดูApplication
----------------------------------------------------------------

# 4. การสะท้อนผลลัพธ์ | Reflection (2 คะแนน / 2 pts)

พบปัญหาข้อมูลจองไม่แสดง เพราะส่งผ่าน navigation โดยไม่มีการเก็บสถานะแบบ global

ได้เรียนรู้การปรับ UI ให้ดูน่ารักทันสมัย และใช้ TouchableOpacity แทนปุ่มปกติ

หากมีเวลา อยากเพิ่มระบบ login และเชื่อม Firebase เพื่อเก็บข้อมูลการจองแบบถาวร

----------------------------------------------------------------

# 5. การใช้ AI ช่วยพัฒนา | AI Assisted Development (Bonus / ใช้ประกอบการพิจารณา)

5.1 ใช้ AI ช่วยคิดไอเดีย | Idea Generation

Prompt ที่ใช้:

"Suggest mobile app ideas for booking pet grooming services."

ผลลัพธ์:

ได้ไอเดียแอปรับ-ส่งสัตว์เลี้ยงเพื่ออาบน้ำ พร้อมระบบจอง ยกเลิก และติดตามสถานะ

5.2 ใช้ AI ช่วยออกแบบ UI | UI Layout Prompt

Prompt ที่ใช้:

"Design a simple React Native layout for a pet grooming booking app using Expo."

ผลลัพธ์:

ได้โครงสร้างแอปแบบ modern UI พร้อม navigation และหน้าจองที่ใช้งานง่าย

5.3 ใช้ AI ช่วยเขียนโค้ด | Code Writing Prompt

Prompt ที่ใช้:

"React Native code with navigation bar, booking form, and cancellation button."

ผลลัพธ์:
ได้โค้ดจองบริการ โดยมีฟอร์มใส่ชื่อสัตว์เลี้ยง วัน เวลา และที่อยู่ พร้อมปุ่มยกเลิกและจัดเก็บข้อมูลจองใน state

5.4 ใช้ AI ช่วย debug | Debug Prompt

Prompt ที่ใช้:

"My bookings screen doesn't show new bookings after I navigate back. How can I fix it?"

ผลลัพธ์:

AI แนะนำให้ใช้ React Context เพื่อเก็บ bookings แบบ global state แก้ปัญหาหน้าจอรีเฟรชแล้วข้อมูลหาย

5.5 ใช้ AI ช่วย Deploy | Deployment Prompt

Prompt ที่ใช้:

"How to build and test an Expo app on Android device?"

ผลลัพธ์:

ได้ขั้นตอนการใช้ expo build หรือ npx expo start พร้อม scan QR code ผ่านแอป Expo Go เพื่อทดสอบบนเครื่องจริงprofile preview

เพื่อทดสอบแอพได้ทันที
