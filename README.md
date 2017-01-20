# PSD2 

Bankaların retail tarafında gelir kaybetmesine sebep olan gelişmeler:

* Mobile ödemeler, internet of things, yeni "end-to-end" ödeme sistemleri 
* Fintech startuplar'ı ve uygulama modelleri (http://www.cnbc.com/2016/04/04/10-hottest-fintech-start-ups-to-watch-right-now.html)
* Transaction fee'lerinin piyasa regülatörleri tarafından giderek daha da düşürülmesi

Bu zorlukların 2020'ye kadar ingiliz bankalarınn retail ödeme gelirlerini %43 azaltmasına sebep olacağı öngörülüyor. (2015 : 6,6 milyar € --> 2020 :4,6 milyar € )

Kayıplar: 
* % 27 transaction fee'ye getirilen limitler
* % 7 non-bank aktörler: apple pay, paypal, mpos
* % 9 üçüncü parti PISP hizmetleri

Bankacılık sektörünün dönüşümden daha az etkilenmesi için, Revised Payment Services Directive adlı kurum bazı reformlar öngörüyor: örneğin 2018'e kadar EU zone içerindeki tüm bankaların API'larını non-bank aktörelere açmak zorunda olmaları. 

Aşağıdaki 4 maddeyi sağlayan bankaların gelirlerinin bir kısmını geri kazanabileceği ve  yeni ekosistemin anlamlı bir parçası olabileceğinden bahsediliyor:

## PSD2'nin getirdikleri:

En önemli düzenleme, kullanıcı banka hesabına ulaşabilen 3. parti sağlayıcıların güvenliğini zorunlu hale getirmesi, bankanın, bu amaç için tanımlanan XS2A (access to accounts) kurallarına uyan bir API sunabilmesi 3.partinin de API'ya göre implement edilmiş bir uygulama geliştirmesi şart

XS2A'nın gerçeklenmesi iki farklı servis sağlayıcı modelini mümkün kılıyor:

**PISP** : Müşteri banka hesaplarına güvenli şekilde erişebilen 3.parti Payment Servis Provider, örnek:
[https://trustly.com/en/](https://trustly.com/en/)

Geleneksel modeldeki dükkanın bankasını (acquirer) bypass ediyor, transaction PISP üzerinden tamamlanıyor.
Ödeme zinciri kısaldığı için transaction fee düşüyor  
 
**AISP** : Müşterinin sahip olduğu banka hesapların datasını, transaction history ve harcamalarını da  görebilecek şekilde tutabilen sağlayıcı modeli, aynı zamanda ödeme initate edebiliyor. oteller için trivagonun yaptığına benzer birşey yapıyor, hatta trivago ile kullanıcının arasına giriyor, örneğin oteli vs. seçip sana tatil kredisi çekebileceğin bankayı da buluyor. 

[https://moven.com/](https://moven.com/)
(kişisel bütçe yönetim araçları \)

## PSD2'nin banka için getirdiği riskler
 
* Retailer'ın bankasının bypass ediliyor olması, bankanın transaction gelirinden mahrum kalması demek.( İngiltere'de şimdiden yılda £480 milyon pound satıcının cebinde kalıyormuş)
  
* Ayrıca kart network'ünün de aradan çıkmasıyla transaction başına kesinti 0.68%'den 0.2%'ye düşüyor. Transaction fee'nin daha düşük olması, zamanla retailer'in sadece PSIP modellerini tercih edip bankasıyla ilişkisini bitirmesine yol açabilir

* AISP hizmetlerinin yaygınlaşmasıyla kişisel kullanıcılar için banka neredeyse görünmez hale getiriyor, bu da "Ownership" hissinin aşınmasına neden olabilir. Kullanıcının custom ihtiyaçlarına göre herhangi bir bankadan ürün satın alabilmesi yine bu süreci hızlandırıyor. Yani banka Fintech şirketlerinin sanal bir uzantına gönüşüyor. 

* Uzan vadede, müşteri geri bildiriminin AISP firmada toplanması bankanın negatif feedback almasının önüne geçiyor, bu da bankanın rekabet edebilmesini sağlayan kullanıcı verisinden mahrum kalması demek.

## Bankaların yapması gereken

Makalenin geri kalanında bankaların eski güçlü pozisyonalarından kalabilmeleri için yukarıda özetlediğim dört maddede örneklerle anlatılıyor:

* İlk aşamada bankalar API'larını açıp ekosisteme olabildiğince erken dahil olmalılar, burada yasanın öngördüğü verilere access sağlamaları yeterli 
* İkinic adımda daha gelişkin bir API ile PSIP'lere gelir karşılığı daha fazla veri ve insight sağlayabilecek bir monetization modeli kurmalılar, örneğin demografik bilgileri satmak vs. Yani erişimi modüler ve premium hale getirmek
* 3 ve adımlar, bankanın  PSIP ve AISP aktörlerin işlevlerini kendilerine adapte etmesini öngörüyor, yani son kullanıcıya verilebilecek veri insightları, tavsiyeler vs ile kullanıcı ile bağını koparmayarak veri birikimini elinde tutmaya devam etmesi. Örneğin harcamalar üzerinden tatile çıkma zamanının belirlenmesi, destinasyon tavsiyesi, turistik gezi için kredinin sağlanması, gidilecek yerde otelin bulunması, arabanın kiralanması vs. 
* Ekosistemin genişletilmesi, örneğin daha fazla sektöre yönelik insight/ tavsiye verilmesi. Veri birikiminin arttırılıp gelire dönüştürülmesi. 




