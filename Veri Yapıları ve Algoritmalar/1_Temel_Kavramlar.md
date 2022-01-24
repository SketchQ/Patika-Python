# Temel Kavramlar

## Algoritma Nedir?

Algoritma nedir sorusunun cevabı, bir problemin çözümü için gerekli olan adımların bütününe verilen bir isimdir.

![Algoritma](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/algoritma-nedir/figures/Algoritma.png)

**Özetle, Algoritma belirli bir durumdan başlayıp belirli bir sonuçta biten problemlere çözüm getiren adımlardır.**

### Kaynaklar - 1.1

1. [Wikipedia](https://tr.wikipedia.org/wiki/Algoritma)
2. [Khan Academy](https://tr.khanacademy.org/computing/computer-science/algorithms/intro-to-algorithms/v/what-are-algorithms)
3. [Investopik](https://www.investopedia.com/terms/a/algorithm.asp)
4. [BBC](https://www.bbc.co.uk/bitesize/topics/z3tbwmn/articles/z3whpv4)

### Test - 1.1

**Soru - 1/3**  
**Aşağıdakilarden hangisi bir algoritma tanımı değildir?**

Bilgisayar bilimlerinde ya da matemetikte kullanılan, verilen bir listenin elemanlarını belirli bir sıraya sokan kurallardır.

**Soru - 2/3**  
**Algoritma terimini ilk olarak 9.yy'da kim ortaya çıkarmıştır?**

Harizmi

**Soru - 3/3**  
**Aşağıdaki örneklerden hangisi bir algoritmayı ifade etmez?**

Oturmak

## Bilgilerin Bilgisayarda İfadesi

Bilgisayar da bir bilgiyi ifade etmek için bit( 0 ve 1)'den oluşan ikili sayıları(Binary) kullanır.  
Transistörlerde iki tane komut vardır, 0(kapat) ve 1(açık).

![Bilgilerin Bilgisayarda İfadesi](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/bilgi-ifade/figures/Konu%C5%9Fma.jpg)

Örnek Java üzerinden olacak yazdığınız kod Java'nın hali hazırda sahip olduğu Java Compiler ile derlenerek .class uzantılı dosyayı oluşturur. Haa dikkat, bu format prensesimiz olan sadece JVM (JAVA VİRTUAL MACHİNE)'ye özeldir. İşlemcimiz bu aşamada okuyamadığından işleyemez. JVM (JAVA VİRTUAL MACHİNE) .class uzantılı bytecode'u satır satır işleyerek makine koduna dönüştürür ve çalıştırır.

**Özetle, Javada yazılan kod önce bytecode'a çevrilir, daha sonrasında üzerinde çalıştığı makinenin içerisindeki yalın dile (makine koduna) yorumlanarak çalıştırılır.**

![Compiler](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/bilgi-ifade/figures/DerlemeJava.png)

**Sonuç olarak bilgisayarlar kendilerini 0 ve 1 sayıları aracılığıyla ifade eder. Bilgisayar üzerindeki her şey 1 ve 0'lardan oluşur.**  
**bytecode ->** Java derleyicisinin Java ile yazılmış kodların makine dili yerine kendine has oluşturduğu Binary (0 ve 1) dosyasıdır.  
**JVM ->**Java Bytecode formatına derlenmiş programların çalışmasını sağlayan bir sistemdir.  

### Kaynaklar - 1.2

1. [BİL-110](https://slideplayer.biz.tr/slide/2798593/)
2. [Medium - Java Derleme](https://medium.com/@msenell/derleyi%CC%87ci%CC%87-compiler-ve-yorumlayici-interpreter-%C3%BCzeri%CC%87ne-bi%CC%87r-deneme-d8656619ef6)
3. [Java - Bytecode](https://tr.wikipedia.org/wiki/Java_bytecode)
4. [Wikipedia - Machine code](https://simple.wikipedia.org/wiki/Machine_code)
5. [Wiki of Computer Science](https://computersciencewiki.org/index.php/Data_representation)
6. [JVM](https://www.w3schools.in/java-tutorial/java-virtual-machine/)

### Test - 1.2

**Soru - 1/3**  
**Bilgisayarlar bilgiyi nasıl ifade ederler?**  
İkili Sayılar ile  
**Soru - 2/3**  
**Transistör elektrik akımı ileten, 0 ve 1 ile çalışan bir devre parçasıdır.**  
Doğru  
**Soru - 3/3**  
**Sadece JVM'nin derleyebildiği format aşağıdakilerden hangisidir?**  
.class  

## Sayı Sistemleri

![Sayı Sistemler](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/sayi-sistem/figures/ikili-say%C4%B1.png)

![Durumlar](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/sayi-sistem/figures/durumlar.jpg)

* Onluk sayı sistemindeki bir sayı ikilik sisteme, ikilik sistemdeki bir sayı ise onluk sisteme dönüştürülebilir. Nasıl mı? Hemencecik açıklayalım. Onluk tabanda 120 sayısını ikilik sayı sistemine dönüştürelim.

![İkilik Taban](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/sayi-sistem/figures/ikilik-tabana-%C3%A7evirme.png)

* Peki ya ikilik tabanındaki bir sayıyı onluk tabana nasıl dönüştüreceğiz? Nasıl mı? Beyniniz mi yandı :). Devammm. Sayımız ikilik tabanda 111010 sayısı hadi başlayalım. Az önce öğrendiğimiz bilgiyi çevirmede kullanıyoruz. Aslında 20 dan başlamamızın sebebi onluk sayı sistemine geçirdiğimizden kaynaklanıyor.

![Onluk Taban](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/sayi-sistem/figures/onluk-tabana-%C3%A7evirme.png)

### Kaynaklar - 1.3

1. [İkili Sayı Sistemi](https://tr.wikipedia.org/wiki/%C4%B0kili_say%C4%B1_sistemi)

2. [Binary Number System](https://www.mathsisfun.com/binary-number-system.html)

3. [Convert-Number Systems](https://www.purplemath.com/modules/numbbase.htm)

### Test - 1.3

**Soru - 1/3**  
**Aşağıdakilerden hangisi bir sayı sistemi değildir?**  
Yedilik Sayı Sistemi
**Soru - 2/3**  
**150 sayısının ikili sayı sistemindeki karşılığı hangisidir?**  
10010110  
**Soru - 3/3**  
**1011 0110 0010 sayısının onluk sistemdeki karşılığı nedir?**  
2914  

## Sayısal Olmayan Verilerin Tutulması  

* Bilgisayarda var olan her şey 1 ve 0 dan oluştuğunu geçtiğimiz derste gördük. Binary'den onluk tabana nasıl dönüştüreceğimizi öğrendik. Peki ya bir harfi nasıl ifade edeceğiz? Sayısal olmayan bir ifadenin sembol ile gösterimi yapılabilir. Mesela, 1100010010 sayısını onluk tabana çevirdiğimizde değeri 786, fakat sayı olarak değil de bir sembol olarak incelersek karşılığı W harfi olabilir. Başka bir örnek, elimizde 100101010 sembolü var ve bu sembolün karşılık geldiği değer V olabilir.

![Binary Sembol](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/sayisal-olmayan/figures/binary-symbol.gif)

### Kaynaklar - 1.4  

1. [Binary Sembol](hhttps://en.wikipedia.org/wiki/Binary_code)  

### Test - 1.4

**Soru - 1/3**  
**1001 sembolü 'a' harfini ifade ediyor ise 1010 sembolü aşağıdakilerden hangisi olabilir?**  
'b'  
**Soru - 2/3**  
**Aşağıdakilerden hangisi doğrudur?**  
1001 semnbolü bazen 9 sayısını ifade ederken bazen 'c' harfini ifade edebilir.  
**Soru - 3/3**  
**100101010 bilgisayarda bulunan resmin bir kısmını ifade edebilir.**  
Doğru  

## Verilerin Tutulması  

* Bilgisayar, yapısından dolayı içerisinde tutulabilecek veri miktarı sınırlıdır. Bu verilerin en küçük yapı taşları bitlerdir.

![Verilerin Tutulması](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/veri-tutulma/figures/veri-tutulma.png)

* Şimdi karşımıza çıkan problemlerin bir tanesi, 256 sembolden daha fazla bir depolama alanı isteyebiliriz. Peki bu durum da ne yapacağız? Aslında çözüm çok basit byte'ları yan yana koyarak depolama alanımızı arttıracağız.

![Verilerin Tutulması](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/veri-tutulma/figures/veri-tutulma2.png)

* Binary semboller, kullanan kişiye göre farklılık gösterebilir.

![Verilerin Tutulması](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/veri-tutulma/figures/sembol-veri.png)

### Kaynaklar - 1.5

1. [Bit-Nedir](https://tr.wikipedia.org/wiki/Bit_(bili%C5%9Fim)#Bitler)

2. [Byte-Nedir](https://tr.wikipedia.org/wiki/Bayt)

3. [What is Bit](https://techmonitor.ai/what-is/what-is-a-bit-4950370)

4. [Bit and Bytes](https://web.stanford.edu/class/cs101/bits-bytes.html)

### Test - 1.5

**Soru - 1/3**  
**Bil ile ilgili verilen bilgilerin hangisi doğrudur?**  
Verilerin en küçük yapı taşları bitlerdir.  
**Soru - 2/3**  
**Binary semboller kişiden kişiye farklılık göstermez.**  
Hayır  
**Soru - 3/3**  
**Byte 8 bitten daha fazla bit değeri alamaz.**  
Evet  

## Recursion

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
```

* Bir problemin alt problemlere bölünüp hesaplanmasına, nerde son bulacağımı belirttiğimiz ifadelere recursion (Özyineleme) diyoruz.

![Fibonacci](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/recursion/figures/fibonacci.png)

* Fibonacci serisi 0,1 den başlayarak her önceki 2 sayının toplamı şeklinde bir kurala sahiptir. 0+1 = 1, 1+1=2, 2+1=3, 3+2=5 gibi. Kendinden bir önceki eleman ile iki önceki elemanın toplamı serinin devam sayısını verir. Recursion kullanımı : Fonksiyonumuz fib(x). 3. elemana n diyelim, fib(n-1) + fib(n-2) bize 3.elemanı yani 1 sonucunu verir. fib(n-1) + fib(n-2) => Recursion

### Kaynaklar - 1.6

1. [Özyineleme Nedir?](https://tr.wikipedia.org/wiki/%C3%96zyineleme)

2. [Fibonacci](https://tr.wikipedia.org/wiki/Fibonacci_say%C4%B1)

3. [Explanation of Recursion](https://www.geeksforgeeks.org/recursion/)

### Test - 1.6

**Soru - 1/2**  
**Aşağıdaki tanımların hangisi yanlıştır?**  
Recursion için tekrarın önemi yoktur.Önemli olan sonuçtur.  
**Soru - 2/2**  
**Recursion kendini çağırmak anlamına gelebilir.**  
Doğru  
