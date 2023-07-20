# Component 

Component คือหน่วยย่อยที่สุดที่ใช้สำหรับรับข้อมูลจาก user มีประเภทต่างๆ ดังนี้

* [Image](#image)
* [Text Block](#text-block)
* [Button](#button)
* [Video](#video)
* [Brand Card](#brand-card)
* [Content Group 1](#content-group-1)
* [Style](#style)
* [Align](#align)
* [SEO](#seo)

## Image

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/component/comp-image.png" alt="Image Component" style="width:100%; max-width:600px; hight:auto;">

ใช้รับข้อมูลรูปภาพ โดย user สามารถเลือกรูปที่มีอยู่หรืออัพโหลดใหม่ได้ผ่านทาง [Media Library](overview.md#media-library)

| Field | Description |
|-----|-----|
| image_desktop | รูปสำหรับแสดงผลบน website ขนาดจอไซส์ desktop |
| image_mobile | รูปสำหรับแสดงผลบน iOS, Androild App และ web ไซส์ mobile |
| link_url | ลิงค์ที่จะไปหากคลิกที่รูป (มีหรือไม่มีก็ได้) |
| link_target | รูปแบบการเปิดลิงค์ same tab หรือ new tab |

<hr>

## Text Block

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/component/comp-text.png" alt="Text Block Component" style="width:100%; max-width:600px; hight:auto;">

เป็น input ประเภท Rich Text Editor ที่สามารถรับข้อความ รูปภาพ มีเครื่องมือเบื้องต้นในการจัดการตัวหนังสือและ paragraph การใส่ Table ไปจนถึงการใส่ HTML ได้

<hr>

## Button

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/component/comp-button.png" alt="Component Image" style="width:100%; max-width:600px; hight:auto;">

ใช้สำหรับแสดงผลปุ่มตาม Style Guide ของ King Power

| Field | Description |
|-----|-----|
| button_text | ข้อความที่จะให้แสดงบนปุ่ม |
| link_url | ลิงค์ที่จะไปหากคลิกที่ปุ่ม |
| link_target | รูปแบบการเปิดลิงค์ same tab หรือ new tab |

<hr>

## Video

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/component/comp-vdo.png" alt="Video Component" style="width:100%; max-width:600px; hight:auto;">

ใช้แสดงผล Video Player ที่เป็นการ embed มาจากวิดีโอที่ถูกอัพโหลดไว้บน Youtube

| Field | Description |
|-----|-----|
| vdo_id | ใส่ ID ของคลิป Youtube (youtube.com/watch?v=[ Video ID ]) |

<hr>

## Brand Card

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/component/comp-brand-card.png" alt="Brand Card Component" style="width:100%; max-width:600px; hight:auto;">

ใช้แสดงผล Card ที่คล้าย Product Card แต่มีโลโก้แบรนด์ติดอยู่และไม่แสดงราคา

| Field | Description |
|-----|-----|
| title_name | รูปสำหรับแสดงที่ list หลังบ้านเท่านั้น ไม่แสดงผลที่ Front |
| logo_image | รูป brand logo |
| image | รูปสินค้า |
| description | ข้อความที่จะให้ปรากฎบนการ์ด |
| link_url | ลิงค์ที่จะไปหากคลิกที่การ์ด |
| link_target | รูปแบบการเปิดลิงค์ same tab หรือ new tab |

<hr>

## Content Group 1

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/component/comp-item-group-1.png" alt="Content Group 1 Component" style="width:100%; max-width:600px; hight:auto;">

ใช้แสดงผลเนื้อหาที่เป็นรูปคู่กันกับข้อความ คล้าย thumbnail คู่กับ caption เพื่อให้การเรียงลำดับเนื้อหาเมื่อ responsive รูปและเนื้อหาจะอยู่คู่กันเสมอ

| Field | Description |
|-----|-----|
| thumbnail | รูป |
| description | ข้อความ |
| link_url | ลิงค์ที่จะไปหากคลิกที่รูป |
| link_target | รูปแบบการเปิดลิงค์ same tab หรือ new tab |

<hr>

## Style

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/component/comp-style.png" alt="Style Component" style="width:100%; max-width:600px; hight:auto;">

ใช้สำหรับกำหนดสไตล์เบื้องต้นให้ [Layout](dynamic-zone.md#component-layout) ที่มี component นี้ติดตั้งอยู่

| Field | Description |
|-----|-----|
| padding | ระยะห่างที่ขอบ หากเป็น layout ที่มีมากกว่า 1 คอลัมน์ ค่านี้จะเป็นระยะห่างระหว่างคอลัมน์ด้วย มีให้เลือกระหว่าง no padding, 16px และ 32px |
| bg_color | สีของพื้นหลัง เลือกจาก color wheel หรือใส่ hex code เช่น #ffffff |
| text_color | สีของตัวหนังสือ เลือกจาก color wheel หรือใส่ hex code เช่น #ffffff |

<hr>

## Align

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/component/comp-align.png" alt="Align Component" style="width:100%; max-width:600px; hight:auto;">

ใช้สำหรับกำหนด align ของ [Layout](dynamic-zone.md#component-layout) ที่มี component นี้ติดตั้งอยู่ มีให้เลือกระหว่าง left, center และ right

<hr>

## SEO

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/component/comp-seo.png" alt="SEO Component" style="width:100%; max-width:600px; hight:auto;">

ใช้สำหรับกำหนด Page Title และ Meta Description ของหน้า

| Field | Description |
|-----|-----|
| metaTitle | ข้อความ Title ที่จะแสดงผลที่ web browser |
| metaDescription | ข้อความที่จะแสดงเมื่อหน้าถูก Search จาก Search Engine |

<hr>