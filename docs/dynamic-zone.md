# Component Layout

## Dynamic Zone
ภายในระบบจัดการเนื้อหาสำหรับบางส่วน จะมีพื้นที่ที่ user จะสามารถจัดการเนื้อหาได้อย่างยืดหยุ่นมากขึ้น สามารถเลือก layout ที่ต้องการให้แสดงผลบนหน้าเว็บไซต์ได้ เราเรียกการจัดการส่วนนี้ว่า Dynamic Zone โดย User จะต้องเลือก Component Layout ต่างๆ ขึ้นมาเป็นเหมือนกับกรอบให้เนื้อหาก่อน โดย layout ต่างๆ นั้นจะเป็น Form รูปแบบต่างๆ ที่ไกด์ให้ User ใส่เนื้อหาได้ตาม layout ที่ต้องการ มีประเภทต่างๆ ดังนี้

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/dynamic-zone/dz-components.png" alt="Dynamic Zone Component Layout" style="width:100%; max-width:600px;">

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/dynamic-zone/dz-components-shared.png" alt="Dynamic Zone Component Layout" style="width:100%; max-width:600px;">

* [One Image](#one-image)
* [Two Image](#two-image)
* [Three Image](#three-image)
* [Four Image](#four-image)
* [Two Fixed Image](#two-fixed-image)
* [Three Fixed Image](#three-fixed-image)
* [Four Fixed Image](#four-fixed-image)
* [Text Block](#text-block)
* [Button Group 0](#button-group-0)
* [Button Group 1](#button-group-1)
* [Item List 3](#item-list-3)
* [Product Card](#product-card)
* [Flex Content](#flex-content)
* [VDO Player](#vdo-player)
* [Content with Image](#content-with-image)
* [Divider](#divider)

### Drag and Drop

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/dynamic-zone/dz-drag-drop-rearrange.png" alt="Dynamic Zone Drag & Drop to re-arrange" style="width:100%; max-width:600px;">

ภายใน Dynamic Zone สามารถ drag & drop layout ต่างๆ เพื่อทำการจัดลำดับบน-ล่างได้

<hr>

## One Image

เป็น Layout ที่จะแสดงผลรูปเดียว กางเต็มพื้นที่ container ซ้ายขวา 

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/layout/layout-one-image.png" alt="One Image Layout">

#### การจัดการเนื้อหา

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/layout/layout-one-image-blank.png" alt="One Image Layout" style="max-width:600px;">
<br><br>

| Field | Description |
|-----|-----|
| image | จัดการรูปผ่าน Component [Image](component.md#image) |
| style | จัดการสไตล์ผ่าน Component [Style](component.md#style) |

<hr>

## Two Image

เป็น Layout สำหรับแสดงผลรูป 2 รูป ที่จอขนาด desktop จะแบ่งพื้นที่กันซ้าย-ขวา ที่จอขนาด mobile จะต่อกันลงมาบน-ล่าง

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/layout/layout-two-image.png" alt="Two Image Layout">

#### การจัดการเนื้อหา

| Field | Description |
|-----|-----|
| image_1 | จัดการรูปผ่าน Component [Image](component.md#image) |
| image_2 | จัดการรูปผ่าน Component [Image](component.md#image) |
| style | จัดการสไตล์ผ่าน Component [Style](component.md#style) |

<hr>

## Three Image

เป็น Layout สำหรับแสดงผลรูป 3 รูป ที่จอขนาด desktop จะแบ่งพื้นที่กันตามความกว้าง ที่จอขนาด mobile จะต่อกันลงมาบน-ล่าง

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/layout/layout-three-image.png" alt="Three Image Layout">

#### การจัดการเนื้อหา

| Field | Description |
|-----|-----|
| image_1 | จัดการรูปผ่าน Component [Image](component.md#image) |
| image_2 | จัดการรูปผ่าน Component [Image](component.md#image) |
| image_3 | จัดการรูปผ่าน Component [Image](component.md#image) |
| style | จัดการสไตล์ผ่าน Component [Style](component.md#style) |

<hr>

## Four Image

เป็น Layout สำหรับแสดงผลรูป 4 รูป ที่จอขนาด desktop จะแบ่งพื้นที่กันตามความกว้าง ที่จอขนาด mobile จะต่อกันลงมาบน-ล่าง

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/layout/layout-four-image.png" alt="Four Image Layout">

#### การจัดการเนื้อหา

| Field | Description |
|-----|-----|
| image_1 | จัดการรูปผ่าน Component [Image](component.md#image) |
| image_2 | จัดการรูปผ่าน Component [Image](component.md#image) |
| image_3 | จัดการรูปผ่าน Component [Image](component.md#image) |
| image_4 | จัดการรูปผ่าน Component [Image](component.md#image) |
| style | จัดการสไตล์ผ่าน Component [Style](component.md#style) |

<hr>

## Two Fixed Image

เป็น Layout สำหรับแสดงผลรูป 2 รูป ที่จอขนาด desktop จะแบ่งพื้นที่กันซ้าย-ขวา ที่จอขนาด mobile จะต่อกันตามลักษณะเดิม

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/layout/layout-two-fixed-image.png" alt="Two Fixed Image Layout">

#### การจัดการเนื้อหา

| Field | Description |
|-----|-----|
| image_1 | จัดการรูปผ่าน Component [Image](component.md#image) |
| image_2 | จัดการรูปผ่าน Component [Image](component.md#image) |
| style | จัดการสไตล์ผ่าน Component [Style](component.md#style) |

<hr>

## Three Fixed Image

เป็น Layout สำหรับแสดงผลรูป 3 รูป ที่จอขนาด desktop จะแบ่งพื้นที่กันตามความกว้าง ที่จอขนาด mobile จะต่อกันตามลักษณะเดิม

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/layout/layout-three-fixed-image.png" alt="Three Fixed Image Layout">

#### การจัดการเนื้อหา

| Field | Description |
|-----|-----|
| image_1 | จัดการรูปผ่าน Component [Image](component.md#image) |
| image_2 | จัดการรูปผ่าน Component [Image](component.md#image) |
| image_3 | จัดการรูปผ่าน Component [Image](component.md#image) |
| style | จัดการสไตล์ผ่าน Component [Style](component.md#style) |

<hr>

## Four Fixed Image

เป็น Layout สำหรับแสดงผลรูป 4 รูป ที่จอขนาด desktop จะแบ่งพื้นที่กันตามความกว้าง ที่จอขนาด mobile จะต่อกันตามลักษณะเดิม

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/layout/layout-four-fixed-image.png" alt="Four Fixed Image Layout">

#### การจัดการเนื้อหา

| Field | Description |
|-----|-----|
| image_1 | จัดการรูปผ่าน Component [Image](component.md#image) |
| image_2 | จัดการรูปผ่าน Component [Image](component.md#image) |
| image_3 | จัดการรูปผ่าน Component [Image](component.md#image) |
| image_4 | จัดการรูปผ่าน Component [Image](component.md#image) |
| style | จัดการสไตล์ผ่าน Component [Style](component.md#style) |

<hr>

## Text Block

เป็น Layout สำหรับแสดงผลข้อความ โดยจะเป็นการกางเนื้อหาเต็มพื้นที่ container ซ้ายขวา

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/layout/layout-text-block.png" alt="Text Block Layout">

#### การจัดการเนื้อหา

| Field | Description |
|-----|-----|
| text | จัดการเนื้อหาผ่าน Component [Text Block](component.md#text-block) |
| style | จัดการสไตล์ผ่าน Component [Style](component.md#style) |

<hr>

## Button Group 0

เป็น Layout สำหรับแสดงผลปุ่ม สามารถแสดงผลได้มากกว่า 1 ปุ่ม

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/layout/layout-button-group-0.png" alt="Button Group 0 Layout">

#### การจัดการเนื้อหา

| Field | Description |
|-----|-----|
| button | จัดการปุ่มผ่าน Component [Button](component.md#button) สามารถเพิ่มจำนวนปุ่มได้เรื่อยๆ โดยการคลิกที่ + Add an entry |
| style | จัดการสไตล์ผ่าน Component [Style](component.md#style) |
| align | จัดการ align ผ่าน Component [Align](component.md#align) |

<hr>

## Button Group 1

เป็น Layout สำหรับแสดงผลปุ่มคู่กับข้อความ สามารถแสดงผลได้มากกว่า 1 ปุ่ม

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/layout/layout-button-group-1.png" alt="Button Group 1 Layout">

#### การจัดการเนื้อหา

| Field | Description |
|-----|-----|
| text | จัดการข้อความผ่าน Component [Text Block](component.md#text-block) |
| button | จัดการปุ่มผ่าน Component [Button](component.md#button) สามารถเพิ่มจำนวนปุ่มได้เรื่อยๆ โดยการคลิกที่ + Add an entry |
| style | จัดการสไตล์ผ่าน Component [Style](component.md#style) |


<hr>

## Item List 3

เป็น Layout ที่จะแสดงผล Card ที่คล้าย Product Card แต่มีโลโก้แบรนด์ติดอยู่และไม่แสดงราคา โดยการ์ดจะเรียงต่อกันไปทางขวา เมื่อสุด container จะสามารถสไลด์ข้างได้

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/layout/layout-item-list-3.png" alt="Item List 3 Layout">

*Item List 1 และ 2 ถูกใช้ไปกับ GWP และ Partner Promotion ซึ่งไม่ได้เปิดให้ใช้งานบน Dynamic Zone*

#### การจัดการเนื้อหา

| Field | Description |
|-----|-----|
| item_list | เพิ่ม Component [Brand Card](component.md#brand-card) ได้เรื่อยๆ โดยการคลิกที่ + Add an entry |
| style | จัดการสไตล์ผ่าน Component [Style](component.md#style) |

<hr>

## Product Card

เป็น Layout ที่จะแสดงผล Product Card มีเนื้อหาและฟังก์ชั่นตาม Product Card ที่ใช้บนเว็บ/แอพ King Power ทุกอย่าง โดยการ์ดจะเรียงต่อกันไปทางขวา เมื่อสุด container จะสามารถสไลด์ข้างได้

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/layout/layout-product-card.png" alt="Product Card Layout">

#### การจัดการเนื้อหา

| Field | Description |
|-----|-----|
| product_sku | ใส่ sku ที่ต้องการให้แสดงผล โดยแยกแต่ละ sku ด้วย , (comma) |
| style | จัดการสไตล์ผ่าน Component [Style](component.md#style) |

<hr>

## Flex Content

เป็น Layout ที่จะแสดงผลรูปและเนื้อหาคู่กัน สามารถสร้างเพิ่มได้เรื่อยๆ โดยที่จอขนาด desktop จะเรียงเนื้อหาได้เป็น 3 คอลัมน์ จากนั้นจะตัดตกลงมา (flex-wrap)

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/layout/layout-flex-content.png" alt="Flex Content Layout">

#### การจัดการเนื้อหา

| Field | Description |
|-----|-----|
| content_group | เพิ่ม Component [Content Group 1](component.md#content-group-1) ได้เรื่อยๆ โดยการคลิกที่ + Add an entry |
| style | จัดการสไตล์ผ่าน Component [Style](component.md#style) |

<hr>

## VDO Player

เป็น Layout ที่จะแสดงวิดีโอ สามารถกดเล่นวิดีโอได้ โดยจะเป็นการ embed คลิปวิดีโอที่ถูกอัพโหลดบน Youtube

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/layout/layout-vdo-player.png" alt="VDO Player Layout">

#### การจัดการเนื้อหา

| Field | Description |
|-----|-----|
| video | จัดการลิงค์วิดีโอผ่าน Component [Video](component.md#video) |
| style | จัดการสไตล์ผ่าน Component [Style](component.md#style) |

<hr>

## Content With Image

เป็น Layout ที่จะแสดงผลรูปและข้อความคู่กันซ้าย-ขวา สามารถกำหนดความกว้างได้ และสามารถสร้างเพิ่มได้เรื่อยๆ โดยเนื้อหาจะถูกเรียงต่อลงมาเหมือน list

<img src="https://kpc-prod-frontend-resource.s3.ap-southeast-1.amazonaws.com/micrositeHtml/kp-cms/images/layout/layout-content-with-image.png" alt="Content with Image Layout">

#### การจัดการเนื้อหา

| Field | Description |
|-----|-----|
| image | จัดการรูปผ่าน Component [Image](component.md#image) |
| max_width | ความกว้างสูงสุดของ container หน่วยเป็น px |
| content | จัดการเนื้อหาผ่าน Component [Text Block](component.md#text-block) |
| content_ratio | กำหนดสัดส่วนระหว่างรูปและข้อความ ระหว่าง 1:1, 1:3 และ 2:3 |
| style | จัดการสไตล์ผ่าน Component [Style](component.md#style) |

<hr>

## Divider

เป็น Layout ที่จะเพิ่ม space ให้กับหน้า สามารถกำหนดความสูงและสีพื้นหลังได้

#### การจัดการเนื้อหา

| Field | Description |
|-----|-----|
| height | ใช้กำหนดความสูงของพื้นที่ว่าง เลือกได้ระหว่าง 8px, 16px และ 32px |
| bg_color | สีของพื้นหลัง เลือกจาก color wheel หรือใส่ hex code เช่น #ffffff |