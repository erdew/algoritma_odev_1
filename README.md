# algoritma_odev_1

Insertion Sort Projesi

[22,27,16,2,18,6]

## 1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

```
> [22 | 27, 16, 2, 18, 6]
> [22, 27 | 16, 2, 18, 6]
> [22, 27, 16 | 2, 18, 6]
> [22, 16, 27, 2 | 18, 6]
> [16, 22, 2, 27, 18 | 6]
> [16, 2, 22, 18, 27, 6 | ]
> [2, 16, 18, 22, 6, 27]
> [2, 16, 18, 6, 22, 27]
> [2, 16, 6, 18, 22, 27]
> [2, 6, 16, 18, 22, 27]
> [2, 6, 16, 18, 22, 27]

```

## 2.Big-O gösterimini yazınız.

Big-O gösterimi yani performansı O(n2)'dir.
Bunun sebebi dizideki eleman kadar geçiş gerekmesidir.
Her geçişte ise en kötü ihtimalle tüm elemanlar kadar kaydırma gerekmesidir.
Yani insertion sort algoritması için en kötü durum dizinin tersten sıralı olmasıdır.

## 3.Time Complexity:

### Average case: Aradığımız sayının ortada olması. O(n)

### Worst case: Aradığımız sayının sonda olması. O(n2)

### Best case: Aradığımız sayının dizinin en başında olması. O(2n)

## 4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

### Avarage Case.
