# **2. MERGE SORT PROJESİ**
*[16,21,11,8,12,22] -> Merge Sort*

*A.* *Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.*

*B.* *Big-O gösterimini yazınız.*

---
## A. **Merge Sort**
* Dizinin merge sort türüne göre adımları;
```
1.          [16,21,11]               [8,12,22]
2.      [16]         [21,11]   [8,12]         [22]
3.      [16]   [21]    [11]     [8]    [12]   [22]
4.        [16] [11,21]              [8,12] [22]
5.         [11,16,21]                [8,12,22]
6.                  [8,11,12,16,21,22]
```

### **Aşamalar şu şekildedir:**
### **1. Aşama**
* İlk olarak sağ ve sol index belirlenir.
* İkinci olarak dizinin orta noktası belirlenir ve sonra merge işlemine başlanır.
```
[16]= Sol Index / 0. Index
[22]= Sağ Index / 5. Index
Orta Nokta: [(5-0)+1]/2=3

Ayırırsak:
[16,21,11] [8,12,22]
```
### **2. Aşama**
* Sol ve sağa ayrılan index dizileri tekrar ikiye böleriz.
```
[16] [21,11] [8,12] [22]
```
### **3. Aşama**
* Indexler tekrardan, her bir index tek elemanlı bir dizi oluncaya dek ayrılır.
```
[16][21][11][8][12][22]
```
### **4. Aşama**
* Bu indexler tekrardan birleştirilmeye başlanır.
* Birleştirilirken kıyaslama yaparak yine gruplar halinde birleştirilir.
*   Soldaki üçlü grup şu şekilde birleştirilir;
    ```
    - [16] tek elemanlı olduğu için olduğu gibi devam eder.
    - 11<21 olduğu için [11,21] şeklinde sıralanırlar.
    ```
    * Sağdaki üçlü grup şu şekilde birleştirilir;
    ```
    - 8<12 olduğu için [8,12] şeklinde sıralanırlar.
    - [22] tek elemanlı olduğu için olduğu gibi devam eder.
    ```
* Bu aşamanın sonunda gruplar şu şekilde olur;
```
[16][11,21][8,12][22]
```
### **5. Aşama**
* Soldaki üçlü grupta önce 16 ile 11 kıyaslanır. 
* 16>11 olduğu için 11 en sola yazılır.
* 16 ile 21 kıyaslanır. 
* 16<21 olduğu için sıralama şu şekilde olur;
    ```
    [11,16,21]
    ```
* Sağdaki üçlü grupta önce 8 ile 22 kıyaslanır. 
* 8<22 olduğu için 8 olduğu yerinde kalır.
* 12 ile 22 kıyaslanır. 
* 12<22 olduğu için bu elemanlar da olduğu yerinde kalarak birleşir.
    ```
    [8,12,22]
    ```
* Bu aşamanın sonunda gruplar şu şekilde olur;
```
[11,16,21][8,12,22]
```
### **6. Aşama**
* Bu aşamada üçlü gruplar dizilerin en soldaki elemanlarından başlanarak kıyaslanır.
    * 11 ile 8 kıyaslanır. 11>8 olduğu için 8 en başa geçer.
    * 11 ile 12 kıyaslanır. 11<12 olduğu için 8'den sonra 11 gelir.
    * 16 ile 12 kıyaslanır. 16>12 olduğu için 11'den sonra 12 gelir.
    * 16 ile 22 kıyaslanır. 16<22 olduğu için 12'den sonra 16 gelir.
    * 21 ile 22 kıyaslanır. 21<22 olduğu için 22 son elemandır, 16'dan sonra da 21 gelir.
* Bu aşamanın sonunda işlem tamamlanmıştır ve şu dizi elde edilir.
```
[8,11,12,16,21,22]
```

---

## B. **Big-O Gösterimi**
Big-o gösterimi  O(n.logn) şeklinde olur.

---
---
*-> Proje 3 - Binary Search Tree Projesi'ne ilerlemek için[ tıklayınız.](https://github.com/iremDURGUN/Veri_Yapilari_Ve_Algoritmalar/blob/main/BinarySearchTreeProjesi.md)*

*<- Proje 1 - Insertion Sort Projesi'ne dönmek için [tıklayınız.](https://github.com/iremDURGUN/Veri_Yapilari_Ve_Algoritmalar/blob/main/%C4%B0nsertionSortProjesi.md)*

---
---
### **[Patika.dev](https://app.patika.dev/) ekibine teşekkürler.**
---
---

