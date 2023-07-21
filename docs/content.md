# Content Management

วิธีการจัดการเนื้อหาของแต่ละ module อาจมีความแตกต่างกันไปในรายละเอียด เมนูนี้เราจะมาแสดงรายละเอียดของการจัดการเนื้อหา โดนแยกตามแต่ละ module ดังนี้
- Homepage
- Navigation
- [Pop-up](#popup)

## Homepage

<hr>

## Navigation

<hr>

## Pop-up
ป๊อบอัพของเว็บ King Power E-comm จะถูกแบ่งออกเป็นสองประเภทใหญ่ๆ คือ Entry Pop-up กับ Floating Pop-up 

### Entry Pop-up
<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/entry-popup.png" alt="KP Entry Pop-up" style="width:100%; hight:auto;">

Entry Pop-up คือ แบนเนอร์ที่จะแสดงผลแรกสุดเมื่อเข้าสู่หน้า Home จะแสดงผลขึ้นตรงกลาง เหนือเนื้อหาอื่นๆ สามารถกดที่แบนเนอร์เพื่อลิงค์ไปที่หน้าอื่น และคลิกปุ่มกากบาทหรือส่วนอื่นนอกพื้นที่แบนเนอร์เพื่อปิดได้

#### การจัดการแบนเนอร์ Entry Pop-up
ไปที่เมนู Content Manager > Entry Pop-up เลือก entry ที่ต้องการแก้ไข หรือสร้างเพิ่มผ่านปุ่ม + Add new entry ที่มุมขวาบน

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/entry-popup-set.png" alt="KP Entry Pop-up" style="width:100%; max-width:700px; hight:auto;"><br><br>

| Field | Description |
|-----|-----|
| popup_name | ชื่อของ pop-up ใช้สำหรับการแสดงผลที่หลังบ้านเท่านั้น ไม่แสดงที่หน้าเว็บ |
| popup_detail | รายละเอียดของ pop-up ใช้สำหรับการแสดงผลที่หลังบ้านเท่านั้น ไม่แสดงที่หน้าเว็บ |
| popup_image | รูป pop-up |
| link_url | ลิงค์ที่จะไปหากคลิกที่รูป |
| link_target | รูปแบบการเปิดลิงค์ same tab หรือ new tab |
| popup_type | ประเภทของ pop-up มีให้เลือกระหว่าง Marketing กับ Royal ซึ่งจะส่งผลกับลำดับการขึ้นป๊อปอัพ |
| platform | เลือกแสดงผลตามแต่ละ platform ได้ |

### Floating Pop-up
<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/floating-popup.png" alt="KP Floating Pop-up" style="width:100%; hight:auto;">

Floating Pop-up คือแบนเนอร์ที่จะแสดงผลตามส่วนต่างๆ ของเว็บไซต์ มี 3 ตำแหน่งคือ

1. Top
2. Right Bottom
3. Bottom

#### การจัดการแบนเนอร์ Floating Pop-up

<hr>

## Campaign & Condition

<hr>

## GWP

<hr>

## Partner

<hr>

## FAQs

หน้า FAQs หรือ How-to จะมีความคล้ายคลึงกับหน้า [Campaign & Condition](#campaign--condition) ตรงที่ส่วนของเนื้อหาจะจัดการผ่าน [Dynamic Zone](dynamic-zone.md) และต่างกันตรงที่ในหมวดนี้จะแสดงผล [Submenu](#submenu) ทางด้านข้าง (ไซส์ mobile จะเป็น select dropdown) 

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/faqs/faqs-zone.png" alt="FAQs Structure">

#### การจัดการเนื้อหา

ที่เมนูหลัก Content Manager เลือกเมนู FAQ 

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/faqs/faqs-fields.png" alt="FAQs Fields" style="max-width:700px;"><br><br>

| Field | Description |
|-----|-----|
| title_name | ชื่อของหน้า |
| page_url | slug ที่จะนำไปสร้าง url ของหน้า เช่น หากใส่ test01 จะได้ url เป็น https://www.kingpower.com/content/test01 |
| title_display | เลือกระหว่าง show/hide ว่าจะแสดงชื่อหน้าที่ด้านบนของเนื้อหาหรือไม่ |
| submenu | เลือก [submenu](#submenu) ที่เคยถูกสร้างไว้ มาเพื่อแสดงผลทางด้านซ้ายของหน้า |
| focus_submenu | ใส่ชื่อเมนูบน เพื่อกำหนดว่าที่เมนูนั้นๆ จะเป็น state active เมื่อเข้ามาที่หน้านี้ |
| Dynamic Zone | จัดการเนื้อหาผ่าน [Dynamic Zone](dynamic-zone.md) |
| seo | จัดการ seo ผ่านทาง Component [SEO](component.md#seo) |

### Submenu

Submenu เป็นอีกส่วนประกอบหนึ่งที่ถูกใช้ที่เนื้อหาประเภท FAQs โดยจะแสดงผลที่ด้านซ้ายของหน้า แต่จะจัดการเนื้อหาแยกออกจากหน้านั้นๆ จุดประสงค์เพื่อเป็นการรวมลิงค์ของหน้าต่างๆ และนำไปใช้ซ้ำในทุกๆ หน้าที่เกี่ยวข้องกัน ช่วยให้เวลามีการเปลี่ยนแปลง url ของบางหน้าที่จะกระทบทุกๆ หน้าที่เกี่ยวข้อง สามารถแก้ไขได้ที่ submenu เพียงครั้งเดียว ไม่ต้องแก้ในทุกๆ หน้า

#### การจัดการ Submenu

ที่เมนูหลัก Content Manager เลือกเมนู Submenu เลือก submenu ที่ต้องการแก้ไข หรือสร้างเพิ่มผ่านปุ่ม + Add new entry ที่มุมขวาบน

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/faqs/faqs-submenu.png" alt="FAQs Submenu" style="max-width:700px;"><br><br>

| Field | Description |
|-----|-----|
| menu_name | ชื่อของ submenu ใช้สำหรับการแสดงผลที่หลังบ้านเท่านั้น ไม่แสดงที่หน้าเว็บ |
| submenu_item | สำหรับการสร้าง submenu item ได้เรื่อยๆ ผ่านการคลิกปุ่ม + Add new entry<br> ภายใน submenu item จะประกอบด้วย <ul><li>label</li><li>link_url</li><li>link_target</li></ul> |
| faqs | แสดงเมนูที่เชื่อมต่อกับ submenu นี้ |

<hr>