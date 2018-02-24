# I want Menu


ร้านอาหารตามสั่งใส่ใจ สดใหม่ทุกวินาที ตั้งอยู่ในโรงอาหารของโรงพยาบาลแห่งหนึ่ง ซึ่งมีลูกค้าส่วนมากเป็นหมอในโรงพยาบาล ที่มักจะมาจดออเดอร์อาหารเพื่อนำไปรับประทานขณะหิว แล้วจากไปอย่างเร่งรีบ เชฟยิ่งเลิฟ มักจะเครียด เพราะอ่านลายมือของลูกค้าที่เป็นหมอไม่ค่อยออก จึงขอให้เราเขียนโปรแกรมรับออเดอร์จากลูกค้า
-	ส่วนแรกประกอบด้วย ชื่อเมนูและหมายเลขของเมนู
-	ระบบจะให้ใส่จำนวนเมนูทั้งหมดที่ต้องการ
-	ระบบจะให้ใส่เลขของเมนูที่ต้องการ
-	หากต้องการเมนูนั้นๆมากกว่าหนึ่งให้ใส่เลขนั้นซ้ำ


จากนั้นระบบจะแสดงรายการและจำนวนของแต่ละเมนู ให้เชฟได้ลงมือเตรียมอาหาร



##### ตัวอย่างที่ 1
```
               MENU
•Fried rice(1)      •Fried chicken(2)
•Noodle soup(3)     •Porridge with fish(4)
•Roast chicken(5)   •Rice topped with stir-fried pork and basil(6)
•Shark’s fin(7)     •Rice with roast duck(8)
How many you want : 3
Enter number[1]: 5
Enter number[2]: 5
Enter number[3]: 4
       Total
•Porridge with fish.  [1]
•Roast chicken.  [2]

```
##### ตัวอย่างที่ 2
```
               MENU
•Fried rice(1)      •Fried chicken(2)
•Noodle soup(3)     •Porridge with fish(4)
•Roast chicken(5)   •Rice topped with stir-fried pork and basil(6)
•Shark’s fin(7)     •Rice with roast duck(8)
How many you want : 1
Enter number[1]: 5
       Total
•Roast chicken.  [1]
```
##### ตัวอย่างที่ 3
```
               MENU
•Fried rice(1)      •Fried chicken(2)
•Noodle soup(3)     •Porridge with fish(4)
•Roast chicken(5)   •Rice topped with stir-fried pork and basil(6)
•Shark’s fin(7)     •Rice with roast duck(8)
How many you want : 5
Enter number[1]: 4
Enter number[2]: 3
Enter number[3]: 8
Enter number[4]: 7
Enter number[5]: 5
       Total
•Noodle soup.    [1]
•Porridge with fish.  [1]
•Roast chicken.  [1]
•Shark’s fin.    [1]
•Rice with roast duck.   [1]
```