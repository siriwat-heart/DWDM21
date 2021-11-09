# DWDM21
Data Warehouse &amp; Data Mining 2021

ศิริวัฒน์ ภูลำสัตย์ 623020765-0

Group Name : Numberone

1 **นายศิริวัฒน์ ภูลำสัตย์ 623020765-0**

2 นางสาวเบญญาภา ระภูเขียว 623020527-6

3 นางสาววนิศรา จงใจ 623021054-8

4 นายธนิก พิมภิบาล 623021049-1	

5 นายวิฆเนศ เกียรติเกษมสุข 623021055-6	

# สารบัญเนื้อหา
## บทที่ 1
* [introduction](https://github.com/siriwat-heart/DWDM21/blob/main/HW1)
  * ความหมายเเละนิยามของ Data Mining
  * ขั้นตอนเเละองค์ประกอบของ Data Mining
  * knowledge discovery (kdd) process
  * Multi-Dimensional View of Data Mining
## บทที่ 2
#### Lecture
   * [สรุปการบ้านคาบ 1 Know your data](https://github.com/siriwat-heart/DWDM21/blob/main/HW2.1)
     * ขนาดของข้อมูล
     * คุณสมบัติของ matrix
     * ประเภทของชุดข้อมูล : การบันทึกข้อมูล
     * ประเภทของชุดข้อมูล : กราฟเเละเครือข่าย
     * ประเภทของชุดข้อมูล : Ordered Data
     * ประเภทของชุดข้อมูล : ข้อมูลเชิงพื้นที่ ภาพ เเละมัลติมีเดีย
     * ลักษณะสำคัญของข้อมูล
     * ข้อมูลที่เป็นตัวเลข
#### Googlecolab  
   * know your data ประกอบไปด้วย 3 ส่วยย่อย
     * [Basic Python](https://github.com/siriwat-heart/DWDM21/blob/main/Data101(chapter2).ipynb)
       * Casting
       * Data Structure
       * Loop
       * Condition
       * Function
       * [Mount G Drive](https://github.com/siriwat-heart/DWDM21/blob/main/Data102_(Chapter2).ipynb)
         * .head() .tail() 
         * Boxplot
         * Time Series Plot
     * [Data Visualization](https://github.com/siriwat-heart/DWDM21/blob/main/Data_Visualization.ipynb)
       * Scatter plot
       * Plot
       * Bar chart
       * Histogram
     * [Distance Numpy](https://github.com/siriwat-heart/DWDM21/blob/main/Distance_Numpy.ipynb)
       * Numpy Array
         * สร้าง numpy array
         * สร้าง matrix เริ่มต้น (Zeros,ones)
         * สร้าง matrix randoom
         * matrix properties
       * Indexing & Slicing
       * Useful functions
       * วนลูปเอง
         * summation
       * Distance Matrix
         * Euclidean Distance (L2-norm)
       * Distance function
         * Euclidean Distance (L1-norm)
       * Distance of Binary Value
## บทที่ 3 
* [Data Preprocessing](https://github.com/siriwat-heart/DWDM21/blob/main/Data_Preprocessing(Chapter3).ipynb)
      * Meta Data (Data ที่ใช้อธิบาย Data)
      * ชี้ข้อมูลในตาราง 
         * ชี้แบบธรรมดา (ใช้[ชื่อcolumn][index])
         * ชี้แบบ .iloc (มองข้อมูลเป็น matrix)
      * Missing Values
         * Handling Missing Value 1 (ลบค่า missing)
         * Handling Missing Value 1.5 (ลบค่า missing เฉพาะใน column ที่เราสนใจ)
         * Handling Missing Value 2 (แทนด้วย class ใหม่ (unknown))
         * Handling Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
         * Handling Missing Value 4 (เเทนด้วย ค่ากลาง)
         * Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียว)
      * Select data by value [PD]
         * สร้าง list ของ boolean
         * นำ list ของ boolean มาเลือกค่าในตาราง
         * ต่อตารางแนวแกน Y [PD]
         * Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน) (ต่อ)
      * Pandas' looping (.iterrows)
      * การรวมตาราง Data Integration (ต่อตารางในแนวแกน x)
         * Grop by (pandas) 
         * [PD] save ตารางเอาไปใช้ที่อื่น
         * [PD]การสร้างตาราง
