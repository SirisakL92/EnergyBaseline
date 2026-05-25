# Energy Baseline — Multi-Month Analyzer

เครื่องมือวิเคราะห์ Energy Baseline ตามมาตรฐาน ISO 50001 / EnMS / IPMVP

## คุณสมบัติ

- นำเข้าไฟล์ Excel (F-RCMDS-C-015) ได้หลายไฟล์พร้อมกัน
- รองรับวันที่แบบพุทธศักราช (Thai Buddhist Era)
- Simple & Multiple Linear Regression (OLS)
- สถิติ: R², Adjusted R², CV(RMSE), F-statistic, P-Value, CUSUM
- วิเคราะห์รวม / แยกรายเดือน / เปรียบเทียบข้ามเดือน
- วิเคราะห์สัดส่วนการผลิตตามเบอร์ยาง + kWh/kg
- เปรียบเทียบสัดส่วนการผลิตรายเดือน
- Idle Time Analysis + Anomaly Detection (IQR)
- Export Excel

## วิธีใช้งาน

1. เปิด [https://YOUR_USERNAME.github.io/YOUR_REPO/](https://YOUR_USERNAME.github.io/YOUR_REPO/)
2. ลากวางไฟล์ Excel (.xlsx) หรือคลิกเลือกไฟล์
3. เลือกช่วงเดือน → กดวิเคราะห์

## ไฟล์

- `index.html` — ไฟล์หลักสำหรับ GitHub Pages (ไฟล์เดียว ไม่ต้องติดตั้งอะไรเพิ่ม)

## การตั้งค่า GitHub Pages

1. สร้าง Repository ใหม่บน GitHub
2. อัปโหลดไฟล์ `index.html` และ `README.md`
3. ไปที่ Settings → Pages → Source: Deploy from a branch → Branch: main → Save
4. รอ 1-2 นาที แล้วเปิดลิงก์ที่แสดง
