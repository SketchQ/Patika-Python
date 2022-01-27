# Veri Yapıları

## Array

* Arrays(Diziler), anlam ifade edebilmesi için birden fazla nesneye ihtiyaç duyabilir. Mesela, sinema salonlarının koltuklarının kullanım durumlarının tutulduğu bir array.

* Array(Dizi), dezavantajlarından biri olan hafıza problemidir.

* Dynamic Arrays(Dinamik Diziler) ise yeni bir eleman eklenirken, dizinin boyutu artırılır.

* Dynamic Array dezavantajı ise hafızada gereksiz yer kaplamasıdır.

* Avantajları ise, dizilerin elemanlarının birbirine bağlı olması ulaşılabilirliği kolaylaştırır.

### Kaynak 1.1

1. [Array Nedir?](https://medium.com/@denizf.b/array-nedir-d9b7afd44ca2)

2. [Java Array Nedir?](https://yazdoldur.com/programlama/java/java-arrays/)

3. [Dinamikl dizi](https://tr.wikipedia.org/wiki/Dinamik_dizi)

4. [What is Array - BBC](https://www.bbc.co.uk/bitesize/guides/zy9thyc/revision/1)

5. [Definition of Array](https://techterms.com/definition/array)

6. [How do Dynamic Arrays Work?](https://www.geeksforgeeks.org/how-do-dynamic-arrays-work/)

### Test 1.1

**Soru 1/2**  
**Hangisi dizilerin avantajlarından biridir?**  
Ulaşılabilirliği artırır.  
**Soru 2/2**  
**Aşağıdakilerden hangisi Arrays(Diziler) için doğrudur?**  
Diziler anlam ifade etmesi için birden fazla nesneye ihtiyaç duyabilir.  

## Linked List

* Linked List(Bağlı Listeler), yanyana zorunluluğu olmadan veri tutmamızı sağlayan yapılardır.Yeni gelen eleman için hafıza'da yeni bir alan açmamıza gerek yoktur.  
Array'dan farklı olarak elemanlar kendisinden bir önceki elemana adresini bildirmek zorundadır.  
![Array](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/linked-list/figures/linked-list.png)

### Kaynak 1.2

1. [Linked List Nedir?](http://cagataykiziltan.net/veri-yapilari-data-structures/1-linked-list-bagli-listeler/)

2. [Linked List](https://www.tutorialspoint.com/data_structures_algorithms/linked_list_algorithms.htm)

3. [What is Linked List?](https://en.wikipedia.org/wiki/Linked_list#:~:text=In%20computer%20science%2C%20a%20linked,which%20together%20represent%20a%20sequence.)

### Test 1.2

**Soru 1/3**  
**Bağlı listelerde bir düğüm bir önceki düğümün verisini tutar.**  
Yanlış  
**Soru 2/3**  
**Bağlı listeler içerisindeki düğümler bir veri ve adres tutar.**  
Doğru  
**Soru 3/3**  
**Hangisi Doğrudur?**  
Her bir düğüm kendinden sonraki düğümün adresini tutar.  

## Linked List vs Array

![Linked List vs Array](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/linked-list-array/figures/linkedlist-vs-array.png)

![Linked List vs Array](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/linked-list-array/figures/array-vs-linkedlist-diff.png)

### Kaynak 1.3

1. [linkedlist array detay farkları](https://ceyhuncozvelioglu.medium.com/kendime-notlar-1-veri-yap%C4%B1lar%C4%B1na-giri%C5%9F-ve-linkedlist-mant%C4%B1%C4%9F%C4%B1-5944bcbb8165)

2. [Linkedlist vs Array farkları kod](https://www.ysancar.com/veri-yapilari/dizi-ile-bagli-liste-arasindaki-farklar/)

3. [Linked List vs Array](https://www.geeksforgeeks.org/linked-list-vs-array/)

4. [More Details](https://www.studytonight.com/data-structures/linked-list-vs-array)

### Test 1.3

**Soru 1/2**  
Doğru  
**Soru 2/2**  
Bellekte yer kaplarlar  

## Linked List Eleman Ekleme/Silme

![İlk Adım](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/linked-list-add-delete/figures/ilk-ad%C4%B1m.png)

### Eleman Ekleme

![Eleman Ekleme](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/linked-list-add-delete/figures/eleman-ekleme.png)

### Eleman Çıkarma

![Eleman çıkarma](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/linked-list-add-delete/figures/eleman-%C3%A7%C4%B1karma.png)

#### Kaynak 1.4

1. [Linked list operasyonlar kod dökümü](https://medium.com/@tolgahan.cepel/do%C4%9Frusal-veri-yap%C4%B1lar%C4%B1-2-ba%C4%9Fl%C4%B1-liste-linked-list-8e5d3d84c41f)

2. [Linked list operations](https://www.programiz.com/dsa/linked-list-operations)

#### Test 1.4

**Soru 1/2**  
Yanlış  
**Soru 2/2**  
Doğru  

## Stack

* Stack(Stack), veri yapısının en son eklenen elemanının çıkarmasını sağlayan yapıdır. LIFO(Last In First Out) yapısına sahiptir.
* Push(Ekleme), öncelikle yeni bir eleman eklenir.
* Pop(Çıkarma), öncelikle çıkartılacak elemanın adresini alır.

![Stack](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/stack/figures/stack.png)

### Kaynak 1.5

1. [Stack Kod örneği](http://www.baskent.edu.tr/~tkaracay/etudio/ders/prg/dataStructures/Collections/ClassStack.pdf)

2. [Stack detaylı Anlatım](https://cdn-acikogretim.istanbul.edu.tr/auzefcontent/20_21_Guz/veri_yapilari/6/index.html)

3. [Stack Short Definition](https://runestone.academy/ns/books/published//pythonds/BasicDS/WhatisaStack.html)

4. [Stack Definition with Code](https://www.studytonight.com/data-structures/stack-data-structure)

### Test 1.5

**Soru 1/3**  
İlk Giren ilk Çıkar  
**Soru 2/3**  
Doğru  
**Soru 3/3**  
Hayır  

## Queue

* Queue(Queue), veri yapısının ilk eklenen elemanının çıkarmasını sağlayan yapıdır. FIFO(First In First Out) yapısına sahiptir.
* Enqueue(Ekleme), öncelikle yeni bir eleman eklenir.
* Dequeue(Çıkarma), öncelikle çıkartılacak elemanın adresini alır.

![Queue](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/queue/figures/queue.png)

### Kaynak 1.6

1. [Queue Kod örneği](https://medium.com/@tolgahan.cepel/do%C4%9Frusal-veri-yap%C4%B1lar%C4%B1-4-kuyruk-queue-dcbd07e8ba77)

2. [Queue detaylı Anlatım](https://cdn-acikogretim.istanbul.edu.tr/auzefcontent/20_21_Guz/veri_yapilari/7/index.html)

3. [Queue Short Definition](https://www.educative.io/edpresso/what-is-a-queue)

4. [Queue Detail Definition](https://www.studytonight.com/data-structures/queue-data-structure)

### Test 1.6

**Soru 1/3**  
Enqueue ile eleman eklemesi yapılır.  
**Soru 2/3**  
Doğru  
**Soru 3/3**  
Yemekhaneye önce giden öğrencinin en erken ayrılması  

## Hash Table

![Indexleme](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/hash-table/figures/Indexleme.png)

### Hash Function / Hash Table

Hash Table, key value prensibine dayanan bir array kümesidir. Key olarak çağırdığınız elemanın değerini (value) yansıtır.  
Hash Table yerine dizileri kullanabilirdik. Fakat her ürünü ve fiyatını tek tek aramak istemediğimiz için hash table kullanıyoruz.  

![Örnek_1](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/hash-table/figures/%C3%B6rnek-ilk-k%C4%B1s%C4%B1m.png)

Bu kısımda ilk olarak bulunan ürün sayımız kadar değeri olan bir Array oluşturduk.Daha sonra hash fonksiyonundan ürünleri geçirerek index değerlerine ulaştık.  

![Örnek_2](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/hash-table/figures/%C3%B6rnek-ikinci-k%C4%B1s%C4%B1m.png)

Şifrelendiği için artık her badem keyi gönderildiğinde 85TL, fıstık keyi gönderildiğinde ise 69 sonucu verecektir.Özetle, elimizde var olan verileri bir fonksiyondan geçirip indexliyoruz. Bu fonksiyona hash function, bu fonksiyon ile birleştiğimiz dizi yapısına ise Hash Table diyoruz.  

#### Kaynak 1.7

1. [Hash table nedir?](https://www.youtube.com/watch?v=_TCkO3DnVs4)

2. [Full Definition](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)

#### Test 1.7

**Soru 1/2**  
Hash Table bir şeyi aramak için kullanılmaz  
**Soru 2/2**  
Yanlış  

## Hash Function

Hash Function (Karma Fonksiyonu), karma fonksiyonu olabilmesi için bazı temel şartlar vardır.Bunlar;

1. Gönderdiğimiz anahtarlar (keys) farklı olmasına rağmen bize aynı sonuçları veriyorsa bu bir hash function değildir.
2. Fonksiyona gönderilen anahtarlar aynı fakat sonuç farklı ise hash function değildir.
3. Hash Table için kullanılan dizinin boyutu verilen sonuçların sayısı kadar olmalı.

### Kaynak 1.8

1. [Hash Fonksiyonu](https://tr.wikipedia.org/wiki/Karma_i%C5%9Flevi)

2. [Hash Function](https://www.techopedia.com/definition/19744/hash-function)

### Test 1.8

**Soru 1/1**  
Fonksiyona yedirdiğimiz keyler farklı değerle dönüyorsa bu bir Hash function değildir.  

## Hash Collision

Hash Function farklı iki değerden aynı sayı üretilirse bu duruma Collison (çarpışma) denir. Bu olay istediğimiz bir durum değildir.

* Hash Function'lar bazen farklı durumlar için farklı sonuçlar üretemeyebilir. Örnek olarak araçları bir hash function dan geçirelim. Bu fonksiyonumuz son harflerine göre bir değer atıyor. Örneğin, motor ve tır için aynı değerleri ataması collision'a neden oluyor.
* Collision sorunuyla az karşılaşabilmek için kaliteli bir hash function olmalı. Bu sayede verimli bir Hash Table elde etmiş oluyoruz.
* Çarpışma sayısı arttıkça aradığımız şeyi bulma hızı azalır.

### Kaynak 1.9

1. [Wiki](https://en.wikipedia.org/wiki/Hash_collision)

2. [Detail-Collision](https://freemanlaw.com/hash-collisions-explained/)
