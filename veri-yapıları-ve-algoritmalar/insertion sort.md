# Insertion Sort Projesi

## Proje 1

[22,27,16,2,18,6] -> Insertion Sort (*aslında selection sort sanırım, ama patika eğitimine göre yapacağım*)

### **1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**
1. [22,27,16,2,18,6]
2. [2,27,16,22,18,6] (22 sayısı ile 2 sayısı yer değiştirdi.)
3. [2,6,16,22,18,27] (27 sayısı ile 6 sayısı yer değiştirdi.)
4. [2,6,16,22,18,27] (16 sayısı yer değiştirmedi.)
5. [2,6,16,18,22,27] (22 sayısı 18 sayısı ile yer değiştirdi.)
6. [2,6,16,18,22,27] (22 sayısı ve 27 sayısı yer değiştirmedi.)
### **2. Big-O gösterimini yazınız.**
n+(n-1)+(n-2)...1= n*(n-1)/2= (n^2-n)/2 ~ n^2

So, **O(n^2)**

### **3. Time Complexity:**
* Average case: Aradığımız sayının ortada olması  **O(n^2)** 
* Worst case: Aradığımız sayının sonda olması  **O(n^2)**
* Best case: Aradığımız sayının dizinin en başında olması. **O(n)**
### **4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.**
18 sayısı sıralama işleminden sonra dizinin orta kısımlarına denk geldiğinden dolayı **Avarage Case** olarak değerlendirilebilir



------------------------


### **[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**

0. [7,3,5,8,2,9,4,15,6]

2. [**2**,3,5,8,7,9,4,15,6]

3. [2,**3**,5,8,7,9,4,15,6]

4. [2,3,**4**,8,7,9,5,15,6]

5. [2,3,4,**5**,6,9,8,15,7]
