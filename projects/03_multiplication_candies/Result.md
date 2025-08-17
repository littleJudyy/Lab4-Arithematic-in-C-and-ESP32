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
```
### 📝 แบบฝึกหัดที่ 2: เพิ่มลูกอมหลายรส
เพิ่มลูกอมหลายรส:
int strawberry_bags = 3;    // ถุงรสสตรอเบอร์รี่
int orange_bags = 2;        // ถุงรสส้ม
int grape_bags = 4;         // ถุงรสองุ่น

int total_bags = strawberry_bags + orange_bags + grape_bags;
int total_candies = total_bags * candies_per_bag;

ESP_LOGI(TAG, "🍓 สตรอเบอร์รี่: %d ถุง = %d เม็ด", 
         strawberry_bags, strawberry_bags * candies_per_bag);
ESP_LOGI(TAG, "🍊 รสส้ม: %d ถุง = %d เม็ด", 
         orange_bags, orange_bags * candies_per_bag);
ESP_LOGI(TAG, "🍇 รสองุ่น: %d ถุง = %d เม็ด", 
         grape_bags, grape_bags * candies_per_bag);
```
```
I (2457) CANDIES_MATH: 🍬 เริ่มโปรแกรมนับลูกอมหลายรส 🍬
I (2457) CANDIES_MATH: ====================================
I (2457) CANDIES_MATH: 🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (2457) CANDIES_MATH: 🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (2457) CANDIES_MATH: 🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (2457) CANDIES_MATH: 🍬 รวมทั้งหมด: 9 ถุง = 72 เม็ด
I (2457) CANDIES_MATH: 
I (4457) CANDIES_MATH: 🔄 เปรียบเทียบการคูณกับการบวกซ้ำๆ:
I (4457) CANDIES_MATH: 🍓 สตรอเบอร์รี่:
I (4457) CANDIES_MATH:    + 8
I (4457) CANDIES_MATH:    + 8
I (4457) CANDIES_MATH:    + 8 = 24
I (4457) CANDIES_MATH: 🍊 รสส้ม:
I (4457) CANDIES_MATH:    + 8
I (4457) CANDIES_MATH:    + 8 = 16
I (4457) CANDIES_MATH: 🍇 รสองุ่น:
I (4457) CANDIES_MATH:    + 8
I (4457) CANDIES_MATH:    + 8
I (4457) CANDIES_MATH:    + 8
I (4457) CANDIES_MATH:    + 8 = 32
I (4457) CANDIES_MATH: ✅ การคูณและการบวกซ้ำๆ ให้ผลเหมือนกัน
I (4457) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมหลายรส!
I (4457) main_task: Returned from app_main()
```
```
แบบฝึกหัดที่ 3: สร้างตารางสูตรคูณ
เพิ่มการแสดงตารางสูตรคูณ:
ESP_LOGI(TAG, "📊 ตารางสูตรคูณของ %d:", candies_per_bag);
for (int i = 1; i <= 10; i++) {
    ESP_LOGI(TAG, "   %d x %d = %d", i, candies_per_bag, i * candies_per_bag);
}
```
```
I (2862) main_task: Calling app_main()
I (2862) CANDIES_MATH: 🍬 เริ่มโปรแกรมนับลูกอมหลายรส 🍬
I (2862) CANDIES_MATH: ====================================
I (2862) CANDIES_MATH: 🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (2862) CANDIES_MATH: 🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (2862) CANDIES_MATH: 🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (2862) CANDIES_MATH: 🍬 รวมทั้งหมด: 9 ถุง = 72 เม็ด
I (2862) CANDIES_MATH: 
I (4862) CANDIES_MATH: 🔄 เปรียบเทียบการคูณกับการบวกซ้ำๆ:
I (4862) CANDIES_MATH: 🍓 สตรอเบอร์รี่:
I (4862) CANDIES_MATH:    + 8
I (4862) CANDIES_MATH:    + 8
I (4862) CANDIES_MATH:    + 8 = 24
I (4862) CANDIES_MATH: 🍊 รสส้ม:
I (4862) CANDIES_MATH:    + 8
I (4862) CANDIES_MATH:    + 8 = 16
I (4862) CANDIES_MATH: 🍇 รสองุ่น:
I (4862) CANDIES_MATH:    + 8
I (4862) CANDIES_MATH:    + 8
I (4862) CANDIES_MATH:    + 8
I (4862) CANDIES_MATH:    + 8 = 32
I (4862) CANDIES_MATH: ✅ การคูณและการบวกซ้ำๆ ให้ผลเหมือนกัน
I (4862) CANDIES_MATH: 
I (6862) CANDIES_MATH: 📊 ตารางสูตรคูณของ สตรอเบอร์รี่ (8 เม็ดต่อถุง):
I (6862) CANDIES_MATH:    1 x 8 = 8
I (7062) CANDIES_MATH:    2 x 8 = 16
I (7262) CANDIES_MATH:    3 x 8 = 24
I (7462) CANDIES_MATH:    4 x 8 = 32
I (7662) CANDIES_MATH:    5 x 8 = 40
I (7862) CANDIES_MATH:    6 x 8 = 48
I (8062) CANDIES_MATH:    7 x 8 = 56
I (8262) CANDIES_MATH:    8 x 8 = 64
I (8462) CANDIES_MATH:    9 x 8 = 72
I (8662) CANDIES_MATH:    10 x 8 = 80
I (8862) CANDIES_MATH: 📊 ตารางสูตรคูณของ ส้ม (8 เม็ดต่อถุง):
I (8862) CANDIES_MATH:    1 x 8 = 8
I (9062) CANDIES_MATH:    2 x 8 = 16
I (9262) CANDIES_MATH:    3 x 8 = 24
I (9462) CANDIES_MATH:    4 x 8 = 32
I (9662) CANDIES_MATH:    5 x 8 = 40
I (9862) CANDIES_MATH:    6 x 8 = 48
I (10062) CANDIES_MATH:    7 x 8 = 56
I (10262) CANDIES_MATH:    8 x 8 = 64
I (10462) CANDIES_MATH:    9 x 8 = 72
I (10662) CANDIES_MATH:    10 x 8 = 80
I (10862) CANDIES_MATH: 📊 ตารางสูตรคูณของ องุ่น (8 เม็ดต่อถุง):
I (10862) CANDIES_MATH:    1 x 8 = 8
I (11062) CANDIES_MATH:    2 x 8 = 16
I (11262) CANDIES_MATH:    3 x 8 = 24
I (11462) CANDIES_MATH:    4 x 8 = 32
I (11662) CANDIES_MATH:    5 x 8 = 40
I (11862) CANDIES_MATH:    6 x 8 = 48
I (12062) CANDIES_MATH:    7 x 8 = 56
I (12262) CANDIES_MATH:    8 x 8 = 64
I (12462) CANDIES_MATH:    9 x 8 = 72
I (12662) CANDIES_MATH:    10 x 8 = 80
I (12862) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมหลายรส!
I (12862) main_task: Returned from app_main()
```
```
แบบฝึกหัดที่ 4: แจกลูกอมให้เพื่อน
คำนวณการแจกลูกอม:
int friends = 12;           // จำนวนเพื่อน
int candies_per_friend = total_candies / friends;  // ลูกอมต่อคน
int remaining_candies = total_candies % friends;   // ลูกอมที่เหลือ

ESP_LOGI(TAG, "👥 แจกให้เพื่อน %d คน:", friends);
ESP_LOGI(TAG, "   คนละ %d เม็ด", candies_per_friend);
ESP_LOGI(TAG, "   เหลือ %d เม็ด", remaining_candies);
```
```
I (2405) CANDIES_MATH: 🍬 เริ่มโปรแกรมนับลูกอมหลายรส 🍬
I (2405) CANDIES_MATH: ====================================
I (2405) CANDIES_MATH: 🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (2405) CANDIES_MATH: 🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (2405) CANDIES_MATH: 🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (2405) CANDIES_MATH: 🍬 รวมทั้งหมด: 9 ถุง = 72 เม็ด
I (2405) CANDIES_MATH: 
I (4405) CANDIES_MATH: 🔄 เปรียบเทียบการคูณกับการบวกซ้ำๆ:
I (4405) CANDIES_MATH: 🍓 สตรอเบอร์รี่:
I (4405) CANDIES_MATH:    + 8
I (4405) CANDIES_MATH:    + 8
I (4405) CANDIES_MATH:    + 8 = 24
I (4405) CANDIES_MATH: 🍊 รสส้ม:
I (4405) CANDIES_MATH:    + 8
I (4405) CANDIES_MATH:    + 8 = 16
I (4405) CANDIES_MATH: 🍇 รสองุ่น:
I (4405) CANDIES_MATH:    + 8
I (4405) CANDIES_MATH:    + 8
I (4405) CANDIES_MATH:    + 8
I (4405) CANDIES_MATH:    + 8 = 32
I (4405) CANDIES_MATH: ✅ การคูณและการบวกซ้ำๆ ให้ผลเหมือนกัน
I (4405) CANDIES_MATH: 
I (6405) CANDIES_MATH: 📊 ตารางสูตรคูณของ สตรอเบอร์รี่ (8 เม็ดต่อถุง):
I (6405) CANDIES_MATH:    1 x 8 = 8
I (6605) CANDIES_MATH:    2 x 8 = 16
I (6805) CANDIES_MATH:    3 x 8 = 24
I (7005) CANDIES_MATH:    4 x 8 = 32
I (7205) CANDIES_MATH:    5 x 8 = 40
I (7405) CANDIES_MATH:    6 x 8 = 48
I (7605) CANDIES_MATH:    7 x 8 = 56
I (7805) CANDIES_MATH:    8 x 8 = 64
I (8005) CANDIES_MATH:    9 x 8 = 72
I (8205) CANDIES_MATH:    10 x 8 = 80
I (8405) CANDIES_MATH: 📊 ตารางสูตรคูณของ ส้ม (8 เม็ดต่อถุง):
I (8405) CANDIES_MATH:    1 x 8 = 8
I (8605) CANDIES_MATH:    2 x 8 = 16
I (8805) CANDIES_MATH:    3 x 8 = 24
I (9005) CANDIES_MATH:    4 x 8 = 32
I (9205) CANDIES_MATH:    5 x 8 = 40
I (9405) CANDIES_MATH:    6 x 8 = 48
I (9605) CANDIES_MATH:    7 x 8 = 56
I (9805) CANDIES_MATH:    8 x 8 = 64
I (10005) CANDIES_MATH:    9 x 8 = 72
I (10205) CANDIES_MATH:    10 x 8 = 80
I (10405) CANDIES_MATH: 📊 ตารางสูตรคูณของ องุ่น (8 เม็ดต่อถุง):
I (10405) CANDIES_MATH:    1 x 8 = 8
I (10605) CANDIES_MATH:    2 x 8 = 16
I (10805) CANDIES_MATH:    3 x 8 = 24
I (11005) CANDIES_MATH:    4 x 8 = 32
I (11205) CANDIES_MATH:    5 x 8 = 40
I (11405) CANDIES_MATH:    6 x 8 = 48
I (11605) CANDIES_MATH:    7 x 8 = 56
I (11805) CANDIES_MATH:    8 x 8 = 64
I (12005) CANDIES_MATH:    9 x 8 = 72
I (12205) CANDIES_MATH:    10 x 8 = 80
I (14405) CANDIES_MATH: 👥 แจกให้เพื่อน 12 คน:
I (14405) CANDIES_MATH:    คนละ 6 เม็ด
I (14405) CANDIES_MATH:    เหลือ 0 เม็ด
I (14405) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมหลายรสและแจกเพื่อน!
I (14405) main_task: Returned from app_main()
```
