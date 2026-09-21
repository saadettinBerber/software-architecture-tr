# Fundamentals of Software Architecture - Terim Sözlüğü (Glossary)

Bu dosya çeviri boyunca tutarlılık sağlamak için kullanılır.
Her yeni sayfa çevrildikten sonra, o sayfada geçen yeni teknik terimler buraya eklenir
(`finalize_page.py` bunu `glossary_new` listesinden otomatik yapar; alfabetik sıra korunur).
Çeviriye başlamadan önce bu dosya okunmalı ve mevcut terimler aynen kullanılmalıdır.

## Terimler

| İngilizce Terim | Türkçe Karşılığı | Açıklama/Not |
|----------------|-----------------|-------------|
| -ilities | -ility'ler | Mimari özellik adlarının yaygın son eki (scalability → ölçeklenebilirlik, availability → kullanılabilirlik). |
| abstractness | soyutluk | Soyut öğelerin (soyut sınıflar, arayüzler) somut öğelere oranı; Robert Martin'in A ölçütü. |
| accidental complexity | tesadüfi karmaşıklık | Mimari/tasarım tercihlerinden kaynaklanan, gereksiz karmaşıklık; Bölüm 9'da ele alınır |
| Advanced Message Queuing Protocol (AMQP) | Gelişmiş Mesaj Kuyruğu Protokolü (AMQP) | Mesaj kuyruğu standartlarından; AMQP kısaltması korunur. |
| afferent coupling | giren bağlılık | Bir kod öğesine (bileşen, sınıf, fonksiyon vb.) gelen bağlantıların sayısı; Robert Martin'in Ca (fan-in) ölçütü. |
| Agile | Agile | Yerleşmiş terim; bu hâliyle kullanılır. |
| agility | çeviklik | Değişime hızlı yanıt verebilme yeteneği. |
| aleatory contracts | aleatorik sözleşmeler | finansal terim; örnek olarak verilir |
| anti-pattern | ters desen | Kötü veya zararlı bir çözümü tekrarlayan, yaygın yazılım tasarım deseni; 'Frozen Caveman Anti-Pattern' adlandırmasında olduğu gibi. |
| application server | uygulama sunucusu | Uygulamaları çalıştıran ve yöneten sunucu yazılımı |
| application silos | uygulama siloları | her uygulama veri tabanına yalnızca sahibi olan uygulamanın erişebildiği mimari yapı |
| architect | mimar | Yazılım mimarisiyle ilgilenen kişi |
| architectural characteristic | mimari özellik | Performans, kullanılabilirlik, ölçeklenebilirlik gibi sistem başarı ölçütleri. |
| architectural characteristics | mimari özellikler | Mimariyle belirlenen ölçeklenebilirlik, dayanıklılık gibi özellikler. |
| architectural concerns | mimari kaygılar | İş etkenlerinin sistemin mimarisine yansıyan karşılıkları. |
| architectural governance | mimari yönetişim | Mimari özelliklerin yönetilmesi ve denetlenmesi. |
| architectural quantum | mimari kuantum | Bağımsız dağıtılabilir ve ölçeklenebilir en küçük mimari birim; sayfa 92'de ele alınır. |
| architectural style | mimari stil | Çoğulu: mimari stiller. |
| architectural thinking | mimari düşünme | Şeyleri mimari bir gözle ya da mimari bir bakış açısıyla görme; Bölüm 2'nin adı ve ana kavramı. |
| architecture characteristics | mimari özellikler | Kitapta “-ilities” olarak da anılır: scalability, availability, elasticity vb. |
| architecture decision | mimari karar | Bir sistemin nasıl inşa edileceğine dair kural; rehber değil, kısıt. |
| Architecture Decision Record (ADR) | mimari karar kaydı | Mimari kararı kaydeden belge; ADR kısaltması korunur |
| architecture decisions | mimari kararlar | Sistemin yapısını ve davranışını önemli ölçüde etkileyen; gerekçesiyle birlikte kaydedilmesi gereken seçimler. |
| architecture patterns | mimari desenler | sorun alanına uygun mimari desen ve stillerin seçilmesi bağlamında; design patterns (tasarım desenleri) ile ilişkili. |
| architecture review board (ARB) | mimari inceleme kurulu | mimari kararlara sapma taleplerini inceleyip onaylayan veya reddeden kurul |
| architecture style | mimari stil | Mikro hizmetler, katmanlı, mikro çekirdek gibi sistemin uygulandığı stil |
| architecture vitality | mimari canlılığı | Yıllar önce tanımlanan bir mimarinin bugün ne kadar uygulanabilir olduğunun değerlendirmesi. |
| artifact | çıktı (artifact) | Çalışma sonucu üretilen kayıt/eser; burada mimari diyagramlar. |
| asynchronous messaging | asenkron mesajlaşma | servisler arası iletişimde yanıt beklemeden mesaj gönderme |
| auction system | açık artırma sistemi | Kitabın ödünleşim örneğindeki gibi, eşyaların açık artırmayla satıldığı sistem. |
| auto-scaling | otomatik ölçekleme | Kaynakların ihtiyaca göre otomatik artırılıp azaltılması. |
| automation | otomasyon | Araç ve betiklerle tekrarlayan işlerin otomatikleştirilmesi. |
| availability | kullanılabilirlik | Bir mimari özellik (“-ility”) |
| average directional index | ortalama yönlü endeks | finansal terim; piyasa trend ölçüsü |
| axiom | aksiyom | Doğru kabul edilen temel önerme |
| backward compatibility | geriye dönük uyumluluk | Yeni bir özelliğin ya da dilin, eski kod ve alışkanlıklarla uyumlu kalma gereği. |
| behavioral anti-pattern | davranışsal ters desen | Kod veya tasarım yerine insan davranışıyla ilgili ters desen; sayfa 30'da Donmuş Mağara Adamı Ters Deseni bunun örneğidir. |
| bidder | teklif veren | açık artırma (auction) örneği bağlamında; teklif sahibi |
| bidding data | teklif verileri | Açık artırma sistemindeki tekliflere ilişkin veriler. |
| bidirectional communication | çift yönlü iletişim | mimar ile geliştirme ekipleri arasında kararların iki yönde aktığı iletişim biçimi. |
| Big Design Up Front | Önden Büyük Tasarım | BDUF kısaltmasıyla da bilinir. |
| blueprint | mavi baskı (blueprint) | Sistemin yapısını gösteren plan şeması |
| bottleneck trap | darboğaz tuzağı | Mimarın projenin kritik yolundaki kodun sahipliğini alması ve ekibin ilerlemesini bloklaması durumu. |
| business domain | iş alanı | business domain expertise bağlamında |
| business domain knowledge | iş alanı bilgisi | mimarların iş alanını anlaması; 'have business domain knowledge' beklentisi |
| business drivers | iş etkenleri | Mimari kaygılara dönüşen iş tarafındaki itici güçler (kayıp sipariş istememe, hız, maliyet gibi). |
| business layer | iş katmanı | Katmanlı mimaride iş mantığını barındıran katman |
| business stakeholder | iş paydaşı | İş tarafındaki ilgili taraflar |
| C-level executives | üst düzey yöneticiler | CEO, CFO, CTO gibi unvanlar |
| caching | önbellekleme | caching product bağlamında |
| call graph | çağrı çizgesi | Yöntem çağrılarını ve dönüşlerini düğümler ve kenarlar olarak gösteren çizge. |
| career path | kariyer yolu |  |
| change control | değişiklik kontrolü | değişikliklerin izlenmesi ve onaylanması süreci |
| chaos engineering | kaos mühendisliği | Sistemin dayanıklılığını bilinçli arıza enjekte ederek test etme yöntemi. |
| characteristics | özellikler | Kitapta architectural characteristics → mimari özellikler anlamında. |
| checklist | kontrol listesi | Tamamlanması gereken adımların listesi; otomatik kontrol listeleri bağlamında. |
| chief architect | baş mimar | ARB yoksa sapma taleplerini değerlendiren kişi |
| class diagram | sınıf diyagramı | her bileşen için oluşturulan, sınıfları ve ilişkilerini gösteren diyagram. |
| class loader | sınıf yükleyici | Java'da sınıfları classpath üzerinden belleğe yükleyen mekanizma. |
| classpath | classpath | Java'da sınıf ve kaynakların arandığı dizin/JAR yolu; yerleşik terim, olduğu gibi kullanılır. |
| coaching | koçluk | mimarın geliştiricilere yönelik birebir yönlendirmesi. |
| code base | kod tabanı |  |
| code review | kod incelemesi | Bir geliştiricinin yazdığı kodun başka bir kişi tarafından gözden geçirilmesi; çoğulu kod incelemeleri. |
| cohesion | bütünlük | Modülün parçalarının aynı modülde tutulma derecesi; coupling (bağlılık) ile birlikte kullanılır. |
| cohesiveness | bütünlük | Bir modülün uyum (cohesion) derecesi; cohesive (uyumlu) sıfatı da bu sayfada geçer. |
| coincidental cohesion | tesadüfi bütünlük | Öğelerin yalnızca aynı kaynak dosyada bulunması nedeniyle ilişkili sayıldığı, uyumun en olumsuz biçimi. |
| collaboration | iş birliği | mimar ile geliştirme ekibi arasındaki yakın çalışma |
| comfort zone | konfor alanı | beceri/sorumluluk bağlamında |
| communication protocol | iletişim protokolü | servisler arası iletişimde kullanılan protokol (REST, gRPC gibi) |
| communicational cohesion | iletişimsel bütünlük | İki modülün, her birinin aynı bilgi üzerinde işlem yaptığı bir iletişim zinciri oluşturduğu bütünlük düzeyi. |
| compliance | uyum | mimari kararlara uygun davranma; 'ensure compliance with decisions' beklentisi |
| component | bileşen | Çoğulu: bileşenler. |
| connascence | eşdoğuş (connascence) | İki bileşenin, birindeki değişiklik diğerinde de değişikliği zorunlu kılıyorsa eşdoğuşlu olduğu söylenir; Bölüm 3'te (Modülerlik) ayrıntılı ele alınır. |
| constraint | kısıt | Sistemi ve geliştirme ekiplerini sınırlayan mimari karar ya da kural |
| consumer | tüketici | Mesajlaşmada mesajı alan taraf. |
| continuous delivery | sürekli teslim | Yazılımın her an yayınlanabilir durumda tutulduğu uygulama. |
| continuous integration | sürekli entegrasyon | Her değişikliğin push edildiği anda derlenip test edildiği uygulama. |
| contract | sözleşme | Mesajlaşmada üzerinde anlaşılan mesaj yapısı/biçimi. |
| corollary | vargı | Bir yasadan çıkarılan doğal sonuç (Corollary 1 → Vargı 1). |
| coupling | bağlılık | Bileşenlerin birbirine bağımlılık derecesi |
| coupling metrics | bağlılık ölçütleri | Bileşenler arası bağımlılık derecesini ölçen ölçütler; sayfa 44'te ayrıntılı ele alınır. |
| critical path | kritik yol | Proje yönetiminde, bir projenin tamamlanma süresini belirleyen görevler dizisi; burada mimarinin darboğazı olabilecek kod bağlamında kullanılır. |
| CRM | müşteri ilişkileri yönetimi (CRM) | customer relationship management kısaltması |
| customer relationship management | müşteri ilişkileri yönetimi | CRM olarak da bilinir |
| cyclomatic complexity | döngüsel karmaşıklık | kod karmaşıklığını ölçen metrik |
| data architecture | veri mimarisi | Verinin nasıl saklanacağını ve erişileceğini düzenleyen mimari yaklaşım. |
| data center | veri merkezi | Sunucu ve ağ altyapısının barındırıldığı tesis |
| database schema | veri tabanı şeması |  |
| database server | veritabanı sunucusu | Veritabanı yönetimini barındıran sunucu |
| decoupled | gevşek bağlı | coupling (bağlılık) karşıtı; topic yaklaşımının üreticiyi tüketicilerden ayırması bağlamında |
| decoupling | bağlılığın kırılması (decoupling) | coupling (bağlılık) teriminin karşıtı. |
| defensive design | savunmacı tasarım | Bir kısıtlama veya en kötü senaryo etrafında yapılan korumacı tasarım. |
| deployment | dağıtım | Yazılımın çalıştırma ortamına yüklenmesi. |
| derived metric | türetilmiş ölçüt | Ham bağlılık değerinden türetilen ölçüt; soyutluk, kararsızlık ve ana diziden uzaklık gibi. |
| design pattern | tasarım deseni | Yinelenen tasarım sorunlarına kanıtlanmış çözüm kalıpları |
| design principle | tasarım ilkesi | katı kural yerine yol gösteren ilke |
| design principles | tasarım ilkeleri | Günlük kodlama ve geliştirme kararlarını yönlendiren rehber ilkeler (ör. Tek Sorumluluk İlkesi). |
| DevOps | DevOps | Yerleşmiş terim; bu hâliyle kullanılır. |
| directory | dizin | Dosya sisteminde dosyaları gruplayan yapı; klasör. |
| domain | alan (domain) | Problem alanı bağlamında. |
| don't repeat yourself (DRY) | kendini tekrar etme (DRY) | Kod tekrarını önleyen tasarım ilkesi |
| ecosystem | ekosistem | Birbirini etkileyen teknoloji, araç ve uygulamaların bütünü |
| efferent coupling | çıkan bağlılık | Bir kod öğesinden diğer kod öğelerine giden bağlantıların sayısı; Robert Martin'in Ce (fan-out) ölçütü. |
| elastic scale | esnek ölçekleme | İhtiyaca göre kaynak örneklerini artırıp azaltma yeteneği |
| elasticity | esneklik | Kaynakların talebe göre otomatik artırılıp azaltılabilmesi yeteneği (elastic scale) |
| encapsulation | kapsülleme | Veriyi ve davranışı bir birim içinde saklayıp dışarıya kontrollü erişim sunma; kapsüllemek (encapsulate) eylemi de bu sayfada geçer. |
| engineering discipline | mühendislik disiplini |  |
| engineering practices | mühendislik uygulamaları | Süreçten bağımsız, kanıtlanmış ve tekrarlanabilir fayda sağlayan uygulamalar. |
| enterprise | kuruluş | işletme/şirket bağlamında |
| enterprise service bus (ESB) | kurumsal servis veri yolu (ESB) | Servisler arası entegrasyonu ve mesajlaşmayı sağlayan merkezi bileşen. |
| entropy | entropi | Fizikten ödünç alınan, sistemlerin düzensizliğe yönelme eğilimi. |
| estimation | tahmin | Proje tahmini bağlamında. |
| evolutionary architecture | evrimsel mimari | Zamanla değişime uyum sağlayan mimari. |
| evolutionary computing | evrimsel hesaplama | Doğal evrim süreçlerinden esinlenen hesaplama alanı. |
| exchange | exchange | AMQP'de üreticinin mesaj gönderdiği bileşen; yerleşik terim, olduğu gibi kullanılır. |
| expertise | uzmanlık | Bir konudaki derin bilgi ve beceri; piramidin tepesindeki bilgi düzeyi. |
| extensibility | genişletilebilirlik | architectural extensibility (mimari genişletilebilirlik) bağlamında |
| external data storage | harici veri depolama | Uygulama dışında barındırılan veri deposu (veritabanı vb.). |
| Extreme Programming (XP) | Extreme Programming (XP) | Yerleşmiş terim; Türkçe karşılığı yaygın değildir, İngilizce hâliyle kullanılır. |
| facilitation | kolaylaştırıcılık | toplantı/çalışma yürütme becerisi |
| fan-in | fan-in (gelen bağlantı sayısı) | Bir modüle giren bağlantıların sayısı; afferent coupling ile ilişkilidir. |
| fan-out | fan-out (giden bağlantı sayısı) | Bir modülden çıkan bağlantıların sayısı; efferent coupling ile ilişkilidir. |
| fault tolerance | hata toleransı | Sistemin bileşen arızalarına rağmen çalışmaya devam edebilme yeteneği. |
| feature toggles | özellik anahtarları | Davranışı kod değişikliği olmadan açıp kapatmayı sağlayan bayraklar |
| feedback loop | geri bildirim döngüsü | Kararların sonucunun hızla değerlendirilmesini sağlayan döngü; Çevik yaklaşımın temel avantajı |
| field | alan | Sınıf düzeyinde tanımlanan değişken; örnek alanı (instance field). |
| First Law of Software Architecture | Yazılım Mimarisi Birinci Yasası | “Yazılım mimarisindeki her şey bir ödünleşimdir.” |
| fitness function | uygunluk fonksiyonu | bir mimari özelliği ölçen otomatik denetim; Bölüm 6'da ayrıntılı ele alınır |
| framework | çerçeve |  |
| friction | sürtünme | Uyumsuz süreç veya araçların yarattığı direnç. |
| frontend | ön uç | Kullanıcıya görünen taraf; frontend. |
| Frozen Caveman Anti-Pattern | Donmuş Mağara Adamı Anti-Deseni | Mimarın her mimaride en sevdiği mantıksız endişeye geri dönmesini anlatan davranış anti-deseni; sayfa 30'da ele alınır. |
| fully qualified name | tam nitelikli ad | Bir öğeyi benzersiz biçimde tanımlayan, paket/alan adı zincirini içeren tam ad. |
| functional cohesion | işlevsel bütünlük | En yüksek bütünlük düzeyi; modülün tüm parçaları birbiriyle ilişkilidir. |
| functional language | fonksiyonel dil | Hesaplamanın fonksiyonlar aracılığıyla yapıldığı programlama dili. |
| functionality | işlevsellik | Sistemin gerçekleştirdiği işlevler; mimari karakteristiklerden bağımsızdır |
| genetic algorithm | genetik algoritma | Çözümü mutasyon ve seçimle evrimleştirerek optimize eden algoritma. |
| graph theory | çizge kuramı | Çizge (graf) yapılarını inceleyen matematik dalı. |
| guideline | kılavuz ilke | yol gösteren ama dayatmayan ilke; karşılığı kılavuz/rehber |
| hands-on | uygulamalı | hands-on knowledge bağlamında |
| hard-and-fast rule | katı ve kesin kural | istisnası olmayan, koşulsuz uygulanan kural |
| heterogeneous | heterojen | farklı teknolojilerden oluşan ortam |
| heterogeneous contracts | heterojen sözleşmeler | Birbirinden farklı yapıdaki mesaj sözleşmeleri. |
| historical relevance | tarihsel önem | Yalnızca geçmiş bağlamında anlamlı olma durumu |
| incidental coupling | tesadüfi bağlılık | Birbirinden bağımsız yöntemlerin hiçbir ortak alanı paylaşmadan aynı sınıfta toplanması durumu; LCOM ölçütünün sınıflar içinde ortaya çıkardığı bağlılık. |
| incidentally coupled | tesadüfen bağlanmış | Aralarında gerçek bir ilişki olmamasına rağmen tek bir sınıfta toplanmış; yüksek LCOM ile tespit edilir. |
| incremental change | artımlı değişiklik | Küçük adımlarla, düşük maliyetle yapılan değişiklik |
| infrastructure | altyapı | Sistemin üzerinde çalıştığı donanım ve ağ hizmetleri. |
| instability | kararsızlık | Robert Martin'in I ölçütü; çıkan bağlılığın toplam bağlılığa oranı. |
| integrity assessment | bütünlük değerlendirmesi | Bir özelliğin veya parçanın durumunun nesnel olarak ölçülüp değerlendirilmesi. |
| interpersonal skills | kişilerarası beceriler | mimarlardan beklenen iletişim ve iş birliği becerileri; 'possess interpersonal skills' beklentisi |
| iteration | yineleme | bir projenin tekrarlanan geliştirme çevrimi |
| iterative | yinelemeli |  |
| iterative development | yinelemeli geliştirme | Küçük ve tekrarlı adımlarla ilerleyen geliştirme biçimi |
| iterative process | yinelemeli süreç | Her adımda geri bildirim alarak art arda ilerleyen süreç. |
| knowledge pyramid | bilgi piramidi | bilgiyi; bilinen, bilinmediği bilinen ve bilinmediği bilinmeyen olarak ayıran model; Şekil 2-3 |
| knowledge triangle | bilgi üçgeni | bilgiyi üç bölüme ayıran kavram; sayfada knowledge pyramid (bilgi piramidi) ile aynı anlamda kullanılır |
| known knowns | bilinen bilinenler | Rumsfeld'ın bilgi modelindeki terim. |
| known unknowns | bilinen bilinmeyenler |  |
| lack of cohesion in methods | yöntemlerde bütünlük eksikliği | LCOM metriklerinin ölçtüğü durum. |
| latest trends | güncel trendler | teknoloji ve sektör trendlerini takip etme; 'keep current with latest trends' beklentisi |
| Laws of Software Architecture | Yazılım Mimarisi Yasaları | Bölüm 1'in kesit başlığı ve sayfa 19'un koşu başlığı. |
| layered | katmanlı | Katmanlı mimari stili |
| layered architecture | katmanlı mimari | Katmanlar halinde düzenlenmiş mimari stili |
| LCOM metric | LCOM ölçütü | yöntemlerde bütünlük eksikliği (lack of cohesion in methods) ölçütü. |
| library | kütüphane | Yeniden kullanılabilir kod koleksiyonu; framework'ten (çerçeve) daha az yapılandırılmıştır. |
| lint test | lint testi | Kodda olası hataları ve biçim sorunlarını denetleyen test; lint terimi korunur. |
| load balancing | yük dengeleme | İş yükünün tüketiciler arasında dağıtılması. |
| logical cohesion | mantıksal bütünlük | Modüldeki verinin işlevsel değil mantıksal olarak ilişkili olduğu uyum türü; örn. StringUtils gibi aynı tür veri üzerinde çalışan ilişkisiz statik yöntemler. |
| loose coupling | gevşek bağlılık | Bileşenler arası bağımlılığın az olması |
| machine provisioning | makine sağlama | Sunucu ve kaynakların otomatik olarak hazırlanması. |
| main sequence | ana dizi | Soyutluk–kararsızlık grafiğinde A+I=1 doğrusu; bu doğrudan uzaklık (distance from the main sequence) ile ölçülür. |
| mentoring | rehberlik | mimarın geliştiricilere yol göstermesi; coaching (koçluk) ile birlikte anılır. |
| messaging model | mesajlaşma modeli | yayınla-abone ol ve noktadan noktaya dahil mesajlaşma biçimleri |
| metaobject protocol | meta nesne protokolü (metaobject protocol) | Geliştiricilere ek genişletme mekanizmaları sağlayan programlama yapısı. |
| metrics | ölçütler | Ölçülebilir performans ve değer göstergeleri. |
| metrics suite | ölçüt takımı | Bir arada sunulan, birbiriyle ilişkili ölçütler dizisi; Chidamber ve Kemerer takımı gibi. |
| microkernel | mikro çekirdek | Bir mimari stil türü |
| microservice | mikroservis | Çoğulu: mikroservisler. |
| microservices | mikroservisler | Küçük, bağımsız dağıtılabilir servislerden oluşan mimari stil |
| microservices architecture | mikroservis mimarisi | mimari stil türü; servisler arası asenkron mesajlaşma örneği verilir |
| mindmap | zihin haritası |  |
| mixed cohesion | karma bütünlük | Bir sınıfın yöntem kümelerinin bazı alan gruplarını paylaşıp bazılarını paylaşmadığı ara bütünlük durumu; Şekil 3-1'deki Class Z örneği. |
| mnemonic | anımsatıcı | Bilgiyi hatırlamaya yardımcı olan sözcük ya da ipucu; burada afferent/efferent ayrımı için geliştirilen ipuçları. |
| modular programming | modüler programlama | Kodu modül adı verilen bağımsız birimlerde gruplayan programlama yaklaşımı; Modula ve Ada gibi dillerde görülür. |
| modular reuse | modüler yeniden kullanım | Modülleri bağımsız birimler olarak başka bağlamlarda yeniden kullanma. |
| modularity | modülerlik |  |
| module | modül | İlgili kodun mantıksal olarak gruplandığı birim; nesne yönelimli dillerde sınıf grubu, yapısal veya fonksiyonel dillerde fonksiyon grubu olabilir. |
| monitoring | izleme | Sistemin durumunu ölçüp gözlemleme eylemi; monitors (izleyiciler) ile ilişkilidir. |
| monitors | izleyiciler | Sistemin durumunu sürekli izleyen araçlar. |
| monolithic architecture | monolitik mimari | Tüm bileşenlerin tek bir dağıtılabilir birimde toplandığı mimari |
| moving target | hareketli hedef | Sürekli değişen, sabitlenemeyen konu ya da durum |
| name conflict | ad çakışması | Aynı kapsamda aynı ada sahip iki öğenin çakışması; Java 1.0 tasarımının önlemeye çalıştığı sorun. |
| namespace | ad alanı (namespace) | .NET gibi dillerde ilgili kodun gruplandığı modülerlik mekanizması. |
| negotiation | müzakere |  |
| negotiation skills | müzakere becerileri | Mimarların kararları onaylatmak için kullandığı beceriler |
| nomenclature | adlandırma | Bir alana özgü terimler bütünü. |
| nonpriority debt | imtiyazsız borç | finansal terim; junior debt olarak da bilinir |
| object-oriented | nesne yönelimli | Nesneleri ve kapsüllemeyi temel alan programlama paradigması (OOP). |
| object-oriented language | nesne yönelimli dil | Kodun sınıflar ve nesneler etrafında düzenlendiği programlama dili. |
| office politics | ofis politikaları | kurum içi güç ve çıkar dinamikleri |
| open source | açık kaynak | Kaynak kodu serbestçe kullanılabilen ve değiştirilebilen yazılım modeli |
| operating system | işletim sistemi | Donanım ile uygulamalar arasında arayüz sağlayan temel yazılım |
| operational awareness | operasyonel farkındalık | Sistemin işleyiş ve işletim boyutunu görme yetisi |
| operational concerns | operasyonel kaygılar | Ölçek, performans, esneklik gibi operasyonla ilgili mimari kaygılar |
| operations group | operasyon grubu | Sistemin işletilmesinden sorumlu ekip. |
| organizing principle | düzenleme ilkesi | Bir sistemin parçalarını düzenleyen temel ilke. |
| orthogonal | ortogonal (bağımsız) | İşlevsellikle ilişkisiz, birbirinden bağımsız |
| outsourcing | dış kaynak kullanımı | Operasyon gibi işlevlerin maliyet tasarrufu amacıyla başka bir şirkete/ekibe devredilmesi |
| package | paket | Java gibi dillerde ilgili sınıfların gruplandığı modülerlik mekanizması; dil anahtar sözcüğü olarak package korunur. |
| page load time | sayfa yükleme süresi | Bir sayfanın yüklenmesi için geçen süre; performans ölçütü. |
| paradigm | paradigma | Programlamada benimsenen model ya da yaklaşım; programlama paradigması bağlamında. |
| pattern | desen | Tasarım desenleri bağlamında; çoğulu: desenler. |
| perceived technical risk | algılanan teknik risk | Gerçekte var olup olmadığına bakılmaksızın mimarların hissettiği/algıladığı teknik risk; sayfa 30'da gerçek teknik riskle karşılaştırılır. |
| point-to-point messaging | noktadan noktaya mesajlaşma | Her mesajın tam olarak bir tüketici tarafından işlendiği mesajlaşma modeli. |
| presentation layer | sunum katmanı | Kullanıcı arayüzü sorumluluğunu taşıyan katman |
| problem domain | sorun alanı | çözülmek istenen iş sorununun yer aldığı alan |
| problem space | problem alanı |  |
| procedural cohesion | süreçsel bütünlük | İki modülün kodu belirli bir sırayla çalıştırması gerektiği uyum türü. |
| process-agnostic | süreçten bağımsız | Belirli bir sürece bağlı olmayan. |
| producer | üretici | Mesajlaşmada mesajı gönderen taraf. |
| product owner | ürün sahibi | Ürün gereksinimlerinden ve önceliklerden sorumlu paydaş |
| production-quality code | üretim kalitesinde kod | Üretim ortamına girebilecek kalitede yazılan kod. |
| programmatic load balancing | programatik yük dengeleme | Kod aracılığıyla yapılan yük dengeleme. |
| project manager | proje yöneticisi | Proje planlaması ve yürütmesinden sorumlu kişi |
| proof-of-concept (POC) | kavram kanıtı (POC) | Bir mimari kararı doğrulamak için geliştirilen çalışan örnek; POC kısaltması korunur. |
| publish-and-subscribe | yayınla-abone ol | Üreticinin bir konuya (topic) yayınladığı mesajı tüm abonelerin aldığı mesajlaşma modeli. |
| queue | kuyruk | Mesajlaşmada, bir mesajı tek bir tüketiciye ulaştıran sıra; point-to-point modelin temel öğesi. |
| rates rally | oran rallisi | finansal terim; faiz oranlarındaki yükseliş |
| reactive-based framework | tepkisel tabanlı çerçeve | Angular, Elm, React.js, Vue gibi ön uç web çerçeveleri. |
| readability | okunabilirlik | Kodun okunma ve anlaşılma kolaylığı. |
| refactoring | refaktoring (yeniden düzenleme) | Davranışı değiştirmeden kodun iç yapısını iyileştirme. |
| reference architecture | referans mimari | Başkalarının izleyebileceği, örnek alınan mimari. |
| release | sürüm | Yazılımın kullanıcılara yayınlanması. |
| release environment | sürüm ortamı | Sürümün hazırlandığı, doğrulandığı ve yayınlandığı ortam. |
| remote access protocol | uzaktan erişim protokolü | REST, SOAP gibi uzak servis çağrılarında kullanılan protokol |
| requirements | gereksinimler | Sistemin karşılaması gereken işlevsel ihtiyaçlar. |
| resilient architecture | dayanıklı mimari | Değişime ve arızalara karşı dirençli mimari. |
| responsibility | sorumluluk | Mimarın rol kapsamı bağlamında. |
| restructuring | yeniden yapılandırma | Mimarinin bir desenden diğerine taşınması/değiştirilmesi |
| reuse mechanism | yeniden kullanım mekanizması | Kodun farklı yerlerde tekrar kullanılmasını sağlayan platform yeteneği. |
| roadmap | yol haritası | Bir sistemi geliştirme sürecini gösteren plan |
| rogue service | başıboş servis | Kurallar dışına çıkan, izinsiz davranan servis. |
| scalability | ölçeklenebilirlik | Bir mimari özellik (“-ility”) |
| scope (scoping) | kapsam (scoping) | Bir tanımlayıcının görülebildiği ve erişilebildiği bölge; kapsam kuralları. |
| scoping rules | kapsam kuralları | Bir adın hangi bağlamlarda görünür ve erişilebilir olduğunu belirleyen kurallar. |
| Second Law of Software Architecture | Yazılım Mimarisi İkinci Yasası | “Neden, nasıl’dan daha önemlidir.” |
| security breach | güvenlik ihlali | Güvenliğin ihlal edildiği olay/olay örüntüsü. |
| sequential cohesion | sıralı bütünlük | Bir modülün çıktısının diğerinin girdisi olduğu bütünlük düzeyi. |
| service-level agreement (SLA) | hizmet düzeyi anlaşması (SLA) | Çalışma süresi, ölçek, yanıt verebilirlik gibi hizmet ölçütlerini tanımlayan sözleşme |
| service-oriented architecture (SOA) | servis odaklı mimari | İşlevleri bağımsız servisler olarak düzenleyen mimari yaklaşım. |
| services layer | hizmet katmanı | Katmanlı mimaride hizmetleri barındıran katman |
| shared resources | paylaşılan kaynaklar | Birden çok uygulamanın birlikte kullandığı altyapı kaynakları |
| shared utility classes | paylaşılan yardımcı sınıflar | Mimari değişiminde sıkıntı yaratan, birden çok sınıfın ortak kullandığı yardımcı sınıflar. |
| side effect | yan etki | Bir işlemin öngörülmeyen ya da istenmeyen sonucu |
| single responsibility | tek sorumluluk | Her bileşenin tek bir sorumluluğu olması ilkesi |
| single source of truth | tek doğruluk kaynağı |  |
| soft skills | sosyal beceriler | İletişim, iş birliği gibi teknik olmayan beceriler |
| software architect | yazılım mimarı | Meslek/rol adı. |
| software architecture | yazılım mimarisi | Disiplin adı; kitabın ana konusu. |
| software asset | yazılım varlığı | Bileşen, sınıf gibi yeniden kullanılabilir yazılım öğesi. |
| software development ecosystem | yazılım geliştirme ekosistemi | Sektörü etkileyen topluluk, araç ve trendler bütünü. |
| source validator | kaynak doğrulayıcı | Kaynak kodu belirli kodlama kurallarına göre otomatik denetleyen araç. |
| Space-Based Architecture | Alan Tabanlı Mimari | Bölüm 15'te ele alınan, yüksek ölçek için veriyi dağıtan mimari stili. |
| stakeholders | paydaşlar |  |
| stale expertise | bayat uzmanlık | Güncelliğini yitirmiş bilginin hâlâ en ileri düzey olduğu yanılgısı; uzmanlığın sürdürülmemesi sonucu oluşur. |
| static initializer | statik başlatıcı | Java'da sınıf yüklenirken bir kez çalışan, statik alanları başlatan kod bloğu. |
| Strangler Pattern | Strangler Deseni | Eski sistemi aynı arayüzün arkasında parça parça değiştirerek yeni mimariye geçme deseni |
| strategy pattern | strateji deseni | GoF tasarım deseni |
| structural change | yapısal değişiklik | Sistemin yapısını ilgilendiren değişiklik |
| structural cohesion | yapısal bütünlük | Bir modülün yapısının (ör. alan erişimi) ölçülebilen bütünlüğü; LCOM gibi yapısal ölçütlerle belirlenir. |
| structural decay | yapısal çürüme | Geliştiricilerin kodlama/tasarım değişiklikleri sonucu mimari özelliklerin bozulması. |
| structural metric | yapısal ölçüt | Kodun yapısını (alan erişimi, bağımlılıklar gibi) kaynak düzeyinde ölçen ölçüt. |
| structural soundness | yapısal sağlamlık | Sistemin yapısının sağlam ve tutarlı olma durumu; tesadüfen oluşmaz, sürekli enerji gerektirir. |
| structure | yapı | Sistemin mimari stil türüyle ilgili yapısı |
| structure of the system | sistemin yapısı | Mimarinin en görünür parçası; mimari stili ve bileşen düzenini kapsar. |
| structured programming | yapısal programlama | Pascal ve C ile örneklenen, GOTO gibi kontrolsüz sıçramaları reddeden programlama anlayışı. |
| stuff you know you don’t know | bildiğini bilmediğin şeyler | Varlığından haberdar olunan ama uzmanlık gerektiren bilgi düzeyi; known unknowns (bilinen bilinmeyenler) ile ilişkilidir. |
| success criteria | başarı kriterleri | Sistemin başarılı sayılması için karşılanması gereken ölçütler |
| symbiotic relationship | simbiyotik ilişki | Birbirini tamamlayan ve destekleyen karşılıklı ilişki. |
| teamwork | takım çalışması |  |
| technical breadth | teknik genişlik |  |
| technical debt | teknik borç | Kısa vadeli ya da acele çözümlerin biriktirdiği, sonradan ödenmesi gereken kod/tasarım borcu. |
| technical depth | teknik derinlik |  |
| technical leader | teknik lider | Ekibin mühendislik kararlarını yönlendiren kişi. |
| technologist | teknoloji uzmanı | teknolojik bilgiyi kullanan, geliştirici veya mimar gibi teknik profesyonel |
| temporal cohesion | zamansal bütünlük | Modüllerin zamanlama bağımlılıklarına göre ilişkili olduğu uyum türü; örn. sistem başlangıcında başlatılan görünüşte alakasız görevler. |
| test-first development | önce test geliştirme | Kod yazılmadan önce testin yazıldığı geliştirme yaklaşımı. |
| testing environment | test ortamı | Değişikliklerin test edildiği ortam. |
| throwaway code | atılacak kod | Yalnızca hızlı doğrulama için yazılan, üretime girmesi amaçlanmayan kod. |
| tightly coupled | sıkı bağlı | Birbirinin iç yapısına bağımlı, birlikte değişmek zorunda kalan öğelerin durumu. |
| topic | topic | Yayınla-abone ol modelinde birden çok abonenin aynı mesajı aldığı kanal. |
| topology | topoloji | Sistem bileşenlerinin bağlantı ve dağılım yapısı. |
| trade-off | ödünleşim | Bir fayda için başka bir özellikten vazgeçme; metinde İngilizcesiyle de kullanılır |
| traveling salesperson problem | gezgin satıcı problemi | Çeşitli şehirler arasındaki en kısa rotayı bulmayı amaçlayan klasik optimizasyon problemi. |
| unit tests | birim testleri | Tek bir kod birimini izole biçimde doğrulayan testler. |
| unknown unknowns | bilinmeyen bilinmeyenler |  |
| uptime | çalışma süresi | Sistemin kullanılabilir olduğu süre oranı |
| user story | kullanıcı hikâyesi | Çevik geliştirmede, kullanıcı ihtiyacını kısa ve iş dilinde anlatan iş öğesi. |
| variance | sapma | bir standarda veya mimari karara incelenip onaylanan istisna/muafiyet |
| variance model | sapma modeli | sapma talep sürecini biçimlendiren kurumsal model |
| verification mechanism | doğrulama mekanizması | Bir özelliğin veya parçanın durumunu otomatik olarak doğrulayan mekanizma. |
| volatility | değişkenlik | Bir kod tabanının değişikliklerden etkilenme eğilimi; kararsızlık ölçütüyle belirlenir. |
| waterfall | şelale | şelale (waterfall) modeli; eski, sıralı yazılım geliştirme yaklaşımı |
| whitepaper | teknik rapor | Beyaz rapor; teknik belge türü. |
| wiretap | izinsiz dinleme | Gizlice dinleme; mesaj akışını izinsiz gözlemleme. |
| workflow | iş akışı | İşlerin yapılandırılmış akışı. |
| working knowledge | çalışma bilgisi | Bir konuyu pratikte kullanabilecek düzeyde bilme. |
