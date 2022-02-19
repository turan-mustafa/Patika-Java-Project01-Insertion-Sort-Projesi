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



2.  Big-O gösterimini yazınız.
3.  Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4.  Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
