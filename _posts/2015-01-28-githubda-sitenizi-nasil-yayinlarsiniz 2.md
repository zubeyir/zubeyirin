---
layout: post
title: Github'da sitenizi nasıl yayınlarsınız?
---

Birçok *WordPress*, *BlogSpot* ve benzeri içerik yönetim sistemleri (content management system, CMS) varken neden başka birşey kullanayım diye sorabilirsiniz.

Aslında kullanmanıza gerek yok. Sadece, benim gibi bu sitelerin verdiği sonuçlardan, herşeye hakim olamamaktan ve arka planda yürüyen işlerin karmaşıklığından sıkıldıysanız bunu yapmak isteyebilirsiniz.

Github, ortak ve herkesin katkı verebileceği yazılım projeleri geliştirmek için bir ortam. Bu ortamı yalnızca bu amaç için kullanmak haksızlık gibi. Ortak çalışma yapılabilecek tüm amaçlar için kullanılabilir. Sağladığı en büyük avantaj sizin ve ekibinizin yaptığı değişiklikleri görebilmeniz ve ekibin projenin farklı kısımları üzerinde aynı anda çalışabilmesi ve sonra bunların bir bütün içerisinde birleştirilebilmesi.

Websitesi oluşturmak için sağladığı avantaj ise CMS'lerin ihtiyacı olan veritabanı ve PHP gibi karmaşık dilleri kullanmaya ihtiyaç olmaması. Yaptığınız herşey gayet şeffaf bir biçimde elinizin altında. Oluşturduğunuz metin dosyalarını web sayfalarına dönüştürüp internette yayınlıyorsunuz. Eskiden olduğu gibi web sayfalarınız sadece .html sayfalardan oluşuyor. Aslında son zamanlarda WP gibi CMS sistemleride sitelerinizin sunumunu hızlandırmak için nihai olarak dinamik websitelerini statik .html dosyaların dönüştürüp ziyaretçilere bunu sunuyorlar.

WP, BS gibi sitelerin sağladığı önemli avantajlardan biri blog yazabilmeniz. Github üzerinde oluşturduğunuz statik sayfaları da isterseniz bir blog olarak yayınlayabiliyorsunuz. Bunu yapmak için Jekyll'e ihtiyacınız var ve işler burada kısa bir öğrenmeyi gerektiyor.

Github üzerinde bu işleri yapmanın bir diğer avantajı websitemi *nerede saklayacağım* sorunu olmaması. Github sitenizi sizin için saklıyor, kimseye para vermiyorsunuz. Github üzerinde oluşturduğunuz siteler kullaniciadi.github.io adresine sahip olabileceği gibi isterseniz kendinize özel bir alan adı alıp websitenizi bu alan adına yönlendirebiliyorsunuz. Mesela bu sitenin Github adı zubeyir.github.io olmasına karşın özel ismi zubeyir.in ve bu adresi kullanarak bu siteye ulaşabiliyorsunuz.

Github'da websitemi oluşturmak için ne yapmanız gerektiğini yazının devamında anlatmaya çalışacağım. Aşağıda bahsettiklerim karmaşık görünebilir. Bir kere anlaşıldığında o kadar da zor olmadığını göreceksiniz.

Github'dan faydalanmak için önce Github üzerinde bir kullanıcı oluşturmak gerekiyor.

Kullanıcı adını oluşturduktan sonra kullaniciadi.github.io adlı bir repository oluşturun.

https://github.com/mdo/hyde adlı repository'i buraya fork edin.

Jekyll ile derleyin ve kendi repository'nize push edin.

Klasör ve dosyaların yapısını anladıktan sonra sitenizi değiştirmek çok kolay bir hale geliyor. Bu klasör ve dosyaların yapısından bir sonraki yazıda bahsedeceğim.
