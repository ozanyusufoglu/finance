# PSD2 

Bankaların retail tarafında kredi kartı gelirlerini kaybetmesine sebep olan gelişmeler:

* Mobil ödemeler, internet of things, yeni end-to-end ödeme sistemleri 
* Fintech startuplar'ı ve uygulama modelleri (http://www.cnbc.com/2016/04/04/10-hottest-fintech-start-ups-to-watch-right-now.html)
* Transaction fee'lerinin piyasa regülatörleri tarafından giderek daha da düşürülmesi

Bu gelişmelerin 2020'ye kadar İngiliz bankalarının retail ödeme gelirlerini %43 azaltmasına sebep olacağı öngörülüyor(2015 : 6,6 milyar € --> 2020 :4,6 milyar €).

Kayıplar: 
* % 27 transaction fee'ye getirilen kısıtlamalardan dolayı 
* % 7 non-bankink aktörler: Apple pay, Paypal, mpos
* % 9 üçüncü parti PISP hizmetleri

Bankacılık sektörünün bu dönüşümlerden daha az etkilenmesi için ve uyum sağlayabilmesi için Revised Payment Services Directive adlı yaptırım bazı reformlar öngörüyor: 2018'e kadar EU zone içerindeki tüm bankaların API'larını banka dışı aktörelere açmak zorunda olmaları gibi.


## PSD2'nin getirdikleri:

Düzenlemenin temelinde, müşteri banka hesabına ulaşabilen 3. parti sağlayıcıların (PISP) standart ve güvenli bir yol izlemelerini sağlamak. Bu amaca yönelik tanımlanan XS2A (Access to Accounts) kuralları, bankanın uygun bir API sunabilmesi, 3.parti sağlayıcının da API'ya göre implemente edilmiş bir uygulama geliştirmesini sağlıyor. 

XS2A iki temel servis sağlayıcı modelinini adresliyor:

**PISP** : Müşteri banka hesaplarına güvenli şekilde erişebilen 3.parti Payment Servis Provider, örnek:
[https://trustly.com/en/](https://trustly.com/en/)

Geleneksel modeldeki satıcı(retailer) bankasını (Acquirer Bank) ve kredi kartı ağını ( Visa, Master) bypass eden bu modelde, ödeme PISP üzerinde başlatılıyor müşteri bankasına API aracılığıyla bağlanıp transaction gerçekleştiriliyor. Fazla aktörlerin aradan çıkmasıyla ödeme zincirinin kısalması, toplam transaction fee oranını, satıcının lehine olacak şekilde düşürüyor.  
 
**AISP** : Müşterinin sahip olduğu farklı banka hesapları verilerini, transaction history ve harcamaları  görebilecek şekilde saklayabilen sağlayıcı modeli, aynı zamanda PISP gibi ödeme initate edebiliyor. Oteller için Trivago'nun yaptığı gibi birden fazla bankanın API'na erişebiliyor. Hatta Trivago benzeri uygulamalar ile müşteria arasında bir katman olarak giribiliyor, örneğin müşteri verisi üzerinden derlediği insight'lar sayesinde tatile çıkmak için en uygun zamanı belirlenmesi, gezide kullanılacaksa ihtiyaç kredisinin ayarlanması,  destinasyon, otel bulunması ve arabanın kiralanma tavsiyeleri ve ürünlerin satın alınabilmesi ... 

[https://moven.com/](https://moven.com/)
(kişisel bütçe yönetim araçları \)

## PSD2'nin Bankaların Gelirlerini Olumsuz Etkisi
 
* Satıcı bankasının bypass ediliyor olması, bankanın transaction gelirlerinden mahrum kalması demek( İngiltere'de şimdiden yılda £480 milyon pound, satıcıların cebinde kalıyor).
  
* Kart Ağı'nın (Visa, Master) aradan çıkmasıyla transaction başına komisyon 0.68%'den 0.2%'ye kadar düşebiliyor(Toplam komisyonun, geleneksel sisteme oranla çok daha düşük olması, zamanla retailer'in sadece PISP modellerini tercih etmesine sebep olup, bankanın müşteriyi kaybetmesine sebep olabiliyor.

* AISP hizmetlerinin yaygınlaşması müşteriye bakan tarafta bankayı neredeyse görünmez hale getiriyor, bu da "ownership" hissinin aşınmasına neden oluyor. Kullanıcının custom ihtiyaçlarına göre herhangi bir bankadan ürün satın alabilmesi bu süreci daha da hızlandırıyor. Yani bankalar, fintech şirketlerinin sanal bir uzantına gönüşüyor, müşterinin banka ürününe sahiplik hissi yok oluyor. 

* Uzan vadede, müşteri geri bildiriminin AISP firmada toplanması bankanın negatif feedback almasının önüne geçiyor, bu da bankanın rekabet edebilmesini sağlayan kullanıcı verisinden mahrum kalması demek.

## Bankaların yapması gereken

Makalenin geri kalanında bankaların eski güçlü pozisyonalarından kalabilmeleri için yukarıda özetlediğim dört maddede örneklerle anlatılıyor:

* İlk aşamada bankalar API'larını açıp ekosisteme olabildiğince erken dahil olmalılar, burada yasanın öngördüğü verilere access sağlamaları yeterli 
* İkinic adımda daha gelişkin bir API ile PSIP'lere gelir karşılığı daha fazla veri ve insight sağlayabilecek bir monetization modeli kurmalılar, örneğin demografik bilgileri satmak vs. Yani erişimi modüler ve premium hale getirmek
* 3 ve adımlar, bankanın  PSIP ve AISP aktörlerin işlevlerini kendilerine adapte etmesini öngörüyor, yani son kullanıcıya verilebilecek veri insightları, tavsiyeler vs ile kullanıcı ile bağını koparmayarak veri birikimini elinde tutmaya devam etmesi. Örneğin harcamalar üzerinden tatile çıkma zamanının belirlenmesi, destinasyon tavsiyesi, turistik gezi için kredinin sağlanması, gidilecek yerde otelin bulunması, arabanın kiralanması vs. 
* Ekosistemin genişletilmesi, örneğin daha fazla sektöre yönelik insight/ tavsiye verilmesi. Veri birikiminin arttırılıp gelire dönüştürülmesi. 




