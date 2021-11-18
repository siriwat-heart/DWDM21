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
## บทที่ 4
   * [Data Warehousing and On-line Anaalytical Processing](https://github.com/siriwat-heart/DWDM21/blob/main/Chapter_4.pdf)
     * Data Warehouse : Basic concepts
     * Data Warehouse Mining : Data Cube and OLAP
       * OLTP vs. OLAP
       * Data Cubes
     * Data Warehouse Disng and Usage
     * Data Warehouse Implementation
## บทที่ 5
#### Lecture
   * [สรุปเนื้อหา chapter 6](https://github.com/siriwat-heart/DWDM21/blob/main/Chapter_6.pdf)
#### Googlecolab  
   * [Association Rules](https://github.com/siriwat-heart/DWDM21/blob/main/Chapter_6_Association_Rules.ipynb)
     * Besic Concepts
       * K-itemsets
       * ลบ records ที่ถูก cancel ออกไป
       * Plot graph of Itemsets
       * Frequence Itemsets to Association Rule
     * Efficient Pattern Mining Methods
       * Apriori
       * Support
## บทที่ 6
   * ประกอบด้วย 3 ส่วนย่อย ดังนี้
     * [Desition Tree](https://github.com/siriwat-heart/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
       * Load Data
       * Train Model
         * import(เรียกใช้ algorithm ที่เราต้องการ)
         * define (กำหนด paramiters ให้กับ model)
         * train (ฝึกสอนตัวแบบ)
       * plot tree
       * Evaluation
         * Random
       * Advanced Tree
         * import
         * Define
         * Train
       * TEST
       * Start here
         * mport
         * Define
         * Train
         * Evaluate
       * HW
     * [KNN](https://github.com/siriwat-heart/DWDM21/blob/main/Chap7_Classification_(KNN_NN).ipynb)
       * Load data
       * Split Data
       * Train Model
         * import
         * knn1
         * knn2
         * knn3 
       * Retrain & Evaluate
       * Neural Network
         * import
         * Define
         * Train - Test
         * ANN 2
         * ANN 3
     * [Evaluation](https://github.com/siriwat-heart/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
       * Load data
       * เเบ่ง Data
       * สร้าง Model ทำนาย
         * import
         * Define
         * Train
       * Evaluation
## บทที่ 7
#### Lecture
   * [สรุป Classifier](https://github.com/siriwat-heart/DWDM21/blob/main/Chapter_8_Classifier.ipynb)
   * [Homeworks InfoD](https://github.com/siriwat-heart/DWDM21/blob/main/Homeworks_InfoD.ipynb) 
#### Googlecolab  
   * [Clustering](https://github.com/siriwat-heart/DWDM21/blob/main/Chapter_10.pdf)
     * K-means
       * Generate Data
       * Explore Data
       * Clustering
         * import
         * Define
         * Fit-Predict
       * Exanple Application (Color Quantization)
         * นับจำนวนสี
         * จัดกลุ่มให้เหลือ 16 สี
         * แปลงข้อมูลให้อยู่ในรูป row-column
         * ใช้ centroid เป็นตัวแทนของสี
         * แทนสีคืนลงไป
     * Hierachical Clustering
     * Clustering Evaluation
   * [Cluster Analysis:Basic Concepts and Methods](https://github.com/siriwat-heart/DWDM21/blob/main/Chapter_10.pdf)
     * K-Means คืออะไร?
     * Clustering แบบลำดับชั้น
     * Cluster ที่ดี มี 4 ข้อ อะไรบ้าง?
## MiniExam
   * [Mid Term](https://github.com/siriwat-heart/DWDM21/blob/main/MiniExam.ipynb)
## Project
   * [Project Final](https://github.com/siriwat-heart/DWDM21/blob/main/Project_%E0%B8%A5%E0%B9%88%E0%B8%B2%E0%B8%AA%E0%B8%B8%E0%B8%94.ipynb)
     * ที่มาของข้อมูล
     * ตรวจสอบค่า missing และลบค่า missing
     * รวมตารางหาจังหวัดต้นทางต้นทาง
     * รวมตารางหาจังหวัดปลายทาง
     * รวมตารางต้นทางและปลายทาง
     * Challenge
     * 1.ทำนายประเภทรถไฟที่จะเลือกใช้บริการ โดยใช้ระยะทางระหว่างสถานี จำนวนนักท่องเที่ยวในจังหวัดต้นทาง จำนวนนักท่องเที่ยวในจังหวัดปลายทาง
       * Classification
       * Decision Tree
       * KNN
       * Neural Network
       * Retain & Evaluate
       * Evaluation
       * Data Visualization
     * 2.แบ่งกลุ่มข้อมูลรถไฟขาเข้าที่มี ลองจิจูด(column : X) และ ละติจูด (column : Y) ที่ใกล้กันจำนวน 6 กลุ่ม
       * สถานีต้นทาง
       * สถานีปลายทาง
       * เช็คความถูกต้อง
     * 3.หาจังหวัดที่มีรถไฟขาเข้ามากที่สุด
       * Plot กราฟ
       * สรุป
 * [PowerPoint](https://github.com/siriwat-heart/DWDM21/blob/main/NUMBERONE.pdf)

