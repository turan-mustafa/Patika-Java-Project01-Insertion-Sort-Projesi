# Patika-Java-Project01-Insertion-Sort-Projesi

```
Proje 1

[22,27,16,2,18,6] -> Insertion Sort

    Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
    Big-O gösterimini yazınız.
    Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
    Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```


# [22,27,16,2,18,6] -> Insertion Sort

## 1.  Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[22,27,16,2,18,6] - bakarım, bu dizinin ek küçük sayısı hangisi, bunu bulur ve listein en başına yazarım

[(2),22,27,16,18,6] - Artık en küçük sayıyı biliyorum, o yüzden onu listedeki diğer değerleden ayrı tutarım ve ikinci değerden başlayarak yeniden dizinin en küçük sayısını ararım ve onu taradığım listenin en başına yazarım, şimdi listem şu şekilde olur.

[2,6,22,27,16,18] - İlk iki değer için işlem yaptığımdan, bunları listenin kalanından ayrı tutarım ve kalan listedeki değerleri tekrar tarayarak en küçük değeri bularak taradığım listenin en başına yazarım. Şimdi listem şu şekilde olur.

[2,6,16,22,27,18] - İlk iki değer için işlem yaptığımdan, bunları listenin kalanından ayrı tutarım ve kalan listedeki değerleri tekrar tarayarak en küçük değeri bularak taradığım listenin en başına yazarım. Şimdi listem şu şekilde olur.

[2,6,16,18,22,27] - İlk üç değer için işlem yaptığımdan, bunları listenin kalanından ayrı tutarım ve kalan listedeki değerleri tekrar tarayarak en küçük değeri bularak taradığım listenin en başına yazarım. Şimdi listem şu şekilde olur.

[2,6,16,18,22,27] - İlk dört değer için işlem yaptığımdan, bunları listenin kalanından ayrı tutarım ve kalan listedeki değerleri tekrar tarayarak en küçük değeri bularak taradığım listenin en başına yazarım. Şimdi listem şu şekilde olur.

[2,6,16,18,22,27] - İlk beş değer için işlem yaptığımdan, bunları listenin kalanından ayrı tutarım ve kalan listedeki değerleri tekrar tarayarak en küçük değeri bularak taradığım listenin en başına yazarım. Şimdi liste son halini alır.

[2,6,16,18,22,27]


## 2.  Big-O gösterimini yazınız.

n + (n-1) + (n-1)+... +1

n x (n+1)       n^2 + n
----------  =  ---------
    2               2

yukarıdaki işlemde dominant faktör en büyük olan n^2 olduğu için onu alırız. Böylece Big-O Notation gösterimi aşağıdaki gibi olur.

O(n^2)


## 3. Time Complexity: 
    Average case: Aradığımız sayının ortada olması,
    Worst case: Aradığımız sayının sonda olması, 
    Best case: Aradığımız sayının dizinin en başında olması.

## 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[22,27,16,2,18,6]
[2,6,16,18,22,27]
Average case: Aradığımız sayının ortada olması kapsamında girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6]
[2,7,3,5,8,9,4,15,6] - > Adım 1
[2,3,7,5,8,9,4,15,6] - > Adım 2
[2,3,4,7,5,8,9,15,6] - > Adım 3
[2,3,4,5,7,8,9,15,6] - > Adım 4

