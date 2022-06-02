# veri_yapilari_ve_algoritmalar
Patika.dev modül sonu sorting projeleri!
[Patika.dev](https://app.patika.dev/)

## Insertion sort projesi
Verilen örüntüye ait en küçük elemanı buluyor ve en baştaki sayı ile yer değiştiriyor. İkinci en küçük elemanı buluyor ve 2. sıra ile değiştiriyor. Eğer 2.sıradaki eleman en küçük eleman ise dokunmadan 3. sıraya geçiyor ve dizi böyle sıra ile devam ederek bitirilir.
Ödev cevabı:
[7,3,5,8,2,9,4,15,6] dizisinin insert sort a göre ilk dört adımı;
1.adım [2,3,5,8,7,9,4,15,6] n-1
2.adım [2,3,4,8,7,9,5,15,6] n-2
3.adım [2,3,4,5,7,9,8,15,6] n-3
4.adım [2,3,4,5,6,9,8,15,7] n-4 
....

Ödev cevabı:
[22,27,16,2,18,6] n
Yukarıdaki dizinin insertion sort a göre aşamaları
1.adım [2,27,16,22,18,6] n-1
2.adım [2,6,16,22,18,27] n-2
3.adım [2,6,16,18,22,27] 1

Big-O gösterimi n*n dir

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
dizinin sırslı hali [2,6,16,18,22,27] olduğuna göre Average Case kapsamına girer.

## Merge Sort Projesi
 Merge Sort  bir listeyi her adımda parçaya ayırıp tek eleman kalıncaya kadar bölüyor. Böldükten sonra sıralı bir şekilde bize sunuyor .

 [16,21,11,8,12,22]
 Dizinin aşamaları;
      [16,21,11]                               [8,12,22]
 [16]       [21,11]                        [8]    [12,22]
 [16]     [21]  [11]                       [8]   [12]   [22](?)
 [16]     [11,21]                          [8]   [12,22]
 [11,16,21]                                [8,12,22]
             [8,11,12,16,21,22]

Big-O (nlogn)


## Binary Search Tree Projesi
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları:


                               7
                        5            8
               1             6             9
          0         3