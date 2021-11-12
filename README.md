# DWDM21
Data Warehouse &amp; Data Mining 2021

Thitichaya Kraiwong 623020520-0

Group Name : ลูกหมี

1 **ฐิติชญา  ไกรวงค์      623020520-0**

2 มินตรา      ทิพยรัตน์สุนทร 623020041-2

3 กัญญารัตน์   แสนสมบัติ    623020513-7

4 นันทิชา      วิชิต        623020526-8

5 ศศิกานต์     บุญมี        623020539-9

# สารบัญเนื้อหา

* บทที่ 1 Introduction 
  * Lecture
    * (https://github.com/Thitichaya2000/DWDM21/blob/main/HW%20Chapter%201.pdf)

* บทที่ 2 Getting to Know Your Data 
  * Lecture
    * (https://github.com/Thitichaya2000/DWDM21/blob/main/Chapter%202.pdf)
    * (https://github.com/Thitichaya2000/DWDM21/blob/main/Chapter2.pdf)
  * Github 
     * Basic python
       * (https://github.com/Thitichaya2000/DWDM21/blob/main/Data101(Chapter2).ipynb)
       * Variables
       * Data structure
       * Loop
       * Condition
       * Function
     * Data Exploration
       * (https://github.com/Thitichaya2000/DWDM21/blob/main/Data102(Chapter2).ipynb) 
       * Boxplot
       * Times Series Plot 
     * Data Visualization 
       * (https://github.com/Thitichaya2000/DWDM21/blob/main/Data_Visualization.ipynb)
       * Scatter plot
       * Plot
       * Bar chart
         * Grouped Barchart
         * Stacked Barchart
       * Histogram 
     * Distance Numpy
       * (https://github.com/Thitichaya2000/DWDM21/blob/main/Distance_Numpy.ipynb)
       * Numpy Array
         * สร้าง numpy array (matrix) จาก list
         * สร้าง matrix เริ่มต้น (zeros, ones)
         * สร้าง matrix random 
         * matrix properties
         * Indexing & Slicing
         * Useful functions
       * Distance Matrix
         * Euclidean Distance (L2-norm)
         * Distance function
         * Manhattan Distance (L1-norm)
         * Distance of Binary Value
* บทที่ 3 [Data Preprocessing]
  * lecture  
     * (https://github.com/Thitichaya2000/DWDM21/blob/main/Chapter%203.Data%20Preprocessing.pdf)
  * Github
     * (https://github.com/Thitichaya2000/DWDM21/blob/main/Data_Preprocessing(Chapter_3).ipynb)
     * ชี้ข้อมูลในตาราง
       * ชี้แบบธรรมดาใช้ [ชื่อ column] [index]
       * ชี้แบบ .iloc (มองข้อมูลเป็น matrix)
     * Missing Values NAN NULL NA
       * Handling Missing Value 1 (ลบ missing)
       * Handling Missing Value 1.5 (ลบค่า Missing เฉพาะใน Column ที่เราสนใจ)
       * Handing Missing Value 2 (แทนด้วย class ใหม่ (unknown))
       * Handing Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
       * Handing Missing Value 4 (แทนด้วย ค่ากลาง)
       * Handing Missing Value 5 (แทนด้วย ค่ากลางของ Samples ใน Class เดียวกัน)
     * Select date by values [PD]
       * ต่อตารางแนวแกน Y [PD]
       * การเรียงข้อมูล [PD]
       * Outlier
     * การรวมตาราง Data Integration (ต่อตารางในแนวแกน x)
       * รวม 2 ตาราง (.merge())
       * เลือกเฉพาะ column ที่ต้องการมาแปะ (.map())
       * Group by (pandas)
       * [PD] save ตารางเอาไปใช้ที่อื่น
       * [PD] การสร้างตาราง
* บทที่ 4 [Data Warehousing and On-line Analytical Processing]
  * lecture 
    * (https://github.com/Thitichaya2000/DWDM21/blob/main/04OLAP.pdf) 
      * Data Warehouse : Basic Concepts 
      * Data Warehouse Modeling : Data Cube and OLAP  โมเดลของData Warehouse
       ***************************************************************************** เพิ่มสไลด์
      * Data Warehouse Design and Usage การออกแบบและการใช้งานคลังข้อมูล
      * Data Warehouse Implementation การใช้งานคลังข้อมูล
      * Summary 
* บทที่ 5 Association Rules
  * lecture
    * (https://github.com/Thitichaya2000/DWDM21/blob/main/06FPBasic.pdf)  
  * Github 
    * (https://github.com/Thitichaya2000/DWDM21/blob/main/Chapter6_Association_Rules.ipynb)  
    * เตรียม Data สำหรับ (Fequence Pattern) Association Rule
    * Apriori
* บทที่ 6 [Classification]
  * Lecture
    * (https://github.com/Thitichaya2000/DWDM21/blob/main/08ClassBasic.pdf)
    * (https://github.com/Thitichaya2000/DWDM21/blob/main/Lecture141064.pdf) 
    * (https://github.com/Thitichaya2000/DWDM21/blob/main/Lecture191064.pdf)
    * *************************************************************************** เพิ่มสไลด์
  * Github
    * Decision Tree
      * (https://github.com/Thitichaya2000/DWDM21/blob/main/Chapter7_Classification(Decision_Tree).ipynb)
      * Load data
      * Train Model
      * Evaluation
      * Advanced Tree
      * Test
    * KNN
      * (https://github.com/Thitichaya2000/DWDM21/blob/main/Chap7_Classification_(KNN_NN).ipynb)
      * Load data
      * Split data
      * Train Model 
      * Retrain & Evaluate
      * Neural Network
    * Evaluation
      * (https://github.com/Thitichaya2000/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
      * Load data
      * Split data     
      * สร้าง Model ทำนาย
        * import
        * define
        * train
      * evaluation
* บทที่ 7 [Clustering]  
  * Lecture
  *  ****************************************************************************** เพิ่มสไลด์
  * Github
    * (https://github.com/Thitichaya2000/DWDM21/blob/main/Chap_8_Clustering.ipynb) 
    * K-means
      * Generate Data    
      * Explore data
      * Clustering
    * Example Application (Color Quantization)
      * นับจำนวนสี
      * จัดกลุ่มสีให้เหลือ 16 สี
      * ใช้ centroid เป็นตัวแทนของสี
    * Hierachical Clustering
    * Clustering Evaluation
* MiniExam
  * (https://github.com/Thitichaya2000/DWDM21/blob/main/MiniExam.ipynb) 
* Project
  * Powerpoint  
  *  (https://github.com/Thitichaya2000/DWDM21/blob/main/Final%20Project%20%E0%B8%81%E0%B8%A5%E0%B8%B8%E0%B9%88%E0%B8%A1%E0%B8%A5%E0%B8%B9%E0%B8%81%E0%B8%AB%E0%B8%A1%E0%B8%B5.pdf)  
  * Github
    * (https://github.com/Thitichaya2000/DWDM21/blob/main/Project_lookmhee.ipynb)

