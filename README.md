# Patika.dev-Insertion-Sort-Projesi
Insertion Sort Projesi
[22,27,16,2,18,6] -> Insertion Sort
```
Soru 1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Cevap 1) Aşamalar aşağıda belirtilmiştir.

1) [2,27,16,22,18,6]
2) [2,6,16,22,18,27]
3) [2,6,16,18,22,27]
```
```
Soru 2)Big-O gösterimini yazınız.,

Cevap 2)Big O -> O(n^2)
```
```
Soru 3)Time Complexity:
       Average case: Aradığımız sayının ortada olması,
       Worst case: Aradığımız sayının sonda olması,
       Best case: Aradığımız sayının dizinin en başında olması.

Cevap 3)- Average ve Worst Case için ->  Big O -> O(n^2)
        - Best Case için  -> Big O -> O(n)
```
```       
Soru 4)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Cevap 4)Time complexity => Avarage Case. Çünkü 18 sayısı dizinin ortasına yakın denk
gelmektedir.
```
```
Soru: [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Cevap:[7,3,5,8,2,9,4,15,6] -> Insertion Sort Adımları aşağıdaki gibidir.

1) [2,3,5,8,7,9,4,15,6]
2) [2,3,4,8,7,9,5,15,6]
3) [2,3,4,5,7,9,8,15,6]
4) [2,3,4,5,6,9,8,15,7]
```

[Patika.dev profilime buraya tıklayarak erişebilirsiniz!](https://app.patika.dev/kadircelebi)
# Patika.dev-Merged-Sort-Projesi-2
```
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

- Cevap:
-[16,21,11] | [8,12,22]
-[16],[21,11] | [8,12],[22]
-[16],[21],[11] |[8],[12],[22]
-[16],[11,21]|[8,12],[22]
 -[11,16,21] | [8,12,22]
 -[8,11,12,16,21,22]
 Big O gösterimi O(nlogn) dir.
