# Sohhaa Design System

## Overview
Sohhaa is an event discovery and management platform that connects event-goers with organizers in one seamless experience. The design system reflects the brand's core identity: **warm, approachable, and trustworthy** — easy enough for anyone to find and join an event, yet powerful enough for organizers to manage and grow their audience.

The aesthetic balances a clean, modern structure with friendly energy. Every component is designed to reduce friction — whether someone is browsing weekend activities or an organizer reviewing post-event analytics.

**Design Principles**
- **Clear over clever** — ข้อมูลต้องอ่านได้ทันที ไม่ต้องตีความ
- **Approachable** — ทุกคนใช้งานได้ ไม่ว่าจะ Tech-savvy แค่ไหน
- **Trustworthy** — ระบบจอง/ชำระเงินต้องดูน่าเชื่อถือทุกจุด
- **Responsive-first** — Mobile และ Web ต้องสมบูรณ์เท่ากัน

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

### Secondary
โทน Teal สำหรับ Element รองที่ไม่แย่งความสนใจจาก Primary

| Token | Hex | การใช้งาน |
|---|---|---|
| `secondary` | `#0D9488` | Secondary buttons, category tags, badges |
| `secondary-light` | `#CCFAF6` | Tag backgrounds, chip fills |

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
- **ภาษาไทย**: Sarabun — โหลดจาก Google Fonts

```css
@import url('https://fonts.googleapis.com/css2?family=Red+Hat+Display:wght@400;500;600;700&family=Sarabun:wght@400;500;600;700&display=swap');
```

**Red Hat Display** ให้ความรู้สึก Modern และ Approachable เหมาะกับ Heading และ UI Label ภาษาอังกฤษ
**Sarabun** เป็นฟอนต์มีหัวที่อ่านง่ายบน Screen รองรับทุก Weight และแสดงผลชัดเจนทุกขนาด

### Type Scale

| ชื่อ | Size | Weight | Font | Line Height | Letter Spacing |
|---|---|---|---|---|---|
| Display | 40px | 700 | Red Hat Display | 1.2 | -0.02em |
| H1 | 32px | 700 | Red Hat Display | 1.2 | -0.02em |
| H2 | 24px | 700 | Red Hat Display / Sarabun | 1.3 | -0.01em |
| H3 | 20px | 600 | Red Hat Display / Sarabun | 1.3 | 0em |
| Body | 16px | 400 | Sarabun | 1.6 | 0em |
| Body Medium | 16px | 500 | Sarabun | 1.6 | 0em |
| Body Small | 14px | 400 | Sarabun | 1.6 | 0em |
| Caption | 12px | 500 | Sarabun | 1.5 | 0.01em |
| Button | 15px | 600 | Red Hat Display | 1.0 | 0em |

### กฎการใช้งาน
- ประโยคผสมไทย-อังกฤษ ให้ใช้ **Sarabun เป็นหลัก**
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
| Secondary | `#FFFFFF` | `#232323` | 1px `#F2F3F7` |
| Ghost | transparent | `#3e93ed` | — |
| Danger | `#E62F29` | `#FFFFFF` | — |
| Disabled | 40% opacity | — | — |

### Card
- Background: `#FFFFFF`
- Border: 1px `#F2F3F7`
- Border radius: `12px`
- Padding: `20px`
- Hover: border-color `#3e93ed`
- Shadow: Level 1

**Event Card** แสดง: รูป Cover, ชื่อ Event (H3), วันเวลา (Body Small), สถานที่ (Body Small), ราคา (Body Medium, Red Hat Display), Badge ประเภทงาน

### Input
- Height: `44px`
- Padding: `10px 14px`
- Border radius: `8px`
- Border: 1px `#F2F3F7`
- Font: Sarabun 400, 16px
- Focus: 2px `#3e93ed`, ring 4px `#3e93ed` 10% opacity
- Error: 1px `#E62F29`
- Placeholder color: `#94A1B1`

### Chip / Tag
- Height: `28px`
- Padding: `0 10px`
- Border radius: `4px`
- Font: Sarabun 500, 13px

| Variant | Background | Text |
|---|---|---|
| Primary | `#ebf1fd` | `#3e93ed` |
| Secondary | `#CCFAF6` | `#0D9488` |
| Success | `#E4FBE7` | `#228350` |
| Warning | `#FFF7E4` | `#FFD56E` |
| Error | `#FFE4E1` | `#E62F29` |
| Neutral | `#F2F3F7` | `#394956` |

### Navigation
- Top bar height: `60px`
- Background: `#FFFFFF`
- Bottom border: 1px `#F2F3F7`
- Logo: ซ้าย
- Nav links: กลาง, Sarabun 500, 15px
- CTA: ขวา
- Active state: `#3e93ed` text + 2px bottom border

### Check-in Badge (Organizer-specific)
Component พิเศษสำหรับหน้างาน แสดงผลขนาดใหญ่บน Mobile

- ✅ เช็คอินแล้ว: Background `#E4FBE7`, text `#228350`, ตัวเลขขนาด Display
- ❌ ยังไม่มา: Background `#FFE4E1`, text `#E62F29`
- ⏳ รอยืนยัน: Background `#FFF7E4`, text `#FFD56E`

---

## Do's and Don'ts

**Do**
- ใช้ Sarabun สำหรับข้อความภาษาไทยทุกขนาด
- ใช้ Red Hat Display สำหรับ Heading, Button และตัวเลขสำคัญ
- ใช้ `success` (#228350) สำหรับสถานะสำเร็จและ `error` (#E62F29) สำหรับความผิดพลาด
- ใช้ Skeleton loading สำหรับข้อมูลที่โหลดจาก API

**Don't**
- อย่าใช้สี Primary (#3e93ed) สำหรับ Data visualization ให้ Reserve ไว้สำหรับ Interactive element
- อย่าผสม Red Hat Display และ Sarabun ในประโยคเดียวกัน
- อย่าใช้ฟอนต์ขนาดต่ำกว่า 12px บน Mobile
- อย่าใช้ Shadow ซ้อนกันหลายชั้น ให้เลือก Level ที่เหมาะสมเพียงชั้นเดียว
- อย่าใช้สี Semantic (Success/Warning/Error) เพื่อความสวยงาม ใช้เฉพาะสื่อสถานะจริงเท่านั้น
