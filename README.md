# Merge-sort
## Proje 2
 **[16,21,11,8,12,22] -> Merge Sort**

**Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.** <br>
**Big-O gösterimini yazınız.**  <br> <hr>
**Answer:**  <br>
1 -->  [16,21,11,8,12,22]

2 --> [16,21,11] [8,12,22]

3 --> [16,21] [11] [8,12] [22]

4 --> [16] [21] [11] [8] [12] [22]

5 --> [16,21] [8,11] [12,22]

6 --> [8,11,16,21] [12,22]

7 --> [8,11,12,16,21,22] (sonuç)
<hr>
<br>
2^x=n -> logn=x <br>
Big O Notation : O(nlogn)


