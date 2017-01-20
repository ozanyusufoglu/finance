# PSD2 

Payment Services Directive, EU ve EEA zone içerisinde ödeme sektörü kurallarını düzenleyen yönergenin adı. Bankacılık sektörünün son yıllardaki dönüşümlerden daha az etkilenmesi ve uyum sağlayabilmesi için bu yönergenin yenilenmiş versiyonu, Revised Payment Services Directive (PSD2), bazı reformları öngörüyor, örneğin 2018'e kadar EU zone içerindeki tüm bankaların API'larını banka dışı aktörelere açmak zorunda olmaları.

Bankaların retail tarafında kredi kartı gelirlerini kaybetmesine sebep olan gelişmeler şunlar: 

* Dijital ödeme alternatifleri (Apple Pay, Google Wallet, Paypal)
* Finans-teknoloji start-up'ları ile sayısı artan 3.parti ödeme sağlayıcılar (http://www.cnbc.com/2016/04/04/10-hottest-fintech-start-ups-to-watch-right-now.html) 
* Transaction başına alınan ücretlerinin piyasa regülatörleri tarafından sınırlandırılması
* Mobil ödemeler, Internet of Things, yeni uçtan-uca ödeme çözümleri

Bu gelişmelerin 2020'ye kadar İngiliz bankalarının retail ödeme gelirlerini %43 azaltmasına sebep olacağı öngörülüyor(2015 : 6,6 milyar € --> 2020 :4,6 milyar €).

Kayıplar: 
* % 27 transaction fee'ye getirilen kısıtlamalardan dolayı 
* % 7 non-bankink aktörler: Apple pay, Paypal, mpos
* % 9 üçüncü parti PISP hizmetleri

 


## PSD2'nin getirdikleri:

Düzenlemenin temelinde, müşteri banka hesabına ulaşabilen 3. parti sağlayıcıların (PISP) standart ve güvenli bir yol izlemelerini sağlamak yatıyor. Bu amaca yönelik tanımlanan XS2A (Access to Accounts) kuralları, bankanın uygun bir API sunabilmesi, 3.parti sağlayıcının da API'ya göre gerçeklenmiş bir uygulama geliştirmesini sağlıyor. 

XS2A iki temel servis sağlayıcı modelinini adresliyor:

**PISP** : Müşteri banka hesaplarına güvenli şekilde erişebilen 3.parti Payment Initiator Service Provider, örnek:
[https://trustly.com/en/](https://trustly.com/en/)

Geleneksel modeldeki satıcı(retailer) bankasını (Acquirer Bank) ve kredi kartı ağını ( Visa, Master) bypass eden bu modelde, ödeme PISP üzerinde başlatılıyor müşteri bankasına API aracılığıyla bağlanıp transaction gerçekleştiriliyor. Fazla aktörlerin aradan çıkmasıyla ödeme zincirinin kısalması, toplam transaction fee oranını, satıcının lehine olacak şekilde düşürüyor.  
 
**AISP** : Müşterinin sahip olduğu farklı banka hesapları verilerini, transaction history ve harcamaları  görebilecek şekilde saklayabilen sağlayıcı modeli, aynı zamanda PISP gibi ödeme initate edebiliyor. Oteller için Trivago'nun yaptığı gibi birden fazla bankanın API'na erişebiliyor. Hatta Trivago benzeri uygulamalar ile müşteri arasında bir katman olarak giribiliyor, örneğin müşteri verisi üzerinden derlediği insight'lar sayesinde tatile çıkmak için en uygun zamanın belirlenmesi, gezide kullanılacaksa ihtiyaç kredisinin ayarlanması,  destinasyon, otel bulunması ve arabanın kiralanma tavsiyeleri ve ürünlerin satın alınabilmesi ... 

[https://moven.com/](https://moven.com/)
(kişisel bütçe yönetim araçları \)

## PSD2'nin Bankaların Gelirlerini Olumsuz Etkisi
 
* Satıcı bankasının bypass ediliyor olması, bankanın transaction gelirlerinden mahrum kalması demek( İngiltere'de şimdiden yılda £480 milyon pound, satıcıların cebinde kalıyor).
  
* Kart Ağı'nın (Visa, Master) aradan çıkmasıyla transaction başına komisyon 0.68%'den 0.2%'ye kadar düşebiliyor(Toplam komisyonun, geleneksel sisteme oranla çok daha düşük olması, zamanla retailer'in sadece PISP modellerini tercih etmesine sebep olup, bankanın müşteriyi kaybetmesine sebep olabiliyor.

* AISP hizmetlerinin yaygınlaşması müşteriye bakan tarafta bankayı neredeyse görünmez hale getiriyor, bu da "ownership" hissinin aşınmasına neden oluyor. Kullanıcının custom ihtiyaçlarına göre herhangi bir bankadan ürün satın alabilmesi bu süreci daha da hızlandırıyor. Yani bankalar, fintech şirketlerinin sanal bir uzantına gönüşüyor, müşterinin banka ürününe sahiplik hissi yok oluyor. 

* Uzan vadede, müşteri geri bildiriminin AISP firmada toplanması bankanın müşteri geri bildirimlerini toplamasını engelliyor, bu da bankanın rekabetteki yerini belirleyebilmesi için ihtiyaç duyduğu kullanıcı verisinden mahrum kalması anlamına geliyor.

## Bankaların Yapması Gereken

Bankaların bugünkü pozisyonalarını koruyabilmeleri için dört aşama var: 

1. PSD2 yönergesine uygun hale gelecek şekilde, API'larını banka-dışı aktörlere açıp, ekosisteme olabildiğince erken dahil olmaları. Bu aşamada yönergenin öngördüğü verilere access sağlamaları yeterli 
2. Bir sonraki aşama, daha gelişkin bir API ile PISP'lere gelir karşılığı daha fazla veri ve insight sağlayabilecek bir monetization modeli kurmaları, örneğin demografik veriler, kimlik belgeleri ya da ödeme talimat bilgileri. Yani veriye erişimi modüler ve premium hale getirmek.
3. Bu adım, bankaların  PISP ve AISP aktörlerinin işlevlerini adapte etmesini öngörüyor, yani kendi PISP ve AISP uygulamlarını kurmasını. Böylece son kullanıcıya verilebilecek veri insightları, tavsiyeler vs ile müşteri ile bağını koparmayarak veri birikimini elinde tutmaya devam etmesi.
4. Son adımda ekosistemin genişletilmesi, yani daha fazla sektöre yönelik insight/tavsiye verilmesi. Böylece hem gelirin hem de veri birikiminin arttırılması öngörülmekte. 




