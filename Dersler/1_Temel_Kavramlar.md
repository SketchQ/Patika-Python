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
