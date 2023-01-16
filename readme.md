# Merge Sort Projesi
[patika.dev](https://patika.dev) Veri Yapıları ve Algoritmalar eğitimindeki ödev.
## [16,21,11,8,12,22] -> Merge Sort
1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
> ÇÖZÜM:
>
>[16,21,11,8,12,22] n (en küçük sayı olan 8 ile en baştaki sayıyı değiştiririz.)
>
>[8,21,11,16,12,22] (n-1) (2.en küçük sayı olan 11 ile 2.sıradaki sayıyı değiştiririz.)
>
>[8,11,21,16,12,22] (n-2) (3.en küçük sayı olan 12 ile 3.sıradaki sayıyı değiştiririz)
>
>[8,11,12,16,21,22] (1)
2. Big-O gösterimini yazınız.
>ÇÖZÜM:
>
>2^x=n
>
>x=log(n) 
>
>n*log(n)
>
>Average case: O(n*logn)