# โปรแกรมคำนวณราคาเครื่องเขียนรวมค่าส่ง #
ร้านจำหน่ายเครื่องเขียนพร้อมส่งแห่งหนึ่งจัดโปรโมชั่นพิเศษ    
สำหรับปากกาเมจิก โดยปากกาเมจิกจะขายในราคากล่องละ 350 บาท
ซื้อ 3  กล่องขึ้นไป ลด 10% ซื้อ 5 กล่องขึ้นไป ลด 20% และซื้อ 4 แถม 1
สำหรับการจัดส่งหากส่งแบบ EMS จะเสียค่าจัดส่งออเดอร์ละ 60 บาท
กล่องต่อไปคิดเพิ่ม 10 บาท ส่วนการจัดส่งแบบ REG จะเสียค่าจัดส่งออเดอร์ละ
30 บาท กล่องต่อไปคิดเพิ่ม 10 บาท โดย 1 ออเดอร์ สามารถบรรจุได้ไม่เกิน
10 กล่อง และผู้ซื้อสามารถสั่งซื้อสิ้นค้าได้ไม่เกิน 40 กล่อง

---
**หมายเหตุ:**
1. 1 ออเดอร์ ไม่เกิน 10 กล่อง คือสมมติว่าผู้ซื้อ ซื้อปากกา 25 กล่อง   
และจัดส่งแบบ EMS จะต้องแยกเป็น 3 ออเดอร์ การคิดค่าส่งจะเป็นดังนี้
2. ออเดอร์ที่ 1 มี 10 กล่อง => กล่องแรกคิดค่าส่ง 60 บาท กล่องต่อไปคิดเพิ่ม
 10 บาท จะได้ 60+(9*10)=150บาท
3. ออเดอร์ที่ 2 มี 10 กล่อง => กล่องแรกคิดค่าส่ง 60 บาท กล่องต่อไปคิดเพิ่ม
 10 บาท จะได้ 60+(9*10)=150บาท   
4. ออเดอร์ที่ 3 มี 5 กล่อง => กล่องแรกคิดค่าส่ง 60 บาท กล่องต่อไปคิดเพิ่ม
 10 บาท จะได้ 60+(4*10)=100บาท   
**ดังนั้น:**
ผู้ซื้อต้องจ่ายค่าส่ง 150+150+100 = 400 บาท
---
จงเขียนโปรแกรมเพื่อแสดงจำนวนออเดอร์ ราคาเต็มพร้อมค่าส่ง ส่วนลด ราคาที่ต้องจ่ายจริง และจำนวนของแถม หากข้อมูลเข้าผิดพลาดให้แสดงผล Invalid! Try again.
---

### **ตัวอย่าง** **input** **output**

```
--input--
Enter your quantity:  18
Select your shipping method:
1.EMS.
2.REG.
Enter your shipping method 1 or 2:  2

--output--
You have 2 order.
Your full price with delivery fee is 6520 baht.
Your discount is 1260 baht.
Total amount is 5260 baht.
You got free gift 4 pcs.
```

```
--input--
Enter your quantity:  -4
Select your shipping method:
1.EMS.
2.REG.
Enter your shipping method 1 or 2:  2

--output--
Invalid! Try again.
```
