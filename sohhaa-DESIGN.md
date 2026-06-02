# Sohhaa Design System

## Overview
Sohhaa is an event discovery and management platform that connects event-goers with organizers in one seamless experience. The design system reflects the brand's core identity: **warm, approachable, and trustworthy** — easy enough for anyone to find and join an event, yet powerful enough for organizers to manage and grow their audience.

The aesthetic balances a clean, modern structure with friendly energy. Every component is designed to reduce friction — whether someone is browsing weekend activities or an organizer reviewing post-event analytics.

**Design Principles**
- **Clear over clever** — ข้อมูลต้องอ่านได้ทันที ไม่ต้องตีความ
- **Approachable** — ทุกคนใช้งานได้ ไม่ว่าจะ Tech-savvy แค่ไหน
- **Trustworthy** — ระบบจอง/ชำระเงินต้องดูน่าเชื่อถือทุกจุด
- **Responsive-first** — Mobile และ Web ต้องสมบูรณ์เท่ากัน

## Brand Voice

### Sohhaa คือใคร
Sohhaa คือพื้นที่รวมกิจกรรมที่ทำให้วันหยุดของคุณไม่ว่างเปล่า เกิดมาเพื่อให้คนหากิจกรรมได้ง่ายขึ้น และให้ผู้จัดงานมีเครื่องมือที่ดีพอ ไม่ต้องใช้หลายแอป จบในที่เดียว

### Tone & Voice
| มิติ | Sohhaa เป็น | Sohhaa ไม่เป็น |
|---|---|---|
| ภาษา | เป็นกันเอง กระชับ | ทางการ ซับซ้อน |
| น้ำเสียง | กระตือรือร้น ชวนออกไป | เย็นชา หรือ Hype เกิน |
| ความรู้สึก | เชื่อถือได้ ไม่ทำให้กังวล | ดูน่ากลัวหรือยุ่งยาก |
| การช่วยเหลือ | แนะนำตรงๆ ไม่วนเวียน | พูดมากเกินจำเป็น |

### Microcopy — ตัวอย่างภาษาที่ใช้ในระบบ
| Moment | ห้ามใช้ | ใช้แทน |
|---|---|---|
| Empty State | "ไม่พบข้อมูล" | "ยังไม่มีงานในพื้นที่นี้ ลองเปลี่ยนพื้นที่การค้นหาดูนะ" |
| Loading | "กำลังโหลด..." | "กำลังเซาะหากิจกรรมให้..." |
| จองสำเร็จ | "ดำเนินการสำเร็จ" | "เจอแล้ว! เตรียมตัวให้พร้อมนะ" |
| Error | "เกิดข้อผิดพลาด" | "โอ๊ะ มีบางอย่างผิดพลาด กรุณาลองใหม่อีกครั้ง" |
| ไม่มีผลการค้นหา | "ไม่พบผลลัพธ์" | "หาไม่เจอ ลองเปลี่ยน Keyword ดูนะ" |

### UI Labels — ชื่อที่ใช้ใน Section และปุ่ม
| ห้ามใช้ | ใช้แทน |
|---|---|
| "Browse by category" | "เลือกตามหมวดหมู่" |
| "View all" | "ดูทั้งหมด →" |
| "Popular Events" | "กำลังมาแรง" |
| "Read more" | "อ่านต่อ" |
| "Stories & guides" | "บทความและไอเดีย" |

---

## Colors

### Primary Scale
โทนน้ำเงินหลักของ Sohhaa สื่อถึงความน่าเชื่อถือและความทันสมัย

| Token | Hex | การใช้งาน |
|---|---|---|
| `primary-900` | `#031123` | Dark backgrounds, high-contrast text |
| `primary-800` | `#13385f` | Dark UI elements |
| `primary-700` | `#1f5288` | Dark interactive states |
| `primary-600` | `#2b6baf` | Active nav, strong accents |
| `primary-500` | `#3682d2` | Supporting actions |
| `primary` | `#3e93ed` | Primary buttons, links, active states |
| `primary-hover` | `#75a9f4` | Hovered buttons, pressed states |
| `primary-300` | `#a3c2f7` | Focus rings, selected backgrounds |
| `primary-200` | `#d0defb` | Subtle highlights |
| `primary-100` | `#ebf1fd` | Background tints, chip fills |

### Neutral
โครงสร้างหน้าและข้อความ

| Token | Hex | การใช้งาน |
|---|---|---|
| `text-primary` | `#232323` | Headings, body copy, event titles |
| `text-secondary` | `#394956` | Descriptions, timestamps, secondary info |
| `text-tertiary` | `#94A1B1` | Placeholder, disabled text, icons |
| `border` | `#F2F3F7` | Card borders, input outlines, dividers |
| `background` | `#fbfbfb` | Page background |
| `surface` | `#FFFFFF` | Cards, modals, panels |

### Semantic
สีสื่อความหมายสำหรับสถานะต่างๆ

| Token | Hex | การใช้งาน |
|---|---|---|
| `success-dark` | `#23633E` | Success icons, dark emphasis |
| `success` | `#228350` | จองสำเร็จ, เช็คอินผ่าน, ยืนยันแล้ว |
| `success-light` | `#E4FBE7` | Success backgrounds |
| `success-subtle` | `#F0FDFC` | Subtle success tints |
| `success-muted` | `#F9FDFC` | Lightest success fill |
| `warning` | `#FFD56E` | ที่นั่งใกล้เต็ม, รอยืนยัน, แจ้งเตือน |
| `warning-light` | `#FFF7E4` | Warning backgrounds |
| `warning-subtle` | `#FEFDF4` | Subtle warning tints |
| `error` | `#E62F29` | จองไม่สำเร็จ, ฟอร์มผิดพลาด, ยกเลิก |
| `error-light` | `#FFE4E1` | Error backgrounds |
| `error-subtle` | `#FDF8F5` | Subtle error tints |

---

## Typography

### Fonts
- **ภาษาอังกฤษ / ตัวเลข**: Red Hat Display — โหลดจาก Google Fonts
- **ภาษาไทย**: Anuphan (Anuphan) — self-hosted

```css
@import url('https://fonts.googleapis.com/css2?family=Red+Hat+Display:wght@400;500;600;700&display=swap');
@font-face {
  font-family: 'Anuphan';
  src: url('/fonts/Anuphan.woff2') format('woff2');
}
```

**Red Hat Display** ให้ความรู้สึก Modern และ Approachable เหมาะกับ Heading และ UI Label ภาษาอังกฤษ
**Anuphan** เป็นฟอนต์มีหัวที่อ่านง่ายบน Screen รองรับทุก Weight และแสดงผลชัดเจนทุกขนาด

### Type Scale

| ชื่อ | Size | Weight | Font | Line Height | Letter Spacing |
|---|---|---|---|---|---|
| Display | 40px | 700 | Red Hat Display | 1.2 | -0.02em |
| H1 | 32px | 700 | Red Hat Display / Anuphan | 1.5 | -0.01em / 0em |
| H2 | 24px | 700 | Red Hat Display / Anuphan | 1.4 | -0.01em / 0em |
| H3 | 20px | 600 | Red Hat Display / Anuphan | 1.4 | -0.01em / 0em |
| Body | 16px | 400 | Anuphan | 1.6 | 0em |
| Body Medium | 16px | 500 | Anuphan | 1.6 | 0em |
| Body Small | 14px | 400 | Anuphan | 1.6 | 0em |
| Caption | 12px | 500 | Anuphan | 1.5 | 0.01em |
| Button | 15px | 600 | Red Hat Display | 1.0 | 0em |

### กฎการใช้งาน
- ประโยคผสมไทย-อังกฤษ ให้ใช้ **Anuphan เป็นหลัก**
- ชื่อ Brand, UI Label ภาษาอังกฤษล้วน และชื่อปุ่ม ใช้ **Red Hat Display**
- ตัวเลขสำคัญ เช่น ราคา, จำนวนที่นั่ง ใช้ **Red Hat Display weight 600** เพื่อความชัดเจน
- ห้ามผสมสองฟอนต์ในคำหรือประโยคเดียวกัน

---

## Spacing
Base unit คือ **4px** ใช้ Multiplier ตามลำดับนี้

| Token | Size | ใช้กับ |
|---|---|---|
| `space-1` | 4px | Icon padding, inline gap |
| `space-2` | 8px | ระยะห่างภายใน Chip, Badge |
| `space-3` | 12px | Padding ภายใน Button เล็ก |
| `space-4` | 16px | Padding มาตรฐาน, List row |
| `space-5` | 20px | Card padding, Input padding |
| `space-6` | 24px | ระยะห่างระหว่าง Section ย่อย |
| `space-8` | 32px | ระยะห่างระหว่าง Component |
| `space-10` | 40px | Section padding บน Mobile |
| `space-12` | 48px | ระยะห่างระหว่าง Section หลัก |
| `space-16` | 64px | Hero section padding |

**Container**
- Max width: `1200px` centered
- Side padding: `24px` (Mobile), `48px` (Desktop)
- Card grid gap: `16px`

---

## Border Radius

| Size | ใช้กับ |
|---|---|
| `4px` | Chip, Badge, Checkbox, Tag เล็ก |
| `8px` | Button, Input, Search bar |
| `12px` | Card, Dropdown, Event tile |
| `16px` | Modal, Bottom sheet, Hero card |
| `9999px` | Avatar, Status dot, Icon container กลม |

---

## Elevation
ใช้แนวทาง Flat เป็นหลัก เน้น Border แทน Shadow ในส่วนที่ข้อมูลหนาแน่น

| Level | Shadow | ใช้กับ |
|---|---|---|
| 0 | ไม่มี | Content ทั่วไป, Table row |
| 1 | `0 1px 3px rgba(3,17,35,0.06)` | Card, Event tile |
| 2 | `0 4px 12px rgba(3,17,35,0.08)` | Dropdown, Popover, Search result |
| 3 | `0 12px 24px rgba(3,17,35,0.12)` | Modal, Bottom sheet |

---

## Components

### Button
- Height: `44px` (มาตรฐาน), `36px` (เล็ก), `52px` (ใหญ่)
- Padding: `10px 20px`
- Border radius: `8px`
- Font: Red Hat Display 600, 15px
- Min width: `100px`

| Variant | Background | Text | Border |
|---|---|---|---|
| Primary | `#3e93ed` | `#FFFFFF` | — |
| Primary Hover | `#75a9f4` | `#FFFFFF` | — |
| Secondary | `#FFFFFF` | `#232323` | 1px `#D1D5DB` |
| Ghost | transparent | `#3e93ed` | — |
| Danger | `#E62F29` | `#FFFFFF` | — |
| Disabled | 40% opacity | — | — |

### Card
- Background: `#FFFFFF`
- Border: 1px `#D1D5DB`
- Border radius: `12px`
- Padding: `20px`
- Hover: border-color `#3e93ed`
- Shadow: ไม่มี

### Event Card
- Background: `#FFFFFF`
- Border: 1px `#D1D5DB`
- Border radius: `12px`
- Shadow: ไม่มี
- Overflow: hidden (รูปภาพชิดขอบ)
- Padding ส่วนข้อมูล: `16px`

**Cover Image Rules (สำคัญ)**
- ต้องใช้รูปภาพจริงจาก Organizer เสมอ
- ห้ามใช้ Gradient สี หรือ Solid Color แทนรูปภาพ
- ห้ามสร้าง Placeholder ที่มีชื่องานหรือข้อความซ้อนบนพื้นสี
- Cover Image height: `180px`, object-fit: cover, width: 100%

**Cover Image Fallback (เฉพาะกรณีไม่มีรูปจริงเท่านั้น)**
- Background: `#F2F3F7`
- แสดง Icon Ticket กลาง Card
- Icon สี `#94A1B1`, ขนาด `48px`
- ห้ามใช้ Gradient หรือสีอื่นแทน

**Layout**
- Category Tag: มุมซ้ายบนของรูป, offset `12px`
- Favorite Button: วงกลม `32px`, bg white, มุมขวาบน
- วันที่: Caption สี `#3e93ed`, uppercase
- ชื่องาน: H3, max 2 บรรทัด
- สถานที่และสถานะ: Body Small + Icon นำ
- ราคา: Body Medium Bold, Red Hat Display, ขวาล่าง

### Blog / Story Card
- Background: `#FFFFFF`
- Border: 1px `#D1D5DB`
- Border radius: `12px`
- Shadow: ไม่มี
- Overflow: hidden

**Cover Image**
- Height: `200px` (fixed ทุก Card ห้ามยืดหดตามรูปจริง)
- object-fit: cover
- width: 100%

**Layout**
- Category Tag: ใต้รูป ก่อนชื่อบทความ
- ชื่อบทความ: H3, max 2 บรรทัด
- คำอธิบาย: Body Small, max 2 บรรทัด, สี `#394956`

### Input
- Height: `44px`
- Padding: `10px 14px`
- Border radius: `8px`
- Border: 1px `#F2F3F7`
- Font: Anuphan 400, 16px
- Focus: 2px `#3e93ed`, ring 4px `#3e93ed` 10% opacity
- Error: 1px `#E62F29`
- Placeholder color: `#94A1B1`

### Chip / Tag
- Height: `28px`
- Padding: `0 10px`
- Border radius: `4px`
- Font: Anuphan 500, 13px

> ⚠️ Tag มี 2 ประเภท ห้ามใช้สลับกัน

**Category Tag — ประเภทกิจกรรม**
- Background: `#F2F3F7`
- Text: `#394956`
- Border: ไม่มี
- ใช้กับ: Concert, Workshop, Business, Sport ฯลฯ
- ใช้สีเดียวทั้งหมดไม่ว่าจะมีกี่ประเภท
- ตำแหน่ง: มุมซ้ายบนของ Cover Image

**Status Tag — สถานะของงาน (Text Only ไม่มีพื้นหลัง)**
- Font: Anuphan 600, 12px
- Background: ไม่มี
- Border: ไม่มี
- ตำแหน่ง: หน้ารายละเอียดคำสั่งซื้อเท่านั้น
- ห้ามแสดงบน Event Card หน้าแรก หรือ Listing Page

| Variant | Text Color | ใช้กับ |
|---|---|---|
| Warning | `#FEC748` | เหลือน้อย, ใกล้เต็ม |
| Error | `#D21B15` | เต็มแล้ว, ปิดรับ |
| Neutral | `#394956` | New |

### Navigation
- Top bar height: `60px`
- Background: `#FFFFFF`
- Bottom border: 1px `#F2F3F7`
- Logo: ซ้าย
- Nav links: กลาง, Anuphan 500, 15px
- CTA: ขวา
- Active state: `#3e93ed` text + 2px bottom border

**Responsive Behavior**
- Desktop (1024px+): แสดง Nav Links เต็ม ไม่มี Hamburger
- Tablet (768px–1023px): แสดง Nav Links เต็มถ้าพื้นที่พอ
- Mobile (< 768px): แสดง Hamburger Menu แทน Nav Links

### Check-in Badge (Organizer-specific)
Component พิเศษสำหรับหน้างาน แสดงผลขนาดใหญ่บน Mobile

- ✅ เช็คอินแล้ว: Background `#E4FBE7`, text `#228350`, ตัวเลขขนาด Display
- ❌ ยังไม่มา: Background `#FFE4E1`, text `#E62F29`
- ⏳ รอยืนยัน: Background `#FFF7E4`, text `#FFD56E`

---

## Brand Illustration

### Journey Path (Decorative Element)
เส้นเดียววิ่งต่อเนื่องตลอดหน้า โค้งงอเป็น Shape ที่สื่อความหมายของแต่ละ Section
สื่อถึงการเดินทางและการเซาะหากิจกรรมของ Sohhaa

**Style**
- รูปแบบ: Single continuous line art
- สี: `#d0defb` (Primary-200)
- ความหนา: 4px
- เส้นโค้ง Organic ดูพริ้วไหว ไม่ใช่เส้นตรง
- ซ่อนบน Mobile (< 768px)
- เป็น SVG decorative ไม่ใช่ Interactive element
- ห้ามทับ Content หลัก

**เส้นแปลงร่างตาม Section**
| Section | รูปที่เส้นแปลงเป็น |
|---|---|
| 2. Hero Section | จุดเริ่มต้น ออกจากมุมซ้ายบน โค้งลงมา |
| 3. Search Bar | รูปแว่นขยาย |
| 4. Browse by Category | เส้นโค้งผ่านเฉยๆ |
| 5. อีเวนต์มาแรง | รูปเปลวไฟ |
| 6. Billboard Banner | เส้นโค้งผ่านเฉยๆ |
| 7. Organizer CTA | รูปดาว |
| 8. บทความและไอเดีย | รูปดินสอ แล้วเส้นจบลง |

## Page Structure

### หน้าแรก (Home)
เรียงตามลำดับจากบนลงล่าง

1. **Navigation Bar** — Logo, Nav Links, Sign in, Create Event
2. **Hero Section** — Headline + Body + Buttons (ซ้าย) + Hero Banner Slider (ขวา)
3. **Search Bar** — ค้นหา, พื้นที่, ช่วงเวลา
4. **Browse by Category** — Filter หมวดหมู่
5. **อีเวนต์ที่กำลังมาแรง** — Event Card Grid 4 คอลัมน์
6. **Billboard Banner** — Full-width แบนเนอร์ event, height 200px, คลิกได้
7. **Organizer CTA** — Dark Section ชวนผู้จัดงาน
8. **บทความและไอเดีย** — Blog/Story Card Grid 3 คอลัมน์
9. **Footer** — Links, Logo, Copyright

> ⚠️ ห้ามเพิ่ม Section นอกเหนือจากนี้โดยไม่ได้รับการอนุมัติ
> ห้ามสลับลำดับ Section โดยไม่มีเหตุผลด้าน UX

### Hero Banner (Paid Placement)
- ตำแหน่ง: Hero Section ฝั่งขวา
- รูปแบบ: Image Slider แนวนอน
- ภาพ: Poster/Cover จาก Organizer เต็มพื้นที่ ไม่ใช่ Event Card
- ขนาดภาพ: 16:9 ratio, object-fit: cover
- Auto slide: ทุก 4-5 วินาที
- มี Dot indicator ด้านล่างบอกจำนวนงาน
- รองรับ Manual swipe บน Mobile
- คลิกแล้วไปหน้า Event Detail ของงานนั้น

### Hero Section Layout
**ฝั่งซ้าย — ประกอบด้วย**
- Badge/Tag เล็ก บอก Context เช่น "กำลังเซาะหากิจกรรมให้..."
- H1 Headline หลัก
- Body Text คำอธิบายสั้นๆ
- Button Group (Primary + Secondary)

**ห้ามมีใน Hero Section**
- Feature Highlights เช่น ✅ จองง่าย 🎟️ E-ticket 📍 ค้นหาตามพื้นที่
- Icon + Text บอก Feature ใดๆ ทั้งสิ้น

---

## Do's and Don'ts

**Do**
- ใช้ Anuphan สำหรับข้อความภาษาไทยทุกขนาด
- ใช้ Red Hat Display สำหรับ Heading, Button และตัวเลขสำคัญ
- ใช้ `success` (#228350) สำหรับสถานะสำเร็จและ `error` (#E62F29) สำหรับความผิดพลาด
- ใช้ Skeleton loading สำหรับข้อมูลที่โหลดจาก API

**Don't**
- อย่าใช้สี Primary (#3e93ed) สำหรับ Data visualization ให้ Reserve ไว้สำหรับ Interactive element
- อย่าผสม Red Hat Display และ Anuphan ในประโยคเดียวกัน
- อย่าใช้ฟอนต์ขนาดต่ำกว่า 12px บน Mobile
- อย่าใช้ Shadow ซ้อนกันหลายชั้น ให้เลือก Level ที่เหมาะสมเพียงชั้นเดียว
- อย่าใช้สี Semantic (Success/Warning/Error) เพื่อความสวยงาม ใช้เฉพาะสื่อสถานะจริงเท่านั้น
