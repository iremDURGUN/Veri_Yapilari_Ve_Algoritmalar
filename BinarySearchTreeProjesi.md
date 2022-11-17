# **3. BINARY SEARCH TREE PROJESİ**
*[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.*

*Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.*

---
* Root 7 olarak belirleyelim.
* Dizideki elemanları 7 ile başlayarak kıyaslarız.
* 7 elemanından büyük olanlar sağ tarafa, küçük olanlar sol tarafa yazılacak şekilde bir tree oluşturulur.

    

## **Aşamalar şu şekildedir;**

* Root elemanı 7 olarak belirlenmiştir.
    ```
                                        7
    ```

* 5 ile 7 kıyaslanır. 5<7 olduğu için 5, 7'nin soluna yazılır.
    ```
                                        7
                                      /
                                    5
    ```
* 1 ile 7 kıyaslanır. 1<7 olduğu için 1,7'nin sol tarafına ilerler.
* Sonrada 1 ile 5 kıyaslanır. 1<5 olduğu için 1, 5'in soluna yazılır.
    ```
                                        7
                                      /
                                    5
                                  /
                                1
    ```
* 8 ile 7 kıyaslanır. 8>7 olduğu için 8,7'nin sağına yazılır.
    ```
                                       7
                                     /   \
                                    5     8
                                   /
                                  1
    ```
* 3 ile 7 kıyaslanır. 3<7 olduğu için 3,7'nin sol tarafına ilerler.
* 3 ile 5 kıyaslanır. 3<5 olduğu için 3,5'in sol tarafına ilerler.
* 3 ile 1 kıyaslanır. 3>1 olduğu için 3,1'in sağına yazılır.
    ```
                                       7
                                     /   \
                                    5     8
                                   /
                                  1
                                   \
                                    3
    ```
* 6 ile 7 kıyaslanır. 6<7 olduğu için 6,7'nin sol tarafına ilerler.
* 6 ile 5 kıyaslanır. 6>5 olduğu için 6,5'in sağına yazılır.
    ```
                                       7
                                     /   \
                                    5     8
                                   / \
                                  1   6
                                   \
                                    3
    ```
* 0 ile 7 kıyaslanır. 0<7 olduğu için 0,7'nin sol tarafına ilerler.
* 0 ile 5 kıyaslanır. 0<5 olduğu için 0,5'in sol tarafına ilerler.
* 0 ile 1 kıyaslanır. 0<1 olduğu için 0,1'in soluna yazılır.
    ```
                                       7
                                     /   \
                                    5     8
                                   / \
                                  1   6
                                /  \
                               0    3
    ```
* 9 ile 7 kıyaslanır. 9>7 olduğu için 9,7'nin sağ tarafına ilerler.
* 9 ile 8 kıyaslanır. 9>8 olduğu için 9,8'in sağına yazılır.
    ```
                                       7
                                     /   \
                                    5     8
                                   / \     \
                                  1   6     9
                                 / \
                                0   3
    ```
* 4 ile 7 kıyaslanır. 4<7 olduğu için 4,7'nin sol tarafına ilerler.
* 4 ile 5 kıyaslanır. 4<5 olduğu için 4,5'in sol tarafına ilerler.
* 4 ile 1 kıyaslanır. 4>1 olduğu için 4,1'in sağ tarafına ilerler.
* 4 ile 3 kıyaslanır. 4>3 olduğu için 4,3'ün sağına yazılır.
    ```
                                       7
                                     /   \
                                    5     8
                                   / \     \
                                  1   6     9
                                 / \
                                0   3
                                     \
                                      4
    ```
* 2 ile 7 kıyaslanır. 2<7 olduğu için 2,7'nin sol tarafına ilerler.
* 2 ile 5 kıyaslanır. 2<5 olduğu için 2,5'in sol tarafına ilerler.
* 2 ile 1 kıyaslanır. 2>1 olduğu için 2,1'nin sağ tarafına ilerler.
* 2 ile 3 kıyaslanır. 2<3 olduğu için 2,3'ün soluna yazılır.
    ```
                                       7
                                     /   \
                                    5     8
                                   / \     \
                                  1   6     9
                                 / \
                                0   3
                                   / \
                                  2   4
    ```

---
---
*-> README.md doyasına dönmek için [tıklayınız.](https://github.com/iremDURGUN/Veri_Yapilari_Ve_Algoritmalar/blob/main/README.md)*

*<- Proje 2 - Merge Sort Projesi'ne dönmek için[ tıklayınız.](https://github.com/iremDURGUN/Veri_Yapilari_Ve_Algoritmalar/blob/main/MergeSortProjesi.md)*


---
---
### **[Patika.dev](https://app.patika.dev/) ekibine teşekkürler.**
---
---

