# Android-1-

## 1. Hafta
### 23.09.2019
- Sınav + Tanışma

## 2. Hafta
### 30.09.2019
- Layout'lar
- - Relative
- - Constraint 
- - Linear

### 02.10.2019
- - onCreate: actility sayfamızın üretilmesi esnasında kullanacağımız özel bir metottur. Bu metot olmazsa Activity sayfası üretilemez. OnCreate metotu kodların yazılacağı ana metottur. OnCreate metodu sayesinde .java uzantılı sayfamızı, .xml uzantılı arayüz sayfalarına SentView() metodu sayesinde bağlanıp Activity üretmiş oluruz. Değişken üretmek, bir değişkene varsayılan değer atamak onCreate metodu zamanında ... tanımlamaları yine onCreate metodu içerisinde gerçekleşir. Bir buton üretmek, üretilen butonu tıklama olayını yazmak onCreate içerisinde tanımlanmak zorundadır. Activity sınıfı üretildiği zaman, 1 defa çalışır (uygulama açıkken).

- - onRestart: Activity sayfasını yeniden başlatmak için kullanılır. Uygulama sayfasının tekrar başlatılma zamanıdır. 

- - onStart: onCreate metodundan sonra onStart metodu çalışır. Activity sınıfı üretildikten sonra çalışan 2. metottur. 

- - onResume: onStart metodundan sonra çalışır. Görevi activity sınıfının çalışmaya devam ettiği zamanda yapılacak işlemlerin tanımlanabildiği metottur.

- - onStop: Activity sayfasının arayüzde olmaması, uygulamanın alta indirilmesi durumunda çalışan metottur. Activity sınıfı kapatılmadan önce yani onDestroy metodundan önce çalışan metottur. 

- - onPause: onStop'tan önce çalışır. Activity sayfası durdurulmadan önce çalıştırılacak metottur.

- - onDestroy: Activity sayfasını kapatılmadan önce son olarak gidebileceğimiz özel bir metottur. Bir sayfa kapatılmadan önce yapılması gereken özel bir metottur. onDestroy metodunu çalıştırabilmek için geri git butonunu ya da finish() metotunu tetiklemek yeterlidir.


