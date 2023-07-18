# KP CMS Overview

## Dashboard

<img src="/assets/images/main-menu-01.png" alt="Dashboard" style="width:100%; max-width:600px; hight:auto;">

User ระดับ Editor จะมองเห็นเมนูหลักได้ดังนี้  

## Content Manager
เมนูหลักที่ใช้ในการจัดการเนื้อหา 

สำหรับ User ระดับ Editor จะสามารถจัดการ
* Homepage
* Entry Popup
* Floating Popup
* Navigation
* Navigation Item
* Campaign & Condition
* Partner
* GWP
* FAQs
* Submenu

สำหรับ User ระดับ Admin จะสามารถจัดการเพิ่มเติมได้กับ
* Homepage Icon

ที่เหลือนอกจากนั้น(หากเห็น) จะเป็น collection สำหรับเซ็ทระบบของ dev เช่น content ratio, padding

<hr>

## Media Library
เมนูที่ใช้สำหรับการเก็บ media ต่างๆ ที่ใช้ในการสร้างเนื้อหา เช่น รูปภาพต่างๆ สามารถจัดระเบียบได้จากการแบ่ง Folder เพื่อให้การเรียกใช้งานเป็นไปอย่างสะดวก

<img src="/assets/images/media-library.png" alt="Media Library" style="width:100%; max-width:600px; hight:auto;">
<br><br>
<img src="/assets/images/media-library-add-assets.png" alt="Media Library" style="width:100%; max-width:600px; hight:auto;">

### ประเภทไฟล์ที่รองรับ

รูป: jpg, jpeg, png, gif, svg, webp, tiff, ico, dvu

วิดีโอ: mpeg, mp4, mov, wmv, avi, flv

เสียง: mp3, wav, ogg

ไฟล์: csv, zip, pdf, xls, xlsx, json

 *รองรับบน Strapi แต่อาจไม่รองรับที่ front ของ web, iOS, Android



<hr>

## ระบบพื้นฐาน

### Version

ระบบ version ทำให้ user สามารถทำการแก้ไขหน้าได้โดยไม่กระทบกับหน้าที่กำลัง Live แม้ว่าหน้านั้นจะ publish อยู่ วิธีการใช้งานคือ ทุกครั้งที่มีการสร้างหน้าใหม่ จะต้องทำการกดที่ปุ่ม Save as a new version อย่างน้อย 1 ครั้งเพื่อสร้าง v1 ขึ้นมา และหากต้องการสร้าง version แยกก็สามารถทำได้จากการกดปุ่มนี้เช่นกัน 

<img src="/assets/images/version.png" alt="Version" style="width:100%; hight:auto;">

เมื่อหน้ามีมากกว่า 1 version จะมี dropdown select ให้เราสามารถสลับไปมาเพื่อแก้ไขแต่ละ version ได้ ควรเช็คดูให้แน่ใจทุกครั้งก่อนทำการแก้ไขว่ากำลังทำงานอยู่บน version ที่ถูกต้องหรือไม่ หากทำการแก้ไช version ที่กำลัง publish อยู่จะทำให้หน้าที่กำลัง Live ทำการเปลี่ยนแปลงทันทีที่กด save

การ preview นั้นสามารถแยก preview ได้แต่ละ version ผ่านปุ่ม opend dreft preview และหากหน้าที่กำลังทำการแก้ไขอยู่นั้นเป็น version ที่ live อยู่ (publish แล้ว) ปุ่มตรงนี้จะกลายเป็น open live view แทน

### Locales

ระบบ locales (Internationalization) ใช้สำหรับการจัดการเนื้อหาหลายภาษา โดยทั้งสองภาษาจะใช้ url ร่วมกัน user สามารถสลับการแก้ไขแต่ละภาษาได้จาก dropdown select locales เมื่อเลือกภาษาแล้วหน้าจะทำการ refresh ไปภาษาที่ถูกเลือก ใน version เดียวกันกับภาษาที่กดมา *ควรกำหนดให้ version แต่ละภาษาตรงกันเพื่อกันความผิดพลาด*

<img src="/assets/images/locales.png" alt="Locales" style="width:100%; hight:auto;">

นอกจากนี้ยังมีปุ่ม Fill in from another locale ที่ทำให้ user สามารถ copy เนื้อหาจากอีกภาษาหนึ่งมาตั้งต้นเพื่อการอัพเดทอีกภาษาหนึ่งได้ เมื่อกดปุ่มจะมีการให้ยืนยันอีกหนึ่งขั้นตอนว่าจะนำเนื้อหาจากภาษาใดมาทับ 

<img src="/assets/images/locales-fill.png" alt="Locales" style="width:100%; hight:auto;">

<img src="/assets/images/locales-save.png" alt="Locales" style="width:100%; hight:auto;">

หลังจากใส่ข้อมูลของภาษานั้นๆ แล้ว ควรทำการ Save as a new version อย่างน้อย 1 ครั้ง เพื่อป้องกันปัญหาการ publish

### Publish/Unpublish

<img src="/assets/images/publish-unpublish-date.png" alt="Publish/Unpublish" style="width:100%; max-width:600px; hight:auto;">

ระบบ Publish/Unpiblish ทำให้ User ทำงานและเซฟแบบ draft ไว้ก่อนได้แล้วค่อย publish แสดงผลที่หน้าบ้านเมื่อพร้อม รวมถึงมีความสามารถในการตั้งเวลา publish/unpublish ล่วงหน้าไว้ได้ เพื่อให้ user ไม่ต้องทำแบบ manual ตอนเวลาที่ต้องการ


