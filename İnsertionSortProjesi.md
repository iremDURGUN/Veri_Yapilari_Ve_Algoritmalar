# **1. INSERTION SORT PROJESİ**

## **Soru 1**

*[22,27,16,2,18,6] => Insertion Sort*

*A.* *Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.*

*B.* *Big-O gösterimini yazınız.*

*C.* *Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.*

*D.* *Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.*

---
##  **A.** ***Verilen dizinin insertion sort türüne göre aşamaları***

* Dizinin insertion sort türüne göre adımları:
```
1. [22,27,16,2,18,6]
2. [16,22,27,2,18,6]
3. [2,16,22,27,18,6]
4. [2,16,18,22,27,6]
5. [2,6,16,18,22,27]
```
### **Aşamalar Şu Şekildedir;**

### **1. Aşama**
* Dizinin ilk elemanı ile sağındaki ikinci eleman kıyaslanır .
*  22<27 olduğu için sıralama bu aşamada aynı kalır.
```
1. [22,27,16,2,18,6]
```
### **2. Aşama**
* İkinci eleman ile üçüncü eleman kıyaslanır. 
* 27<16 olduğu için 16 ile 27 yer değiştirir.
    ```
    [22,16,27,2,18,6]
    ```
* Daha sonra da 16 ile ilk eleman kıyaslanır.
* 16<22 olduğu için bu iki eleman da yer değiştirir. 
* Sıralama da şu şekilde olur;
```
2. [16,22,27,2,18,6]
```
### **3. Aşama**
* Üçüncü eleman ile dördüncü eleman kıyaslanır. 
* 27>2 olduğu için elemanlar yer değiştirir.
    ```
    [16,22,2,27,18,6]
    ```
* Sonradan 2, ikinci eleman olan 22 ile kıyaslanır. 
* 2<22 olduğu için yer değiştirirler.
    ```
    [16,2,22,27,18,6]
    ```
* Tekrardan 2, ilk eleman olan 16 ile kıyaslanır.
*  2<16 olduğu için sıralama şu şekilde olur;
```
3. [2,16,22,27,18,6]
```
### **4. Aşama**
- Dördüncü eleman ile beşinci eleman kıyaslanır.
-  27>18 olduğu için elemanlar yer değiştirir.
    ```
    [2,16,22,18,27,6]
    ```
* Sonrasında 18, üçüncü eleman ile kıyaslanır. 
* 18<22 olduğu için elemanlar yer değiştirir.
    ```
    [2,16,18,22,27,6]
    ```
* Tekrardan 18, ikinci eleman ile kıyaslanır. 
* Zaten 16<18 olduğu için yer değiştirmezler ve sıralama şu şekilde olur;
```
4. [2,16,18,22,27,6]
```

### **5. Aşama**
* Beşinci eleman ile altıncı eleman kıyaslanır. 
* 27>6 olduğu için elemanlar yer değiştirir.
    ```
    [2,16,18,22,6,27]
    ```
* Sonrasında 6, dördüncü eleman ile kıyaslanır. 
* 6<22 olduğu için elemanlar yer değiştirir.
    ```
    [2,16,18,6,22,27]
    ```
*  6, üçüncü eleman ile kıyaslanır. 
* 6<18 olduğu için elemanlar yer değiştirir.
    ```
    [2,16,6,18,22,27]
    ```
* 6, ikinci eleman ile kıyaslanır.
*  6<16 olduğu için elemanlar yer değiştirir.
    ```
    [2,6,16,18,22,27]
    ```
  *Son olarak 6, birinci eleman ile kıyaslanır.
  *6>2 olduğu için elemanlar yer değiştirmez. 6 dizideki son eleman olduğundan dolayı sıralama tamamlanmış olur.
    Sıralama aşağıdaki gibi olur;
   ```
  5. [2,6,16,18,22,27]
```

## **B.** ***Big-O Gösterimi***

**Worst Case:** O(n^2)  şeklinde olur.

**Average Case:** O(n^2)  şeklinde olur.

**Best Case:** O(n)  şeklinde olur.


## **C.** ***Time Complexity***
**Worst Case:** 
```
[27,22,18,16,6,2]
```
**Average Case:**
```
[6,16,22,2,18,27]
```
**Best Case:**
```
[2,6,16,18,22,27]
```

## **D.** ***Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.***
18 elemanı sıralamanın ortasında bulunduğu için **Average Case** durumuna girer.


---

## Soru 2
## **[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**
```
1. [3,7,5,8,2,9,4,15,6]
2. [3,5,7,8,2,9,4,15,6]
3. [3,5,7,8,2,9,4,15,6]
4. [2,3,5,7,8,9,4,15,6]
```
---
---
-> Merge Sort Projesi'ne ilerlemek için [ tıklayınız.](https://github.com/iremDURGUN/Veri_Yapilari_Ve_Algoritmalar/blob/main/MergeSortProjesi.md)

<- README.md doyasına dönmek için [tıklayınız.](https://github.com/iremDURGUN/Veri_Yapilari_Ve_Algoritmalar/blob/main/README.md)

---
---
### **[Patika.dev](https://app.patika.dev/) ekibine teşekkürler.**
---
--- 

