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
- Metotlar
- - onCreate: actility sayfamızın üretilmesi esnasında kullanacağımız özel bir metottur. Bu metot olmazsa Activity sayfası üretilemez. OnCreate metotu kodların yazılacağı ana metottur. OnCreate metodu sayesinde .java uzantılı sayfamızı, .xml uzantılı arayüz sayfalarına SentView() metodu sayesinde bağlanıp Activity üretmiş oluruz. Değişken üretmek, bir değişkene varsayılan değer atamak onCreate metodu zamanında ... tanımlamaları yine onCreate metodu içerisinde gerçekleşir. Bir buton üretmek, üretilen butonu tıklama olayını yazmak onCreate içerisinde tanımlanmak zorundadır. Activity sınıfı üretildiği zaman, 1 defa çalışır (uygulama açıkken).

- - onRestart: Activity sayfasını yeniden başlatmak için kullanılır. Uygulama sayfasının tekrar başlatılma zamanıdır. 

- - onStart: onCreate metodundan sonra onStart metodu çalışır. Activity sınıfı üretildikten sonra çalışan 2. metottur. 

- - onResume: onStart metodundan sonra çalışır. Görevi activity sınıfının çalışmaya devam ettiği zamanda yapılacak işlemlerin tanımlanabildiği metottur.

- - onStop: Activity sayfasının arayüzde olmaması, uygulamanın alta indirilmesi durumunda çalışan metottur. Activity sınıfı kapatılmadan önce yani onDestroy metodundan önce çalışan metottur. 

- - onPause: onStop'tan önce çalışır. Activity sayfası durdurulmadan önce çalıştırılacak metottur.

- - onDestroy: Activity sayfasını kapatılmadan önce son olarak gidebileceğimiz özel bir metottur. Bir sayfa kapatılmadan önce yapılması gereken özel bir metottur. onDestroy metodunu çalıştırabilmek için geri git butonunu ya da finish() metotunu tetiklemek yeterlidir.

- Uygulama Kaynakları
- - R: Resource'un kısatmasıdır. 
- - R.id: 
- - R.anim:
- - R.attr:
- - R.bool:
- - R.color:
- - R.dimen:
- - R.drawable:
- - R.integer:
- - R.layout:
- - R.mipmap:
- - R.string:
- - R.style:
- - R.styleable:

-res Klasörünün Önemi:
- - res klasörü altındaki tüm kalsör isimleriözeldir. 
- - - Klasörler altındaki 

Özel Res Klasörleri:
- - anim
- - animator
- - color: uygulamanın içerisinde bulunan renk tanımlamalarının yapılabileceği klasördür.
- - drawable: Çizim dosyaları bulundurabilen klasördür. İçerisinde .png, .jpg, .xml (vektörel çizim dosyası) gönderilebilir. Uygulama içerisindeki resim dosyalarının saklanabileceği özel bir klasördür. 
- - font
- - interpolator
- - layout: .xml uzantılı layout dosyaları bu klasör altında saklayabiliriz. Uygulama UI Design (arayüz tasarımı) ile alakalı işlemleri burada saklayabiliriz.
- - menu: Menu dosyaları üretebilmek için kullanılır. .xml uzantılı dosyaları burada saklayabiliriz.  
- - mipmap: Uygulama ikonlarının saklanmış olduğu özel klasördür. 
- - navigation:
- - raw: .mp4, .mp3, wav gibi ses ve video içerikli dosyaların uygulama içerisinde saklanabileceği klasördür.
- - values: strings.xml (uygulama içindeki metin dosyalarının saklandığı ifadeler. Değişken gibi tanımlanır.), color.xml(app renkleri) styles.xml(android app temaları - dark vs -) gibi özel klasörleri barındırır.
- - transition: Sayfa geçiş animasyonlarının tanımlanabileceği özel bir klasördür.









