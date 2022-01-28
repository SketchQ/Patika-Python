# Sorting Algoritmaları

## Sorting Nedir?

Sorting, kendinden sıralama algoritmaları olarak bahsetmektedir. Sorting, bir eleman dizisini, belirli sıralama kurallarına göre sıralama yapar.

![Sorting](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/sorting/figures/sorting.png)

1. **Searching** yöntemini kullanarak elemanlarımızı sıraladık. Bunun sebebi, eleman ararken işimizin kolaylaşmasını istiyoruz.
2. **Closest Pair** yöntemini kullanarak birbirine yakın sayıları gruplandırdık ki arama yaparken zamanımızı efektif bir şekilde kullanalım.
3. **Aynı eleman kontrolü**: birbiriyle aynı olan sayıları örüntü içerisinde kaç tane aynı eleman varsa sayısını öğrenebilirim.
4. **Mode bulma**: eleman dizisini search ettikten sonra elemanların yan yana olanları sayarsam daha hızlı mode bulabilirim.

### Kaynak 1.1

1. [Sorting-Algoırithms-full](https://www.geeksforgeeks.org/sorting-algorithms/)

2. [Types of Sorting](https://www.interviewbit.com/tutorial/sorting-algorithms/)

3. [Sıralama Algoritmaları](https://www.halildurmus.com/2021/02/22/siralama-algoritmalari-sorting-algorithms/)

### Test 1.1

**Soru 1/2**  
Üçlü Arama Yöntemi  
**Soru 2/2**  
Eleman dizisinden bir pivot belirleyerek sıralama yapar.  

## Insertion Sort

![Insertion Sort](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/insertion-sort/figures/insertion-sort.png)

* Verilen örüntüye ait en küçük elemanı buluyor ve en baştaki sayı ile yer değiştiriyor. Peki ya devamı? İkinci en küçük elemanı buluyor ve 2. sıra ile değiştiriyor. Baktın ki 2.sıradaki eleman en küçük hiç dokunma!!!. Hemen 3. sıraya geç. 4, 5 derken dizi bitti. İşte insertion sort'un temel çalışma prensibini öğrendin.

![Insertion Sorting](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/insertion-sort/figures/insertion-sort.png)

### Kaynak 1.2

1. [Insertion Sort With Code](https://www.geeksforgeeks.org/insertion-sort/)

2. [Insertion Sort With Data Structure](https://www.tutorialspoint.com/data_structures_algorithms/insertion_sort_algorithm.htm)

3. [Insertion Sort Nedir?](https://www.mobilhanem.com/algoritma-dersleri-insertion-sort/)

4. [Insertion Sort Detay](http://cagataykiziltan.net/algoritmalar/1-siralama-algoritmalari/1-araya-sokma-siralamasi/)

### Test 1.2

**Soru 1/2**  
Diziyi parçalayarak sıralama yapar.  
**Soru 2/2**  
[5,12,15,28,21,35,22]  

## Merge Sort

Insertion Sort'da, Big-O gösteriminden dolayı input'um arttığında n2 olduğunda dolayı çalışma zamanı artıyor.

* Peki daha hızlı bir şekilde sıralama yapılabilir mi? Evet, Merge Sort burada yardımımıza koşuyor. Bir listeyi her adımda parçaya ayırıp tek eleman kalıncaya kadar bölüyor. Böldükten sonra sıralı bir şekilde bize sunuyor (Performans).

![Merge Sorting](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/merge-sort/figures/merge-sort.png)

![Big O Merge](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/merge-sort/figures/big-o-merge.png)

### Kaynak 1.3

1. [Merge Sort Detail with Code](https://www.programiz.com/dsa/merge-sort)

2. [Merge Sort Article](https://www.khanacademy.org/computing/computer-science/algorithms/merge-sort/a/overview-of-merge-sort)

3. [Merge Sort Nedir?Kod Dökümanı](http://cagataykiziltan.net/algoritmalar/1-siralama-algoritmalari/4-birlestirmeli-siralama/)

4. [Merge Sort Wiki](https://tr.wikipedia.org/wiki/Birle%C5%9Ftirmeli_s%C4%B1ralama)

### Test 1.3

**Soru 1/3**  
Bir Diziyi tek hücreye kadar parçalayarak sıralama yapar.  
**Soru 2/3**  
Doğru  
**Soru 3/3**  
[6,12]  

## Quick Sort

Hızlı sıralama günümüzde çok yaygın olarak kullanılan bir sıralama algoritmasıdır. N tane sayıyı average case e göre big-o nlogn, worst case e göre big-o n^2 karmaşıklığı ile sıralanır.

![Quick Sorting](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/quick-sort/figures/Quicksort.png)

* İlk olarak bir pivot belirler bu pivota göre pivottan küçük ve eşitler sol kısmına, pivottan büyük ve eşitler sağ kısmına yazılır. Parçalanmış kısımlar yeni bir pivot belirlenerek parça pinçik edilir.

### Kaynak 1.4

1. [Quick Sort Nedir?](https://tr.wikipedia.org/wiki/H%C4%B1zl%C4%B1_s%C4%B1ralama)

2. [Quick Sort](https://www.mobilhanem.com/algoritma-dersleri-quick-sort/)

### Test 1.4

**Soru 1/1**  
Worst Case'in time complexity'si n'dir.  
