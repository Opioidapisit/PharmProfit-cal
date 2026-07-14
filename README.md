# เว็บไซต์เครื่องคำนวณกำไรร้านยา

## โครงสร้างไฟล์

```text
calpharm-website/
├── index.html
└── images/
    ├── logo.png
    └── giraffe-mascot.png
```

## วิธีเปลี่ยนโลโก้

นำรูปโลโก้ใหม่มาแทนไฟล์:

`images/logo.png`

ควรใช้ไฟล์ PNG พื้นหลังโปร่งใสหรือสีขาว และแนะนำให้เป็นรูปสี่เหลี่ยมจัตุรัส

## วิธีเปลี่ยนมาสคอตยีราฟ

นำรูปมาสคอตใหม่มาแทนไฟล์:

`images/giraffe-mascot.png`

ควรใช้ไฟล์ PNG พื้นหลังโปร่งใส

## วิธีเปลี่ยนขนาดรูป

เปิด `index.html` แล้วค้นหา CSS ต่อไปนี้:

โลโก้:

```css
.mark {
  width: 52px;
  height: 52px;
}
```

มาสคอต:

```css
.mascot {
  width: 64px;
  height: 64px;
}
```

## การนำขึ้น GitHub Pages

1. อัปโหลด `index.html` และโฟลเดอร์ `images` ไปไว้ใน Repository เดียวกัน
2. ไปที่ Settings > Pages
3. เลือก Deploy from a branch
4. เลือก branch `main` และโฟลเดอร์ `/ (root)`
5. กด Save

ห้ามเปลี่ยนตำแหน่งโฟลเดอร์ `images` โดยไม่แก้เส้นทางรูปใน `index.html`
