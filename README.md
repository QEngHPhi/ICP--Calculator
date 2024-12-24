# ICP-Calculator

Merhaba,

2025 Patika.dev Web3 Stajı programına katılmak istiyorum. Hacettepe Üniversitesi Endüstri Mühendisliği 2. sınıf öğrencisiyim ve Ankara'da yaşıyorum. Web3 teknolojileri konusunda çok heyecanlıyım; özellikle Internet Computer Protokolü (ICP) ve Motoko dili ile merkeziyetsiz uygulamalar geliştirme konusunda kendimi geliştirmek istiyorum.

Patika.dev'in sunduğu workshoplar ve topluluk etkinliklerinin bilgi birikimimi artırırken, pratik deneyim kazanmamı da sağlayacağına inanıyorum. Ekip çalışmasına yatkın ve öğrenmeye açık biri olarak bu programa değer katabileceğime inanıyorum.

Bu fırsatın bir parçası olma şansını elde etmek benim için çok önemli. Değerlendirme sürecinde zaman ayırdığınız için şimdiden teşekkür ederim.

Sevgilerimle, [Metin Bera Süslü]

---

Bu projede bir hesap makinesi yaptım. actor hesap_makinesi diye bir yapı var, bu yapı sayesinde sanki bir hesap makinesi ile konuşuyormuşuz gibi çalışıyor. İçinde birkaç tane fonksiyon var, toplama, çıkarma, çarpma, bölme ve bir de temizleme işlemi yapabiliyor.

Başta bir hucre adında bir değişkenim var. Bu hesap makinesinin içinde bir bellek gibi düşünebilirsin, tüm işlemleri bunun üzerinde yapıyorum. Başlangıçta hucre sıfır.

Toplama: toplama diye bir fonksiyon yazdım. İçine bir sayı veriyorsun, o sayıyı hucre'ye ekliyor ve sonucu sana geri döndürüyor. Mesela hucre başta 5 olsun, toplama(3) dersen, hucre 8 oluyor ve sana 8'i veriyor.
Çıkarma: Aynı şekilde cikarma var. Verdiğin sayıyı hucre'den çıkarıyor. Mesela hucre 8'di ya, cikarma(2) dersen, bu sefer hucre 6 oluyor.
Çarpma: Bunun adı da carpma. hucre'yi verdiğin sayıyla çarpıyor. Mesela carpma(3) dedik diyelim, hucre 18 oluyor.
Bölme: Bu biraz hassas, çünkü bir sayıyı 0’a bölemezsin ya, işte ben de onu düşündüm. Eğer verdiğin sayı 0 ise "null" döndürüyor, yani “Bunu yapamam” diyor. Ama sıfır değilse normal bölme işlemi yapıp sonucu sana geri veriyor.
Temizle: Diyelim ki kafan karıştı ya da yeni bir işlem yapmak istiyorsun, temizle fonksiyonu var. Bu direkt hucreyi sıfırlıyor.
Özetle, bu hesap makinesi sadece bir sayıyı değil, önceki işlemlerden kalan değeri de hatırlıyor ve onun üstünde işlem yapıyor. Yani sıfırdan başlamak zorunda değilsin, hep kaldığın yerden devam ediyorsun. Böyle bir hesap makinesi yaptım işte! 😊
