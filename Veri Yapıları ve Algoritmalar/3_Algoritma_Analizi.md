# Algoritma Analizi

## Algoritma Analize Giriş

* Algoritma analizi, var olan kaynaklara göre en uygun algoritmayı seçmek için uygulanır. Peki algoritma analizi en iyi nasıl yapılır? Kulağa karmaşık geliyor ama çok basit. Programlama dillerinden ve donanımlardan bağımsız bir şekilde Algoritma analizi yapılmalıdır. Aksi taktirde en uygun sonuç alınamayabilir.
* Donanımlar veya programlama dilleri farklı cihazlarda aynı performansı vermeyebilir. Örnek verecek olursak, cep telefonları için uygulama tasarladığımızı varsayalım. Bu uygulamanın performansı Apple telefonlar için farklı, Android telefonlar için farklı, arasında donanım farklı olanlar için ayrı olacaktır. Donanım ve diller ile algoritma analizi pek sağlıklı değildir.
* Algoritma analizi, bir algoritmanın çalışabilmesi için gerekli koşulların sağlanıp sağlanamadığını gösteren bir parametredir.

### Kaynak 1.1

1. [Derinlemesine algoritma analizi](https://birhankarahasan.com/algoritma-analizi-nedir-zaman-karmasikligi-big-o-gosterimi)

2. [Wiki](https://tr.wikipedia.org/wiki/Algoritma_analizi)

### Test 1.1

**Soru 1/1**  
Var olan kaynaklara göre en hızlı algoritmayı seçmek için uygulanır.  

## RAM Modeli

Bir algoritmayı farklı cihazlarda denemek bize pek fazla bir sonuç çıkarmıyordu. Çünkü kaynaklar değişebiliyordu. Bu probleme genel bir çözüm getirebilmek için hayalî bir cihaz düşünelim. Bu cihaz üzerinde bütün algoritmaları çalıştırdıktan sonra bize bir sonuç veriyor.

Bu hayalî cihaza RAM (Random Access Machine) diyoruz. Ram, algoritmalar arasındaki farkları belirlemek için kullanacağımız bir araç olacak.

Her işlemin birim zamanı var. Döngüler, kaç defa işlem yapıyorsa, (işlem sayısı * kaç kere tekrar edeceği) kadar birim zaman alır. Toplama, Çıkarma, and, or gibi aritmetik işlemler, 1 birim zaman alır.

### Kaynak 1.2

1. [Ram-Random Access Machine](https://www.youtube.com/watch?v=by1HmASLHkM)

2. [Ram Model](https://www.youtube.com/watch?v=wkBjD0Fvl6U)

### Test 1.2

**Soru 1/1**  
Algoritmalar arasındaki farkı belirlemek için kullanılır.  

## Time Complexity

* Örnek: Raflara kitap yerleştirmek.
* Kitapları, gelişigüzel raflara dağıtırsak aradığımız kitabı daha fazla zamanda bulabiliriz. Aslında bu bir ***worst case***'dir. Kitapları filtrelememiz gerekir. Kalın olanları bir rafa, ince olanları bir rafa, küçük boyutta olanları bir rafa koyduğumuz zaman aradığımız şeyi daha rahat bulabiliriz. Algoritma, en kötü senaryoya ne kadar hazırsa, bizi o kadar memnun edebilir.
* Algoritmalar için genellikle sık kullanılan ***average case***'dir. Kitapların bölümüne göre kaç tane olduğunu biliyorsak average case kullanabiliriz. En büyük rafı miktarı fazla olana ayırabiliriz. Input yoksa average zordur!!!!
* Bir diğer senaryomuz ise ***best case***'dir. Beklediğimiz en iyi durum. Kitap örneğine devam edecek olursak, bütün kitapların ayrı raflarda olması, alfabeye göre sıralanması best case olarak ifade edilebilir. Çünkü aradığımızı rahatlıkla bulabiliyoruz.

### Kaynak 1.3

1. [Why and What Time Complexity](https://www.mygreatlearning.com/blog/why-is-time-complexity-essential/)

### Test 1.3

**Soru 1/1**  
Minumum Case  

## Big O Notation

![Grafik](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/big-o/figures/big-o-grafik.png)

* İki farklı arama yöntemimiz var. Bunlardan A algoritması sayfa sayfa, B algoritması yarıya bölüp tarıyor.

![Big O](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/big-o/figures/big-o.png)

### Kaynak 1.4

1. [Big-O-Nedir?](https://medium.com/kodcular/nedir-bu-big-o-notation-b8b9f1416d30)

2. [big-O](https://www.ridvantulemen.com/buyuk-o-notasyonu-nedir-big-o-notation/)

### Test 1.4

**Soru 1/1**  
O(n+n^2)  
