  # STANDART-CIKTI-ALMA-FONKSIYONU
  Python'da standart çıktı almak için en yaygın kullanılan fonksiyon print() fonksiyonudur. print() fonksiyonu, metin veya değişkenlerin değerlerini ekrana yazdırmak için kullanılır.

print() Fonksiyonu
Temel Kullanım: print() fonksiyonu, parametre olarak verilen ifadeyi veya değişkenin değerini ekrana basar.
Birden fazla parametre: Birden fazla parametre yazdırılabilir ve bunlar arasında boşluk ile ayrılır.
Satır Sonu: print() fonksiyonu, varsayılan olarak çıktının sonuna bir satır sonu (\n) karakteri ekler. Eğer satır sonu eklenmek istenmiyorsa, end parametresi kullanılabilir.
Örnekler:
1. Temel Kullanım:
python
Kodu kopyala
# Değişken tanımlama
a = 10
b = 3.14

# Ekrana yazdırma
print(a)  # Integer değer yazdırılır
print(b)  # Float değer yazdırılır
Çıktı:

Kodu kopyala
10
3.14
2. Birden Fazla Değişkeni Aynı Anda Yazdırma:
python
Kodu kopyala
a = 10
b = 3.14
c = "Merhaba"

# Birden fazla değişkeni yazdırma
print(a, b, c)
Çıktı:

Kodu kopyala
10 3.14 Merhaba
Not: print() fonksiyonu, parametreler arasında otomatik olarak bir boşluk (' ') ekler.
3. Formatlı Çıktı Yazdırma (f-string):
Python 3.6 ve sonrasında, f-string (formatlı string) kullanarak daha okunabilir ve esnek çıktı alabilirsiniz. F-string, değişkenleri doğrudan string içinde yerleştirmeye imkan tanır.

python
Kodu kopyala
a = 10
b = 3.14
c = "Merhaba"

# F-string ile formatlı çıktı
print(f"A: {a}, B: {b}, C: {c}")
Çıktı:

yaml
Kodu kopyala
A: 10, B: 3.14, C: Merhaba
4. Satır Sonu Eklememek İçin end Parametresi Kullanma:
Varsayılan olarak, print() fonksiyonu her yazdırmadan sonra bir satır sonu ekler. Eğer satır sonu eklenmek istenmiyorsa, end parametresi kullanılabilir.

python
Kodu kopyala
# Satır sonu eklenmeden çıktı
print("Bu birinci satır.", end=" ")
print("Bu ikinci satır.")
Çıktı:

Kodu kopyala
Bu birinci satır. Bu ikinci satır.
Not: end parametresinin varsayılan değeri \n yani satır sonu karakteridir. Ancak bu değeri değiştirebilirsiniz (örneğin, boşluk, virgül veya başka bir karakter eklemek için).
5. Değişkenleri ve Hesaplamaları Yazdırma:
Değişkenlerin ve ifadelerin hesaplamalarının sonucunu da yazdırabilirsiniz.

python
Kodu kopyala
a = 5
b = 3

# Hesaplamayı yazdırma
print(f"{a} + {b} = {a + b}")
Çıktı:

Kodu kopyala
5 + 3 = 8
Sonuç:
Python'da print() fonksiyonu, çok yönlüdür ve temel çıktı işlemlerinden daha karmaşık formatlı çıktılara kadar her şey için kullanılabilir. Ayrıca, yazdırma işlemi sırasında metin ve değişkenler birleştirilebilir, formatlama yapılabilir, ve yazdırma sonucunda satır sonu eklenip eklenmeyeceği kontrol edilebilir.
