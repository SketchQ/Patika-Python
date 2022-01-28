# Arama Algoritmaları

## Searching Nedir?

* Günümüzde veriler gitgide artan bir hal alıyor. Her insanın bir bilgisayarı ve telefonu olduğunu düşünürsek, terabaytlarca veri ediyor. Arama algoritmaları ise istediğim özellikteki verinin elimdeki veri setlerinde aranıp, bulunup getirilmesi demek. Bunun hızlı olmasına önem gösterilir.

### Kaynak 1.1

1. [Search Algortihm](https://en.wikipedia.org/wiki/Search_algorithm)

2. [Why we need searching algorithms](https://www.bbc.co.uk/bitesize/guides/zgr2mp3/revision/1)

### Test 1.1

**Soru 1/1**  
Doğru  

## Linear Search

Linear search, tek tek elemanları dolandıktan sonra istediğim elemanın olup olmadığına bakmaktır.

* Örneğin, [20,25,46,48] veri setini ele alalım. Benim aradığım eleman 25. İlk elemana gidiyorum ve değeri 20 sen değilsin diyorum. İkinci elemana gidiyorum ve değeri 25 evet sensin diyorum. Linear search algoritmam burada bitmiş oluyor.
* Big-o ya göre incelediğimizde bizim worst case'imiz neydi? Elemanın dizinin sonunda bulunmasıydı. Bu sebepten ötürü n elemanımız varsa big-o notasyonumuz otomatik olarak n oluyor.

### Kaynak 1.2

1. [BBC linear Search](https://www.bbc.co.uk/bitesize/guides/z7kkw6f/revision/7)

2. [Linear Search with Code](https://www.programiz.com/dsa/linear-search)

### Test 1.2

**Soru 1/2**  
İlk önce veri seti ikiye ayrılır.  
**Soru 2/2**  
O(n)  

## Binary Search

İkili arama algoritması, elimizde bulunan veri dizisini sıralı olduğunu varsayıyor, bu durumu değiştirerek sonuca varmak istiyor.

* İkili arama algoritması, diziyi her seferinde ikiye bölerek ikili arama yapar. Sıralı bir listem var ise benim Big-o logn olarak karşımıza çıkıyor.
* Aradığım sayı 15 ve benim değer kümem [10,15,20,16,22,36,23] diyelim. Binary Search bu diziyi manipüle ederek şu ifadeye dönüştürüyor. [10,15,16,20,22,23,36]. 36 sayısını en yüksek sayı, 10 sayısını en düşük sayı ilan ediyor. Benim aradığım sayı ile ortada kalan sayıyı kıyaslıyor eğer benim sayım büyükse kendinden küçük bütün sayıları siliyor. Ve kendine yeni bir ortanca belirliyor. Böylelikle gereksiz arama yapmaktan kurtarıyor.

![Binary Search](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/binary-search/figures/binary-search.png)

### Kaynak 1.3

1. [Binary Search](https://www.khanacademy.org/computing/computer-science/algorithms/binary-search/a/binary-search)

### Test 1.3

**Soru 1/2**  
En yüksek sayıyı sola, en küçük sayıyı sağa yazıyor.  
**Soru 2/2**  
[13,18,22,28]  

## Binary Search Tree

Bir düğüm her iki tarafa da referans verebiliyor. Sağ ve sol olarak. Sağ tarafından kendinden büyük elemanlar, sol tarafında ise kendinden küçük elemanlar bulunacak.

![Binary Search Tree](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/binary-search-tree/figures/binary-search-tree.png)

* Tree'ye eleman eklemek istediğimde **root**'dan başlıyorum. Örnek olarak ben 26 sayısını ağaç yapısına eklemek istiyorum. Root'a soruyorum senin değerin ne 56. Baştaki açıklamamızı hatırlayalım. Sağ tarafında kendinden büyük, sol tarafında kendinden küçük elemanlar var. O yüzden sırasıyla 56 ve 30 a kadar ilerliyorum. 30 bana benim sol tarafıma geçmelisin çünkü sen benden küçüksün diyor. Karşıma 22 değerinde olan düğüm çıkıyor ve 22 den büyük olduğum için sağ tarafına bir köşe çekiyorum ve 26 sayısını bağlıyorum.

### Kaynak 1.4

1. [Binary Search Tree](https://tsafaelmali.medium.com/binary-search-tree-nedir-2e6fb0621d9)

2. [Binary Search Tree](https://www.buraksenyurt.com/post/Binary-Search-Tree-yi-Anlamak)

3. [Binary Search Tree English Detail](https://www.geeksforgeeks.org/binary-search-tree-data-structure/)

### Test 1.4

**Soru 1/1**  
Ekleyeceğimiz eleman root'dan büyük ise düğümün sol referansından devam edilir.  
