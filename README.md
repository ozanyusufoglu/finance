Ödeme sistemlerindeki yenilikler, bankaların retail tarafında gelir kaybetmesine sebep oluyor:

* mobile transactions, internet of things, yeni end-to-end value teknolojileri
* yeni fintech şirketler, uygulamaları ve modelleri
* interchange fee'lerin (transaction fee) kural koyucular tarafından sınırlandırılması

Bu zorlukların 2020'ye kadar ingiliz bankalarınn retail ödemelerden toplam karının %43 azaltmasına sebep olacağı öngörülüyor. (2015 : 6,6 milyar € --> 2020 :4,6 milyar € )

Kayıplar: 
* % 27 transaction fee'ye getirilen limitler
* % 7 non-bank aktörler: apple pay, paypal, mpos
* % 9 pisp services

Sürecin hızlanması ile birlikte bankaların entegre olabilmesi için Revised Payment Services Directive yeni dünelemeler getirecek, böylece bankaların api'larını non-bank aktörelere açmları zorunlu hale getirilecek. 4 maddeyi sağlayan bankalar gelirlerin bir kısmını geri kazanabilir:

* PSD2'ye uygunluk, şartları yerine getirme
* api'ye erişimin kolaylaştırılması ve para kazanma modelinin kurulması
* danışmanlık ve yeni hizmetlerin/ürünlerin sağlanması
* ekosistemin genişletilmesi ve değer birikimi


## PSD2'nin getirdikleri:

En önemli düzenleme, kullanıcı banka hesabına ulaşabilen 3. parti sağlayıcıların güvenliğini zorunlu hale getirmesi , bunun için bankanın XS2A (access to accounts) kurallarına uyan bir API sunabilmesi 3.partinin de API'ya göre implement edilmiş bir uygulama geliştirmesi şart

PSD2'nin gerçekleştirilmesi, iki farklı servis sağlayıcı modelini mümkün kılıyor:

**PISP** : Müşteri banka hesaplarına güvenli şekilde erişebilen 3.parti Payment Servis Provider, örnek:
[https://trustly.com/en/](https://trustly.com/en/)

Basitçe geleneksel modeldeki dükkanın bankasını (acquirer) bypass ediyor, transaction PISP üzerinden tamamlanıyor

**AISP** : Müşterinin sahip olduğu banka hesapların datasını, transaction history ve harcamaları görebilecek şekilde tutabilen sağlayıcı modeli

[https://moven.com/](https://moven.com/)
(kişisel bütçe yönetim araçları \)

## Grocery :

**PISP** :

**interchange fee:** retail kredi kartı ödemesinde transaction başına ödenen komisyon, acquirer --> issuer'a ödüyor





