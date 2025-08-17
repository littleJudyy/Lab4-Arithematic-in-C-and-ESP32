```
### 📝 แบบฝึกหัดที่ 1: เปลี่ยนจำนวนถุงลูกอม
// หาบรรทัดนี้ในโค้ด:
int candy_bags = 5;         // จำนวนถุง
int candies_per_bag = 6;    // ลูกอมต่อถุง

// ลองเปลี่ยนเป็น:
int candy_bags = 7;         // เพิ่มเป็น 7 ถุง
int candies_per_bag = 8;    // ลูกอมถุงละ 8 เม็ด
```
```
I (2522) CANDIES_MATH: 🍬 เริ่มต้นโปรแกรมนับลูกอมในถุง 🍬
I (2522) CANDIES_MATH: ====================================
I (2522) CANDIES_MATH: 📖 โจทย์:
I (2522) CANDIES_MATH:    มีถุงลูกอม: 7 ถุง
I (2522) CANDIES_MATH:    ถุงละ: 8 เม็ด
I (2522) CANDIES_MATH:    ❓ มีลูกอมทั้งหมดกี่เม็ด?
I (2522) CANDIES_MATH: 
I (5522) CANDIES_MATH: 🧮 ขั้นตอนการคิด:
I (5522) CANDIES_MATH:    จำนวนถุง × ลูกอมต่อถุง
I (5522) CANDIES_MATH:    = 7 × 8
I (5522) CANDIES_MATH:    = 56 เม็ด
I (5522) CANDIES_MATH: 
I (5522) CANDIES_MATH: ✅ คำตอบ:
I (5522) CANDIES_MATH:    มีลูกอมทั้งหมด 56 เม็ด
I (5522) CANDIES_MATH: 
I (5522) CANDIES_MATH: 🎨 ภาพประกอบ:
I (5522) CANDIES_MATH:    ถุงที่ 1: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5522) CANDIES_MATH:    ถุงที่ 2: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5522) CANDIES_MATH:    ถุงที่ 3: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5522) CANDIES_MATH:    ถุงที่ 4: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5522) CANDIES_MATH:    ถุงที่ 5: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5522) CANDIES_MATH:    รวม:     56 เม็ด
I (5522) CANDIES_MATH: 
I (5522) CANDIES_MATH: 🔄 เปรียบเทียบกับการบวกซ้ำๆ:
I (5522) CANDIES_MATH:    การคูณ: 7 × 8 = 56
I (5522) CANDIES_MATH:    การบวกซ้ำๆ:
I (5522) CANDIES_MATH:                   8
I (5522) CANDIES_MATH:                 + 8
I (5522) CANDIES_MATH:                 + 8
I (5522) CANDIES_MATH:                 + 8
I (5522) CANDIES_MATH:                 + 8
I (5522) CANDIES_MATH:                 + 8
I (5522) CANDIES_MATH:                 + 8 = 56
I (5522) CANDIES_MATH:    ผลลัพธ์เหมือนกัน! การคูณคือการบวกซ้ำๆ
I (5522) CANDIES_MATH: 
I (5522) CANDIES_MATH: 📊 ตารางสูตรคูณ 8:
I (5522) CANDIES_MATH:    1 × 8 = 8
I (5822) CANDIES_MATH:    2 × 8 = 16
I (6122) CANDIES_MATH:    3 × 8 = 24
I (6422) CANDIES_MATH:    4 × 8 = 32
I (6722) CANDIES_MATH:    5 × 8 = 40
I (7022) CANDIES_MATH:    6 × 8 = 48
I (7322) CANDIES_MATH:    7 × 8 = 56
I (7622) CANDIES_MATH:    8 × 8 = 64
I (7922) CANDIES_MATH:    9 × 8 = 72
I (8222) CANDIES_MATH:    10 × 8 = 80
I (8522) CANDIES_MATH: 
I (8522) CANDIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (8522) CANDIES_MATH:    ถ้ามีถุงลูกอม 3 ถุง ถุงละ 8 เม็ด
I (8522) CANDIES_MATH:    จะได้ลูกอม 3 × 8 = 24 เม็ด
I (8522) CANDIES_MATH: 
I (8522) CANDIES_MATH:    ถ้ามีถุงลูกอม 7 ถุง ถุงละ 4 เม็ด
I (8522) CANDIES_MATH:    จะได้ลูกอม 7 × 4 = 28 เม็ด
I (8522) CANDIES_MATH: 
I (8522) CANDIES_MATH: 🔄 เปรียบเทียบการดำเนินการ:
I (8522) CANDIES_MATH:    การบวก (+): เพิ่มจำนวน (เช่น ไข่ 4 + 2 = 6)
I (8522) CANDIES_MATH:    การลบ (-): ลดจำนวน (เช่น ของเล่น 8 - 3 = 5)
I (8522) CANDIES_MATH:    การคูณ (×): บวกซ้ำๆ (เช่น ลูกอม 5 × 6 = 30)
I (8522) CANDIES_MATH: 
I (8522) CANDIES_MATH: 🎓 แนวคิดขั้นสูง:
I (8522) CANDIES_MATH:    1. การคูณมีคุณสมบัติการสับเปลี่ยน:
I (8522) CANDIES_MATH:       7 × 8 = 8 × 7 = 56
I (8522) CANDIES_MATH:    2. การคูณด้วย 0 จะได้ 0 เสมอ:
I (8522) CANDIES_MATH:       7 × 0 = 0 (ไม่มีถุงลูกอม)
I (8532) CANDIES_MATH:    3. การคูณด้วย 1 จะได้ตัวเลขเดิม:
I (8532) CANDIES_MATH:       8 × 1 = 8 (มีถุงเดียว)
I (8532) CANDIES_MATH: 
I (8532) CANDIES_MATH: 📚 สิ่งที่เรียนรู้:
I (8532) CANDIES_MATH:    1. การคูณเลข (Multiplication): a × b = c
I (8532) CANDIES_MATH:    2. การใช้ for loop สำหรับการทำซ้ำ
I (8532) CANDIES_MATH:    3. ความสัมพันธ์ระหว่างการคูณและการบวกซ้ำๆ
I (8532) CANDIES_MATH:    4. คุณสมบัติพิเศษของการคูณ
I (8532) CANDIES_MATH:    5. การแสดงผลแบบตาราง
I (8532) CANDIES_MATH: 
I (8532) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (8532) CANDIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 04_division_cookies
I (10532) main_task: Returned from app_main()
```
