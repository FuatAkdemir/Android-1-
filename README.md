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

## 3. Hafta
### 07.10.2019
- Sayaç örneği

### 08.10.2019
- Farklı buton kullanımları
- WebView kullanımı
- ScroolView kullanımı (Programatik olarak nesne üretme)

### 09.10.2019
- Adapter Sınıfını Kullanan Nesneler (aşağıdakiler tek başlarına kullanılamazlar)
-- Spinner: Array adapter, base adapter
-- AutoCompleteTextView: Array adapter, base adapter
-- MultiAutoCompleteTextView: Array adapter, base adapter
-- ListView: Array adapter, base adapter
-- GridView: Array adapter, base adapter
-- RecycleView: En zengin adapter sınıfıdır. Kendine has bir adapter'ı vardır.

## 4. Hafta
### 14.10.2019
- Intent'ler
- Intent ve Image'lar
- Menü oluşturma

### 15.10.2019
- Farklı Intent Kullanımları
- https://serifgungor.com/uploads/pdf/Mobil_Optimizasyon_ve_Responsive_Design.pdf
- StartActivityForResult örnekleri

### 16.10.2019
- CustomListView Örneği
-- 1) İlgili Activity layout'unda listView üret ve referansları tanıt, eşle.
-- 2) İlgili satır dosyasının layout'unu üret (resim, başlık, yazı).
-- 3) Model sınıfını üret (Kapsülleme işlemi)
-- 4) BaseAdapter sınıfını üret
-- 5) BaseAdapter sınıfına context, LayoutInslater ve ArrayList nesneleri üret
-- 6) BaseAdapter için boş ve dolu construct üret
-- 7) getCount, getItemId, getView metotlarını doldur.
-- 8) return'lerin içini düzelt.

- SharedPreferences Kullanımı Örneği
-- Web'deki session - cockie mantığının mobil hali. Örneğin login ekranında kullanıcının mail adresini vs hafızaya kaydetmek için kullanılır.
-- Temel veri yapıları (string, boolean, int vs) hafızaya kaydedebiliyor. Ama boyutu çok olamaz. Mesela string ise bir makale ekleyemeyiz. Bazı durumlarda intent'lerle veri taşımak mantıksız olabilir. Örneğin A -> B -> C sayfalarında intentle veri taşımak mantıksızdır. A'dan direkt C'ye verileri Sharedpreferences ile taşıyabiliriz.
-- Uygulamayı kapatıp açtığımızda hafızada kalır. Hafızadan silmek için ya uygulamayı silmek ya da ön belleği temizlemek gerekir.
-- Sharedpreferences örneğin bir uygulamayı ilk kurduğumuzda tanıtım ekranı getirmek için kullanılabilir. Skip ile atlayıp daha sonra "bir daha gösterme" seçeneği ile false'a çekebiliriz.
-- key - value şeklinde çalışır.

## 5. Hafta
### 21.10.2019
Fıkra Örneği
- SplashActivity




