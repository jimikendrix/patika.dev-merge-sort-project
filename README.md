# patika.dev-merge-sort-project
 patika.dev merge-sort projesi

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
1. [16,21,11,8,12,22]
2. [16,21,11] [8,12,22]
3. [16,21] [11] [8,12] [22]
4. [11,16,21] [8,12,22]
5. [8,11,12,16,21,22]

2) Big-O gösterimini yazınız.
Avarage case: O(nlogn)
Best case: O(nlogn)
Worst case: O(nlogn)

Çözüm açıklaması: 3. adıma kadar bölerek ilerledim. 3. adımda ise en çok 2 eleman kaldığı için bölmeyi bitirdim. 4. adımda ise sıralayarak birleştirdim ve 5.adımda üçlü grubu sıralayarak birleştirdim.

www.patika.dev
