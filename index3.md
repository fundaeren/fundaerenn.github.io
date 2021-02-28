# DİZİN İŞLEMLERİ

# pwd Komutu

Ben neredeyim? Bunu öğrenmek için kullanılır.

![image](https://user-images.githubusercontent.com/55113204/109427724-c0522980-7a04-11eb-881b-6151372927d8.png)

# cd Komutu 

Bir dizine girilmek istendiğinde kullanılır.

![image](https://user-images.githubusercontent.com/55113204/109427726-c47e4700-7a04-11eb-9fb7-64e5ab55defe.png)

Cd .. o dizinden çıkılmak istendiğinde kullanılır.

![image](https://user-images.githubusercontent.com/55113204/109427728-c8aa6480-7a04-11eb-8ed6-ecbc26ddc03b.png)

Cd – ile bir önceki bulunduğumuz dizine döneriz.

![image](https://user-images.githubusercontent.com/55113204/109427734-cd6f1880-7a04-11eb-9581-915fecb8c906.png)
 
Cd - - en başa döneriz.

![image](https://user-images.githubusercontent.com/55113204/109427742-d2cc6300-7a04-11eb-8d18-be41f5742d03.png)

Herhangi bir parametre kullanacak olursak kullanılan komuttan sonra -parametre şeklinde bir dizilim yaparız.

# Full Path 

/ kullanarak çalışma dizine bağlı olmadan istediğimiz yere gidebilmemizi sağlayan araçtır.

![image](https://user-images.githubusercontent.com/55113204/109427751-dcee6180-7a04-11eb-92b9-775b03c41890.png)

# Relative Path

Nerede olduğumuza bağlı olarak yolumuzu belirterek istediğimiz yere o güzergahta gidebildiğimiz araçtır.
 
![image](https://user-images.githubusercontent.com/55113204/109427757-e677c980-7a04-11eb-8f68-16975675e955.png)

O komutlar hakkında daha fazla bilgi edinmek için man, help ve info komutları kullanılmaktadır.
Man ile ls komutu hakkında bilgi edinelim

# Komut man help

![image](https://user-images.githubusercontent.com/55113204/109427777-fee7e400-7a04-11eb-9ed8-cfa69f2e4970.png)
 
Help komutu ile ls hakkında bilgi edinelim. 

![image](https://user-images.githubusercontent.com/55113204/109427781-03ac9800-7a05-11eb-83a6-996dadea08da.png)
 
Info kumutu ile bilgi edinme

![image](https://user-images.githubusercontent.com/55113204/109427785-0909e280-7a05-11eb-97ab-33f4e4497586.png)

# mkdir Komutu

Dizin oluşturmak için kullanılır. 

![image](https://user-images.githubusercontent.com/55113204/109427789-10c98700-7a05-11eb-9678-33be3647ae65.png)

Alt dizinlerde aynı anda oluşturulabilir.

![image](https://user-images.githubusercontent.com/55113204/109427791-158e3b00-7a05-11eb-97ba-b086e4bfb3e5.png)

# rmdir Komutu

İçi boş dizinleri silmek için rm komutu kullanılır.

![image](https://user-images.githubusercontent.com/55113204/109427794-1c1cb280-7a05-11eb-9e9d-182f0d50e6bf.png)

# rm Komutu

İçi dolu dosyaları silmek için rm, dizinleri silmek için rm -r komutu kullanılır.

![image](https://user-images.githubusercontent.com/55113204/109427801-22ab2a00-7a05-11eb-8cf9-1cfd0f46bea9.png)

## -i Parametresi

-i parametresi silinsin mi silinmesin mi onu sorgular.

![image](https://user-images.githubusercontent.com/55113204/109427809-2a6ace80-7a05-11eb-8861-5cdf6e0c3570.png)

## -f Parametresi

-f parametresi sormadan siler

## -r Parametresi

-r parametresi bulunduğu dizinin alt dizinlerini de siler.

## -v Parametresi

-v parametresi ne yapıldığı bilgisini alt kullanıcıya da döndürür. 

![image](https://user-images.githubusercontent.com/55113204/109427813-30f94600-7a05-11eb-9d1e-cc1c7ff58a16.png)

# ln Komutu

Dosyalara link yapmak için kullanılır.

![image](https://user-images.githubusercontent.com/55113204/109427820-35bdfa00-7a05-11eb-8fb5-049328030044.png)

![image](https://user-images.githubusercontent.com/55113204/109427839-3e163500-7a05-11eb-8fbc-f003d04e0075.png)

![image](https://user-images.githubusercontent.com/55113204/109427843-41112580-7a05-11eb-874b-d6766c7f283c.png)
  
# file Komutu

Dosya mı dizin mi ne olduğunu bilmediğimiz zaman bu komutu kullanarak öğrenebiliriz.

![image](https://user-images.githubusercontent.com/55113204/109427850-49696080-7a05-11eb-8d2e-32a3a6bb47e4.png)

‘>’ önüne 1 yazılır yada yazılmaz ise standart çıkışı ekrana verir. 2 yazılırsa komut çalışırken alınan hatalar dosyaya yönlendirilir. Yönlendirmede kullanılan tek ‘>’ eğer yönlendirilecek dosya yoksa dosya oluşturulur varsa dosya içi temizlenir ve çıktıyı yönlendirmektedir.
Yönlendirmedeki yönlendirme işaretinin çift olması “>>”,eğer yönlendirilecek dosya yok ise oluşturulur, dosya var ise çıktıyı dosyanın sonuna yönlendirir.

‘^’  Satır başını belirtir.
‘$’ Satır sonlarını belirtir.
‘.’ Sadece bir karakter ile eşleşir,bir karakter ifade eder
‘*’ Kendinden önceki karakterden 0 veya daha fazla olmasını belirtir
‘[]’ Köşeli Parantez içindeki karakterlerden sadece biriyle eşleşir.
‘[^]’ Köşeli parantez içinde olmayan karakterlerle eşleşir.
+ Kendinden önceki karakter en az 1 veya daha fazla karakteri ifade eder.
