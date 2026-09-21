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
| accessibility | erişilebilirlik | Renk körlüğü veya işitme kaybı gibi engelleri olan kullanıcılar dahil tüm kullanıcılara erişim sağlama; yapısal mimari özellik. |
| accidental complexity | tesadüfi karmaşıklık | Mimari/tasarım tercihlerinden kaynaklanan, gereksiz karmaşıklık; Bölüm 9'da ele alınır |
| accountability | hesap verebilirlik | Bir kullanıcının eylemlerinin izlenebilmesi; güvenlik özelliği. |
| actor/actions approach | aktör/eylemler yaklaşımı | Mimarların aktörleri ve gerçekleştirebilecekleri eylemleri belirleyerek gereksinimleri bileşenlere eşlediği yöntem; Rational Unified Process kökenlidir. |
| adaptability | uyarlanabilirlik | Yazılımın farklı ya da değişen donanım, yazılım veya operasyonel ortamlara uyarlanabilme derecesi. |
| additional context | ek bağlam | Kata alıştırmasında, gereksinimlerde yer almayan ancak tasarımı etkileyen önemli değerlendirmeleri içeren bölüm. |
| address space | adres alanı | Bir sürecin erişebildiği, kendine özgü bellek bölgesi; servislerin kendi adres alanlarında çalışması bağlamında geçer. |
| Advanced Message Queuing Protocol (AMQP) | Gelişmiş Mesaj Kuyruğu Protokolü (AMQP) | Mesaj kuyruğu standartlarından; AMQP kısaltması korunur. |
| afferent coupling | giren bağlılık | Bir kod öğesine (bileşen, sınıf, fonksiyon vb.) gelen bağlantıların sayısı; Robert Martin'in Ca (fan-in) ölçütü. |
| after-the-fact quality assessment | iş sonrası kalite değerlendirmesi | quality attributes teriminin ima ettiği, yapım sonrası yapılan değerlendirme |
| Agile | Agile | Yerleşmiş terim; bu hâliyle kullanılır. |
| agility | çeviklik | Değişime hızlı yanıt verebilme yeteneği. |
| aleatory contracts | aleatorik sözleşmeler | finansal terim; örnek olarak verilir |
| algorithmically complex | algoritmik olarak karmaşık | Sorun alanının algoritma gerektiren yapısal karmaşıklığına işaret eder. |
| analyzability | analiz edilebilirlik | Yazılım hakkında somut ölçütler toplayabilme kolaylığı. |
| anti-pattern | ters desen | Kötü veya zararlı bir çözümü tekrarlayan, yaygın yazılım tasarım deseni; 'Frozen Caveman Anti-Pattern' adlandırmasında olduğu gibi. |
| anti-trollability | trolleme karşıtılık (anti-trollability) | "İtibar endeksi" ifadesinin akla getirdiği, uydurma bir mimari özellik adı; gerçek bir özellik olarak tasarlanmamalıdır. |
| application server | uygulama sunucusu | Uygulamaları çalıştıran ve yöneten sunucu yazılımı |
| application silos | uygulama siloları | her uygulama veri tabanına yalnızca sahibi olan uygulamanın erişebildiği mimari yapı |
| appropriateness recognizability | uygunluğun tanınabilirliği | Kullanıcının yazılımın ihtiyaçlarına uygun olup olmadığını fark edebilmesi; kullanışlılığın alt ölçütü. |
| architect | mimar | Yazılım mimarisiyle ilgilenen kişi |
| architectural characteristic | mimari özellik | Performans, kullanılabilirlik, ölçeklenebilirlik gibi sistem başarı ölçütleri. |
| architectural characteristics | mimari özellikler | Mimariyle belirlenen ölçeklenebilirlik, dayanıklılık gibi özellikler. |
| architectural concerns | mimari kaygılar | İş etkenlerinin sistemin mimarisine yansıyan karşılıkları. |
| architectural governance | mimari yönetişim | Mimari özelliklerin yönetilmesi ve denetlenmesi. |
| architectural principle | mimari ilke | Mimariye yön veren, uygunluk fonksiyonlarıyla ifade edilip otomatik doğrulanabilen temel ilke; sayfada önemli mimari ilkelerin uygunluk fonksiyonu olarak kodlanması bağlamında geçer. |
| architectural quantum | mimari kuantum | Bağımsız dağıtılabilir ve ölçeklenebilir en küçük mimari birim; sayfa 92'de ele alınır. |
| architectural style | mimari stil | Çoğulu: mimari stiller. |
| architectural thinking | mimari düşünme | Şeyleri mimari bir gözle ya da mimari bir bakış açısıyla görme; Bölüm 2'nin adı ve ana kavramı. |
| architecture characteristics | mimari özellikler | Kitapta “-ilities” olarak da anılır: scalability, availability, elasticity vb. |
| architecture decision | mimari karar | Bir sistemin nasıl inşa edileceğine dair kural; rehber değil, kısıt. |
| Architecture Decision Record (ADR) | mimari karar kaydı | Mimari kararı kaydeden belge; ADR kısaltması korunur |
| architecture decisions | mimari kararlar | Sistemin yapısını ve davranışını önemli ölçüde etkileyen; gerekçesiyle birlikte kaydedilmesi gereken seçimler. |
| architecture exposition cycle | mimari sunum döngüsü (architecture exposition cycle) | Bileşenlerin belirlenmesi ve iyileştirilmesinden oluşan genel döngü; sayfadaki 'generic architecture exposition cycle' ifadesinde geçer. |
| architecture kata | mimari kata | Ted Neward'ın, mimarların alan odaklı açıklamalardan mimari özellikler türetme pratiği yapması için tasarladığı alıştırma; çoğulu architecture katas (mimari katalar). |
| architecture partitioning | mimari bölümleme (architecture partitioning) | Mimarinin bileşenlere ayrılma biçimi; sayfada 'top-level partitioning' (üst düzey bölümleme) kavramıyla birlikte geçer. |
| architecture patterns | mimari desenler | sorun alanına uygun mimari desen ve stillerin seçilmesi bağlamında; design patterns (tasarım desenleri) ile ilişkili. |
| architecture review board (ARB) | mimari inceleme kurulu | mimari kararlara sapma taleplerini inceleyip onaylayan veya reddeden kurul |
| architecture style | mimari stil | Mikro hizmetler, katmanlı, mikro çekirdek gibi sistemin uygulandığı stil |
| architecture vitality | mimari canlılığı | Yıllar önce tanımlanan bir mimarinin bugün ne kadar uygulanabilir olduğunun değerlendirmesi. |
| archivability | arşivlenebilirlik | Verinin belirli bir süre sonra arşivlenme veya silinme gereksinimi; yapısal mimari özellik. |
| artifact | çıktı (artifact) | Çalışma sonucu üretilen kayıt/eser; burada mimari diyagramlar. |
| aspiring architect | mimar adayı | Mimarlığa heves eden, kariyerinin başındaki kişi; nascent architect (yeni yetişen mimar) ile ilişkilidir. |
| assertions | iddialar (assertions) | Testlerde beklenen davranışı doğrulayan kontrol ifadeleri; test edilebilirlik bağlamında geçer. |
| asynchronous call | asenkron çağrı | Çağıranın yanıt beklemediği, ateşle ve unut (fire-and-forget) semantiğine olanak tanıyan çağrı biçimi. |
| asynchronous connascence | asenkron eşdoğuş | Dinamik eşdoğuş türü; ateşle ve unut (fire-and-forget) semantiğiyle oluşur ve iki servisin operasyonel mimaride farklılaşmasına izin verir. |
| asynchronous messaging | asenkron mesajlaşma | servisler arası iletişimde yanıt beklemeden mesaj gönderme |
| auction system | açık artırma sistemi | Kitabın ödünleşim örneğindeki gibi, eşyaların açık artırmayla satıldığı sistem. |
| auctioneer | mezatçı (auctioneer) | Canlı açık artırmayı yürüten taraf; Going, Going, Gone katasında kuantum düzeyinde mimari özelliklerin kapsamlandığı ayrı bir örnek. |
| auditability | denetlenebilirlik | İşlem ve olayların izlenip denetlenebilmesi; bu sayfada gün sonu fon fiyatlamasının doğruluğu bağlamında geçer. |
| authentication | kimlik doğrulama | Kullanıcıların gerçekten kendileri olduklarını doğrulamaya yönelik güvenlik gereksinimi; yapısal mimari özellik. |
| authenticity | gerçeklik (authenticity) | Bir kullanıcının kimliğinin kanıtlanması; güvenlik özelliği. |
| authorization | yetkilendirme | Kullanıcıların uygulama içinde yalnızca belirli işlevlere erişebilmesini sağlayan güvenlik gereksinimi; yapısal mimari özellik. |
| auto-import | otomatik içe aktarma | IDE'lerin, başvurulan sınıfı otomatik olarak import eden özelliği; rastgele kullanımı döngüsel bağımlılıklara yol açabilir. |
| auto-scaling | otomatik ölçekleme | Kaynakların ihtiyaca göre otomatik artırılıp azaltılması. |
| automation | otomasyon | Araç ve betiklerle tekrarlayan işlerin otomatikleştirilmesi. |
| availability | kullanılabilirlik | Bir mimari özellik (“-ility”) |
| average directional index | ortalama yönlü endeks | finansal terim; piyasa trend ölçüsü |
| axiom | aksiyom | Doğru kabul edilen temel önerme |
| backend developer | arka uç geliştiricisi | Sunucu tarafı, servis ve veri katmanı üzerinde çalışan geliştirici; katmanlı mimaride aynı departmana yerleştirilen rol örneği. |
| backward compatibility | geriye dönük uyumluluk | Yeni bir özelliğin ya da dilin, eski kod ve alışkanlıklarla uyumlu kalma gereği. |
| baseline | taban çizgisi | Karşılaştırma ve sapma değerlendirmesi için zaman içinde ölçülerek oluşturulan referans değer (built-in ile karıştırılmamalıdır). |
| behavioral anti-pattern | davranışsal ters desen | Kod veya tasarım yerine insan davranışıyla ilgili ters desen; sayfa 30'da Donmuş Mağara Adamı Ters Deseni bunun örneğidir. |
| bidder | teklif veren | açık artırma (auction) örneği bağlamında; teklif sahibi |
| bidding data | teklif verileri | Açık artırma sistemindeki tekliflere ilişkin veriler. |
| bidirectional communication | çift yönlü iletişim | mimar ile geliştirme ekipleri arasında kararların iki yönde aktığı iletişim biçimi. |
| Big Ball of Mud | Büyük Çamur Topu (Big Ball of Mud) | Yapısız, birbirine sıkı bağlı kod yığınını anlatan ünlü ters desen (anti-pattern). |
| Big Design Up Front | Önden Büyük Tasarım | BDUF kısaltmasıyla da bilinir. |
| blueprint | mavi baskı (blueprint) | Sistemin yapısını gösteren plan şeması |
| bottleneck trap | darboğaz tuzağı | Mimarın projenin kritik yolundaki kodun sahipliğini alması ve ekibin ilerlemesini bloklaması durumu. |
| boundary conditions | sınır koşulları | Sistemin uç durumlarda (bağlantı kesilmesi, donanım arızası vb.) doğru davranmasını gerektiren koşullar; Tablo 4-1'deki sağlamlık tanımında geçer. |
| bounded context | sınırlı bağlam | Alan odaklı tasarımdan (domain-driven design) gelen; her mikroservisin kendi veritabanına sahip olmasını yönlendiren felsefe. Sayfa 94'teki 'Domain-Driven Design's Bounded Context' kesitinde ayrıntılı ele alınır. |
| brittleness | kırılganlık | Sistemin gereksiz yere kırılgan olması; isteğe bağlı bir bağımlılığın arızalanmasının tüm sistemi çökertme eğilimi. |
| brown-bag lunch | brown-bag öğle toplantısı | Katılımcıların kendi yemeklerini getirdiği, resmî olmayan öğle toplantısı; brown-bag terimi korunur. |
| bursts of requests | istek patlamaları | Kısa sürede gelen yoğun istek yığınları; esneklik (elasticity) özelliğinin ölçtüğü durum. |
| bursts of traffic | trafik patlamaları | Kısa sürede gelen yoğun trafik yığınları; esneklik (elasticity) özelliğinin ölçtüğü durum; bursts of requests (istek patlamaları) ile ilişkilidir. |
| bursts of users | kullanıcı patlamaları | Kısa sürede gelen yoğun kullanıcı yığınları; esneklik (elasticity) özelliğinin karşıladığı durum; bursts of requests (istek patlamaları) ile ilişkilidir. |
| business analyst | iş analisti | Gereksinimleri açıklayan ve analiz eden uzman rolü. |
| business domain | iş alanı | business domain expertise bağlamında |
| business domain knowledge | iş alanı bilgisi | mimarların iş alanını anlaması; 'have business domain knowledge' beklentisi |
| business drivers | iş etkenleri | Mimari kaygılara dönüşen iş tarafındaki itici güçler (kayıp sipariş istememe, hız, maliyet gibi). |
| business layer | iş katmanı | Katmanlı mimaride iş mantığını barındıran katman |
| business rules | iş kuralları | İş mantığını oluşturan kurallar; teknik bölümlemede teknik yetenek olarak ayrılan grup. |
| business stakeholder | iş paydaşı | İş tarafındaki ilgili taraflar |
| C-level executives | üst düzey yöneticiler | CEO, CFO, CTO gibi unvanlar |
| caching | önbellekleme | caching product bağlamında |
| call graph | çağrı çizgesi | Yöntem çağrılarını ve dönüşlerini düğümler ve kenarlar olarak gösteren çizge. |
| callee | çağrılan | Çağrının hedefi olan taraf; caller'ın (çağıran) karşıtı. |
| caller | çağıran | Bir çağrıyı başlatan taraf; callee'nin (çağrılan) karşıtı. |
| capacity | kapasite | Belirlenen en yüksek sınırların aşılma derecesi; performans verimliliğinin alt ölçütü. |
| career path | kariyer yolu |  |
| CC | CC | Cyclomatic complexity (döngüsel karmaşıklık) kısaltması; kısaltma olduğu gibi korunur. |
| change control | değişiklik kontrolü | değişikliklerin izlenmesi ve onaylanması süreci |
| chaos engineering | kaos mühendisliği | Sistemin dayanıklılığını bilinçli arıza enjekte ederek test etme yöntemi. |
| Chaos Kong | Chaos Kong | Netflix'in, bütün bir Amazon veri merkezi arızasını simüle eden aracı; ürün adı olduğu gibi korunur. |
| Chaos Monkey | Kaos Maymunu | Netflix'in kaos mühendisliğinin öncüsü olan, üretim ortamında rastgele arıza simüle eden aracı; Simian Ordusu'nun (Simian Army) ilk üyesi. |
| characteristics | özellikler | Kitapta architectural characteristics → mimari özellikler anlamında. |
| checklist | kontrol listesi | Tamamlanması gereken adımların listesi; otomatik kontrol listeleri bağlamında. |
| chief architect | baş mimar | ARB yoksa sapma taleplerini değerlendiren kişi |
| class diagram | sınıf diyagramı | her bileşen için oluşturulan, sınıfları ve ilişkilerini gösteren diyagram. |
| class loader | sınıf yükleyici | Java'da sınıfları classpath üzerinden belleğe yükleyen mekanizma. |
| classpath | classpath | Java'da sınıf ve kaynakların arandığı dizin/JAR yolu; yerleşik terim, olduğu gibi kullanılır. |
| co-constructor | ortak yapıcı | Yazılım sisteminin birlikte inşa edilmesinde rol alan kişi; geliştiriciler, proje yöneticisi, operasyon ekibi gibi mimarla birlikte çalışan taraflar. |
| coaching | koçluk | mimarın geliştiricilere yönelik birebir yönlendirmesi. |
| coarse-grained | kaba taneli (coarse-grained) | Bileşen parçalılığı bağlamında; ince taneli (fine-grained) tasarımın karşıtı, üst düzey yapı taşları ölçeğinde bir başlangıç noktası. |
| code base | kod tabanı |  |
| code coverage | kod kapsamı (code coverage) | Testlerin kodu ne ölçüde çalıştırdığını gösteren ölçüt; Crap4J ile ilişkili. |
| code quality metrics | kod kalitesi ölçütleri | Kaynak kodun kalitesini ölçen ölçütler; Bölüm 6'da ele alınan ve kod tabanlarını bütüncül olarak etkileyen ölçütler bağlamında geçer. |
| code review | kod incelemesi | Bir geliştiricinin yazdığı kodun başka bir kişi tarafından gözden geçirilmesi; çoğulu kod incelemeleri. |
| code smell | kod kokusu | Kodda belirli bir sorunu ya da tasarım kusurunu işaret eden kalıntı. |
| code-level metrics | kod düzeyi ölçütler | Kaynak kodun yapısından türetilen, kod tabanına ilişkin ölçütler (döngüsel karmaşıklık gibi); neredeyse tamamı yorum gerektirir. |
| codify | kodlamak (kurala dökmek) | Bir kuralı ya da ilkeyi kod biçiminde ifade ederek otomatik denetlenir hâle getirmek; yönetişim kontrollerinin uygunluk fonksiyonu olarak kodlanması bağlamında. |
| coding hygiene | kod hijyeni | Kredi kartı numaralarını düz metin saklamamak, iletim sırasında şifrelemek gibi özel mimari yapı gerektirmeyen temel güvenlik önlemleri; security hygiene (güvenlik hijyeni) ile ilişkilidir. |
| coexistence | birlikte var olma | Uyumluluğun alt ölçütü; ortak ortam ve kaynakları paylaşırken işlev görme. |
| cohesion | bütünlük | Modülün parçalarının aynı modülde tutulma derecesi; coupling (bağlılık) ile birlikte kullanılır. |
| cohesiveness | bütünlük | Bir modülün uyum (cohesion) derecesi; cohesive (uyumlu) sıfatı da bu sayfada geçer. |
| coincidental cohesion | tesadüfi bütünlük | Öğelerin yalnızca aynı kaynak dosyada bulunması nedeniyle ilişkili sayıldığı, uyumun en olumsuz biçimi. |
| collaboration | iş birliği | mimar ile geliştirme ekibi arasındaki yakın çalışma |
| comfort zone | konfor alanı | beceri/sorumluluk bağlamında |
| communication connascence | iletişim eşdoğuşu | Bileşenler arasındaki iletişim/etkileşim biçiminden kaynaklanan eşdoğuş ölçümü; sayfada geleneksel bağlılık ölçütleriyle (coupling metrics) birleştirilen yeni ölçü olarak geçer. |
| communication protocol | iletişim protokolü | servisler arası iletişimde kullanılan protokol (REST, gRPC gibi) |
| communication structure | iletişim yapısı | İnsanlar arasındaki iletişim düzeni; Conway Yasası'nda tasarıma kopyalanan yapı olarak geçer. |
| communicational cohesion | iletişimsel bütünlük | İki modülün, her birinin aynı bilgi üzerinde işlem yaptığı bir iletişim zinciri oluşturduğu bütünlük düzeyi. |
| compatibility | uyumluluk | ISO 25010 özelliği; aynı ortamı paylaşırken bilgi alışverişi ve işlev görme derecesi. |
| competitive advantage | rekabet avantajı |  |
| compile-time dependency | derleme zamanı bağımlılığı | Derleme sırasında çözümlenen bağımlılık; dinamik bağlantı kütüphaneleri (dynamic link libraries) gibi çalışma zamanında yüklenen bağımlılıkların karşıtı. |
| compliance | uyum | mimari kararlara uygun davranma; 'ensure compliance with decisions' beklentisi |
| component | bileşen | Çoğulu: bileşenler. |
| component discovery | bileşen keşfi | Bileşenlerin varlığının ve kullanımının belirlenmesi; sayfada kapsam (scope) ile birlikte ele alınan bileşen etrafındaki mimari değerlendirme konusu. |
| component identification | bileşen belirleme (component identification) | Bileşenlerin ilk kez belirlenmesi ve geri bildirimle yinelemeli olarak iyileştirilmesi süreci; component discovery (bileşen keşfi) ile ilişkilidir. |
| composite characteristics | bileşik özellikler | Daha küçük ölçekte birçok başka mimari özelliği barındıran özellikler; örn. çeviklik modülerlik, dağıtılabilirlik ve test edilebilirliği kapsar. |
| concert ticket booking system | konser bileti rezervasyon sistemi | Yeni biletler satışa çıktığında trafik patlamaları yaşayan, esneklik gerektiren örnek sistem. |
| concurrent users | eşzamanlı kullanıcılar | Aynı anda sistemi kullanan kullanıcı sayısı; ölçeklenebilirlik ölçümünde temel kavram. |
| confidentiality | gizlilik | Verilere yalnızca erişim yetkisi olanların erişebilmesi; güvenlik özelliği. |
| Conformity Monkey | Uygunluk Maymunu | Netflix mimarlarının yönetişim kurallarını üretim ortamında uygulatan aracı; Simian Ordusu üyesi. |
| connascence | eşdoğuş (connascence) | İki bileşenin, birindeki değişiklik diğerinde de değişikliği zorunlu kılıyorsa eşdoğuşlu olduğu söylenir; Bölüm 3'te (Modülerlik) ayrıntılı ele alınır. |
| Connascence of Algorithm (CoA) | Algoritma Eşdoğuşu (CoA) | Statik eşdoğuş türlerinden biri; birden çok bileşenin belirli bir algoritma üzerinde anlaşmasını gerektirir. |
| Connascence of Convention (CoC) | Uylaşım Eşdoğuşu (CoC) | Connascence of Meaning ile eş anlamlı kullanılan ad; convention sözcüğü, belirli değerlerin anlamı üzerindeki uzlaşımı ifade eder. |
| Connascence of Execution (CoE) | yürütme eşdoğuşu (CoE) | Birden çok bileşenin yürütülme sırasının önemli olduğu dinamik eşdoğuş türü. |
| Connascence of Identity (CoI) | kimlik eşdoğuşu (CoI) | Birden çok bileşenin aynı varlığa başvurması gerektiği dinamik eşdoğuş türü. |
| connascence of meaning | anlam eşdoğuşu | Birden çok bileşenin belirli bir değerin ne anlama geldiği konusunda anlaşması gereken eşdoğuş türü; connascence of convention (kural eşdoğuşu) ile eşanlamlı. |
| Connascence of Meaning (CoM) | Anlam Eşdoğuşu (CoM) | Statik eşdoğuş türlerinden biri; birden çok bileşenin belirli değerlerin anlamı üzerinde anlaşmasını gerektirir. |
| connascence of name | ad eşdoğuşu | Birden çok bileşenin bir varlığın adı üzerinde anlaşması gereken eşdoğuş türü; en yaygın ve en çok tercih edilen biçimdir. |
| Connascence of Name (CoN) | Ad Eşdoğuşu (CoN) | Statik eşdoğuş türlerinden biri; birden çok bileşenin bir varlığın adı (ör. metot adı) üzerinde anlaşmasını gerektirir. |
| Connascence of Position (CoP) | Konum Eşdoğuşu (CoP) | Statik eşdoğuş türlerinden biri; birden çok bileşenin değerlerin sırası (ör. parametre düzeni) üzerinde anlaşmasını gerektirir. |
| Connascence of Timing (CoT) | zamanlama eşdoğuşu (CoT) | Birden çok bileşenin yürütülme zamanının önemli olduğu dinamik eşdoğuş türü; tipik örneği yarış durumudur (race condition). |
| Connascence of Type (CoT) | Tür Eşdoğuşu (CoT) | Statik eşdoğuş türlerinden biri; birden çok bileşenin bir varlığın türü üzerinde anlaşmasını gerektirir. |
| Connascence of Values (CoV) | değer eşdoğuşu (CoV) | Birbiriyle ilişkili birden çok değerin birlikte değişmesi gerektiği dinamik eşdoğuş türü. |
| connascent | eşdoğuşlu | İki bileşen, birindeki değişiklik diğerinde de değişikliği zorunlu kılıyorsa eşdoğuşludur; connascence (eşdoğuş) teriminin sıfat biçimi. |
| connected components | bağlı bileşenler | Çizge kuramında kenarlarla birbirine bağlı düğüm kümeleri; fan-out çağrıları için genel döngüsel karmaşıklık formülündeki (CC = E − N + 2P) P sayısını temsil eder. |
| constraint | kısıt | Sistemi ve geliştirme ekiplerini sınırlayan mimari karar ya da kural |
| consumer | tüketici | Mesajlaşmada mesajı alan taraf. |
| containership | kapsayıcılık (containership) | Bileşenlerin diğer öğeleri içinde barındıran genel bir kapsayıcı mekanizma olma özelliği. |
| continuity | süreklilik | İş sürekliliği (business continuity) bağlamında; kesinti sonrası sistemin hızla yeniden çevrimiçi olması gereği. |
| continuous build | sürekli derleme | Her değişiklikte otomatik derleme ve testleri çalıştırma uygulaması; continuous integration (sürekli entegrasyon) ile ilişkilidir. |
| continuous delivery | sürekli teslim | Yazılımın her an yayınlanabilir durumda tutulduğu uygulama. |
| continuous integration | sürekli entegrasyon | Her değişikliğin push edildiği anda derlenip test edildiği uygulama. |
| contract | sözleşme | Mesajlaşmada üzerinde anlaşılan mesaj yapısı/biçimi. |
| Conway's law | Conway Yasası (Conway's law) | Organizasyonların, iletişim yapılarının kopyaları olan tasarımlar üretmeye zorlandığını söyleyen gözlem; bu sayfada Conway's Law kesit başlığı olarak geçer. |
| coordination | koordinasyon | Ortak çalışan tarafların eylemlerinin düzenlenmesi; paylaşılan çıktıların koordinasyonu zorlaştırması bağlamında geçer. |
| corollary | vargı | Bir yasadan çıkarılan doğal sonuç (Corollary 1 → Vargı 1). |
| coupling | bağlılık | Bileşenlerin birbirine bağımlılık derecesi |
| coupling metrics | bağlılık ölçütleri | Bileşenler arası bağımlılık derecesini ölçen ölçütler; sayfa 44'te ayrıntılı ele alınır. |
| coupling point | bağlılık noktası | İki parçayı birbirine bağlayan ve kırılabilecek bağlılık yeri; tasarım, analiz ve evrimde göz önünde bulundurulur. |
| Crap4J | Crap4J | Java dünyasında, CC ve kod kapsamını birleştirerek kod kalitesini değerlendiren ölçüt aracı; ürün adı olduğu gibi korunur. |
| critical path | kritik yol | Proje yönetiminde, bir projenin tamamlanma süresini belirleyen görevler dizisi; burada mimarinin darboğazı olabilecek kod bağlamında kullanılır. |
| criticality | kritiklik derecesi | Bir sistemin ya da özelliğin kritiklik/önem düzeyi; güvenlik gibi örtük özelliklerin önceliklendirilmesinde göz önüne alınır. |
| CRM | müşteri ilişkileri yönetimi (CRM) | customer relationship management kısaltması |
| cross-cutting architecture characteristics | çapraz kesimli mimari özellikler | Tablo 4-3'te listelenen, kolayca kategorize edilemeyen mimari özellikler; sayfa 60'ta geçer. |
| cross-functional team | çapraz fonksiyonlu ekip | Belirli bir alan (domain) etrafında, gerekli tüm teknik yetkinliklere sahip ekip; Ters Conway Manevrası bağlamında alanlar etrafında kurulur. |
| customer relationship management | müşteri ilişkileri yönetimi | CRM olarak da bilinir |
| customizability | özelleştirilebilirlik | Bir mimari özellik (-ility); sayfa 75'te en az önemli özellik olarak elenebileceği ve davranışın uygulama tasarımına taşınabileceği tartışılır. |
| customization | özelleştirme | Ürünün temel işlevselliğinin dışında, belirli bir alana/coğrafyaya özel eklemeler; Silicon Sandwiches vaka çalışmasında ortak (common) ve yerel (local) varyasyonları kapsar. |
| customization code | özelleştirme kodu | Ortak ve yerel varyasyonlar gibi müşteriye özel değişiklikleri karşılayan kod; alan bölümlemesinde birden çok yerde görünebilir, teknik bölümlemede ayrı bir bileşende toplanır. |
| cycle | döngü | Paket/sınıf bağımlılık çizgesinde kendine dönen bağımlılık; cyclic dependency (döngüsel bağımlılık) ile ilişkilidir. |
| cyclic dependencies | döngüsel bağımlılıklar | Bileşenlerin birbirine dairesel biçimde bağımlı olduğu durum; modülerliğe zarar verir. |
| cyclic dependency | döngüsel bağımlılık | İki veya daha fazla bileşenin birbirine başvurduğu, modülerliği bozan bağımlılık durumu. |
| cyclomatic complexity | döngüsel karmaşıklık | kod karmaşıklığını ölçen metrik |
| data architecture | veri mimarisi | Verinin nasıl saklanacağını ve erişileceğini düzenleyen mimari yaklaşım. |
| data center | veri merkezi | Sunucu ve ağ altyapısının barındırıldığı tesis |
| data coupling | veri bağlılığı | Yapısal programlamada, modüllerin metot çağrıları aracılığıyla veri paylaştığı bağlılık türü. |
| data protection | veri koruma | GDPR, Sarbanes Oxley gibi mevzuatların kapsadığı, verilerin korunmasına yönelik yasal düzenleme; yasal kısıtlamalar bağlamında geçer. |
| data structure | veri yapısı | Verinin düzenlenip saklanma biçimi; bütünlüğü (integrity) korumak için öğelerin birlikte değişmesi gerekebilir. |
| database schema | veri tabanı şeması |  |
| database server | veritabanı sunucusu | Veritabanı yönetimini barındıran sunucu |
| DBA | DBA | database administrator (veritabanı yöneticisi) kısaltması; kısaltma olduğu gibi korunur. |
| decision point | karar noktası | Kodda farklı yürütme yollarına yol açan karar deyimi (if gibi); döngüsel karmaşıklık hesabının temelini oluşturur. |
| decode domain language | alan dilini çözmek | Alan terimlerini (ör. kullanıcı sayısı) mühendislik karşılıklarına (ör. ölçeklenebilirlik) dönüştürmek. |
| decoupled | gevşek bağlı | coupling (bağlılık) karşıtı; topic yaklaşımının üreticiyi tüketicilerden ayırması bağlamında |
| decoupling | bağlılığın kırılması (decoupling) | coupling (bağlılık) teriminin karşıtı. |
| defensive design | savunmacı tasarım | Bir kısıtlama veya en kötü senaryo etrafında yapılan korumacı tasarım. |
| dependent components | bağımlı bileşenler | Kod tabanı dışındaki, mimari özellikleri (özellikle operasyonel olanları) etkileyen veritabanı, kuyruk, harici servis gibi bileşenler. |
| deployability | dağıtılabilirlik | Yazılımın üretim ortamına kolayca ve güvenilir biçimde yayınlanabilme özelliği; çeviklik (agility) bileşeni. Deployment (dağıtım) ile karıştırılmamalıdır. |
| deployment | dağıtım | Yazılımın çalıştırma ortamına yüklenmesi. |
| deployment unit | dağıtım birimi | Birlikte dağıtılabilir tek bir birim; modüler monolit tanımında 'tek dağıtım birimi' bağlamında geçer. |
| derived metric | türetilmiş ölçüt | Ham bağlılık değerinden türetilen ölçüt; soyutluk, kararsızlık ve ana diziden uzaklık gibi. |
| design decision | tasarım kararı | Tasarım sırasında verilen ve sistemin yapısını/davranışını etkileyen karar; architecture decision (mimari karar) ile ilişkilidir. |
| design pattern | tasarım deseni | Yinelenen tasarım sorunlarına kanıtlanmış çözüm kalıpları |
| design principle | tasarım ilkesi | katı kural yerine yol gösteren ilke |
| design principles | tasarım ilkeleri | Günlük kodlama ve geliştirme kararlarını yönlendiren rehber ilkeler (ör. Tek Sorumluluk İlkesi). |
| developer role | geliştirici rolü (developer role) | Mimar rolüyle karşıtlık kuran; bileşenleri sınıflara, fonksiyonlara ve alt bileşenlere bölme sorumluluğunu taşıyan rol. |
| DevOps | DevOps | Yerleşmiş terim; bu hâliyle kullanılır. |
| directory | dizin | Dosya sisteminde dosyaları gruplayan yapı; klasör. |
| disaster recovery | olağanüstü durum kurtarma | Felaket sonrası sistem ve verinin kurtarılması yeteneği; operasyonel mimari özellik. |
| distance from the main sequence | ana diziden uzaklık | Soyutluk–kararsızlık grafiğinde bir bileşenin ana diziden (A+I=1 doğrusu) uzaklığı; D = A + I − 1 ile hesaplanır, normalleştirilmiş biçimi |A + I − 1|'dir. |
| distributed architecture | dağıtık mimari | Mikroservisler gibi, bileşenlerin farklı süreçlerde/makinelerde çalıştığı mimari; distributed systems (dağıtık sistemler) ile ilişkilidir. |
| distributed queue | dağıtık kuyruk | Birden çok bileşenin paylaşıp güncellediği, dağıtık ortamda yaşayan kuyruk. |
| distributed systems | dağıtık sistemler | Birden çok makinede çalışan ve birbirleriyle ağ üzerinden iletişim kuran sistemler. |
| domain | alan (domain) | Problem alanı bağlamında. |
| domain analyst | alan analisti | İş alanını (domain) analiz eden ve gereksinimleri anlamlandıran kişi; mimar ve geliştiricilerle birlikte iş birliği yapan paydaş. |
| domain concern | alan kaygısı | İş alanından (domain) gelen kaygı; Tablo 5-1'de mimari özelliklere çevrilir. Architectural concern (mimari kaygı) ile karıştırılmamalıdır. |
| domain concerns | alan kaygıları | Alan paydaşlarının iş tarafındaki endişeleri; mimari özelliklere çevrilir (Tablo 5-1). |
| domain knowledge | alan bilgisi | Belirli bir iş alanına ilişkin bilgi; mimarlar için her zaman faydalıdır. Business domain knowledge (iş alanı bilgisi) ile ilişkilidir. |
| domain partitioning | alan bölümlemesi (domain partitioning) | Mimarinin alanlar ya da iş akışları etrafında bölümlenmesi; teknik bölümlemenin (technical partitioning) karşıtı. |
| domain requirements | alan gereksinimleri | Sorun alanına (problem domain) ilişkin gereksinimler; mimari özelliklerle birlikte yazılım çözümünü oluşturur. |
| domain stakeholder | alan paydaşı | Çoğulu: alan paydaşları (domain stakeholders); iş alanını temsil eden paydaş. |
| domain-driven design | alan odaklı tasarım (domain-driven design) | Yazılımı modellemek için alanı (domain) merkeze alan tasarım yaklaşımı; DDD kısaltmasıyla da bilinir. |
| domain-level predictions | alan düzeyi öngörüler | Kullanıcı sayısı gibi, alan tarafında beklenen ölçütlere ilişkin öngörüler. |
| domain-targeted descriptions | alan odaklı açıklamalar | Mimari özelliklerin türetildiği, belirli bir alana (domain) yönelik açıklamalar. |
| don't repeat yourself (DRY) | kendini tekrar etme (DRY) | Kod tekrarını önleyen tasarım ilkesi |
| driving architectural characteristics | yönlendirici mimari özellikler | Bir sistemi yönlendiren, öncelikli mimari özellikler; bunları belirlemek mimari çalışmanın ilk adımlarındandır. |
| dynamic connascence | dinamik eşdoğuş | Çağrıları çalışma zamanında analiz eden eşdoğuş türü; statik eşdoğuşun (static connascence) karşıtı. |
| dynamic link library | dinamik bağlantı kütüphanesi (DLL) | Uygulamanın çalışma zamanında yüklediği paylaşımlı kütüphane; DLL kısaltması korunur. |
| dynamically typed language | dinamik tipli dil | Türlerin çalışma zamanında belirlendiği programlama dili. |
| ecosystem | ekosistem | Birbirini etkileyen teknoloji, araç ve uygulamaların bütünü |
| edge | kenar | Çizge kuramında iki düğümü birbirine bağlayan çizgi; döngüsel karmaşıklık formülünde olası kararları (E) temsil eder. |
| edge cases | uç durumlar (edge cases) | Sistemin sınırında ortaya çıkan, yeniden tasarımı teşvik eden özel durumlar; boundary conditions (sınır koşulları) ile ilişkilidir. |
| efferent coupling | çıkan bağlılık | Bir kod öğesinden diğer kod öğelerine giden bağlantıların sayısı; Robert Martin'in Ce (fan-out) ölçütü. |
| elastic scale | esnek ölçekleme | İhtiyaca göre kaynak örneklerini artırıp azaltma yeteneği |
| elasticity | esneklik | Kaynakların talebe göre otomatik artırılıp azaltılabilmesi yeteneği (elastic scale) |
| encapsulation | kapsülleme | Veriyi ve davranışı bir birim içinde saklayıp dışarıya kontrollü erişim sunma; kapsüllemek (encapsulate) eylemi de bu sayfada geçer. |
| encryption | şifreleme | Verinin yetkisiz kişilerce okunamayacak biçime dönüştürülmesi; standart güvenlik hijyeninin parçası. |
| end-of-day fund pricing | gün sonu fon fiyatlaması | İş günü sonunda fonların fiyatlandığı toplu işlem; kitabın örneğinde kullanılır. |
| engineering discipline | mühendislik disiplini |  |
| engineering practices | mühendislik uygulamaları | Süreçten bağımsız, kanıtlanmış ve tekrarlanabilir fayda sağlayan uygulamalar. |
| enterprise | kuruluş | işletme/şirket bağlamında |
| enterprise architect | kurumsal mimar | Kuruluş genelindeki sistem ve çözümlerin mimarisini yönlendiren, kurumsal ölçekte kararlardan sorumlu mimar rolü. |
| enterprise service bus (ESB) | kurumsal servis veri yolu (ESB) | Servisler arası entegrasyonu ve mesajlaşmayı sağlayan merkezi bileşen. |
| entity | varlık | Gereksinimlerde tanımlanan, genellikle bir veritabanı tablosuna karşılık gelen nesne; entity trap (varlık tuzağı) ile ilişkilidir. |
| entity trap | varlık tuzağı | Mimarın veritabanı ilişkilerini yanlışlıkla uygulama iş akışları sanarak bileşenleri varlıklara göre oluşturduğu ters desen (anti-pattern). |
| entropy | entropi | Fizikten ödünç alınan, sistemlerin düzensizliğe yönelme eğilimi. |
| esoteric | az bilinen (esoteric) | Herkesçe bilinmeyen, yalnızca uzmanlara özgü; bu sayfada ölçüt ve uygunluk fonksiyonunu niteleyen sıfat. |
| estimation | tahmin | Proje tahmini bağlamında. |
| event processor | olay işleyicisi | Olay güdümlü mimarilerde olayları işleyen bileşen; birçok olay işleyicisi için dağıtılabilir iş birimi bağlamında geçer. |
| event-driven architecture | olay güdümlü mimari | Bileşenlerin olaylar aracılığıyla iletişim kurduğu mimari stil; asenkron çağrıların yaygın olduğu ortam. |
| evolutionary architecture | evrimsel mimari | Zamanla değişime uyum sağlayan mimari. |
| evolutionary computing | evrimsel hesaplama | Doğal evrim süreçlerinden esinlenen hesaplama alanı. |
| exchange | exchange | AMQP'de üreticinin mesaj gönderdiği bileşen; yerleşik terim, olduğu gibi kullanılır. |
| expertise | uzmanlık | Bir konudaki derin bilgi ve beceri; piramidin tepesindeki bilgi düzeyi. |
| explicit architecture characteristics | açık mimari özellikler | Gereksinim belirtiminde açıkça yer alan mimari özellikler; örtük olanların (implicit) karşıtı. |
| explicit characteristics | açık özellikler | Gereksinim belgesinde açıkça yer alan mimari özellikler; implicit characteristics (örtük özellikler) ile karşıtlık oluşturur. |
| extensibility | genişletilebilirlik | architectural extensibility (mimari genişletilebilirlik) bağlamında |
| external data storage | harici veri depolama | Uygulama dışında barındırılan veri deposu (veritabanı vb.). |
| external mapping services | harici harita servisleri | Trafik bilgisi sağlayan, dışarıdan entegre edilen harita servisleri; entegrasyon noktası örneği. |
| Extreme Programming (XP) | Extreme Programming (XP) | Yerleşmiş terim; Türkçe karşılığı yaygın değildir, İngilizce hâliyle kullanılır. |
| facilitation | kolaylaştırıcılık | toplantı/çalışma yürütme becerisi |
| fail-safe | güvenli arıza (fail-safe) | Arıza durumunda sistemin güvenli biçimde davranması; çökme yerine yumuşak bozunma. |
| fan-in | fan-in (gelen bağlantı sayısı) | Bir modüle giren bağlantıların sayısı; afferent coupling ile ilişkilidir. |
| fan-out | fan-out (giden bağlantı sayısı) | Bir modülden çıkan bağlantıların sayısı; efferent coupling ile ilişkilidir. |
| fault tolerance | hata toleransı | Sistemin bileşen arızalarına rağmen çalışmaya devam edebilme yeteneği. |
| feasibility | fizibilite (uygulanabilirlik) | Bir çözümün zaman ve bütçe açısından uygulanabilirliği; Tablo 5-1'de zaman ve bütçe kaygısının karşılığı. |
| feature flag | özellik anahtarı (feature flag) | Davranışı kod değişikliği olmadan açıp kapatan bayrak; feature toggle (özellik anahtarı) ile eş anlamlı. |
| feature toggles | özellik anahtarları | Davranışı kod değişikliği olmadan açıp kapatmayı sağlayan bayraklar |
| feedback | geri bildirim | Yazılım tasarımında yinelemeli iyileştirmeyi yönlendiren geri bildirim; feedback loop (geri bildirim döngüsü) ile ilişkilidir. |
| feedback loop | geri bildirim döngüsü | Kararların sonucunun hızla değerlendirilmesini sağlayan döngü; Çevik yaklaşımın temel avantajı |
| fervent fans | ateşli hayranlar | Konser bileti satışlarında siteye hücum eden, hevesli taraftarlar; esneklik örneğinde geçer. |
| field | alan | Sınıf düzeyinde tanımlanan değişken; örnek alanı (instance field). |
| fire-and-forget | ateşle ve unut (fire-and-forget) | Gönderenin yanıt beklemediği, mesajı gönderip işine devam ettiği asenkron iletişim biçimi. |
| first contentful paint | ilk içerikli boyama (first contentful paint) | Tarayıcının ilk görünür içeriği (metin, görsel vb.) çizdiği anı ölçen web performans ölçütü. |
| first CPU idle | ilk CPU boşta kalması (first CPU idle) | Sayfanın kullanıcı etkileşimlerini işleyebilmek için CPU'nun ilk kez boşta kaldığı anı ölçen web performans ölçütü. |
| First Law of Software Architecture | Yazılım Mimarisi Birinci Yasası | “Yazılım mimarisindeki her şey bir ödünleşimdir.” |
| first-page render | ilk sayfa görüntülenmesi (first-page render) | Bir web sayfasının, tarayıcıda veya mobil cihazda görünen ilk ilerleme işareti; en uygun süresi 500 ms olarak ölçülür. |
| fitness function | uygunluk fonksiyonu | bir mimari özelliği ölçen otomatik denetim; Bölüm 6'da ayrıntılı ele alınır |
| fragility | dayanıksızlık | brittleness (kırılganlık) ile eş anlamlı kullanılan, tasarımın hasara karşı dirençsizliği. |
| framework | çerçeve |  |
| franchise | bayilik (franchise) | Silicon Sandwiches vaka çalışmasında, her dükkânın farklı bir sahibi olduğu işletme modeli; franchised sıfatı 'bayilik sistemine bağlı (franchised)' olarak çevrilir. |
| fraud | dolandırıcılık (fraud) | Geçmişte sorun oluşturmuş, güvenlikle ilgili bir alan kaygısı; mimarın hangi güvenlik düzeyini tasarlarsa tasarlasın daha fazla girdi istemesini gerektirir. |
| friction | sürtünme | Uyumsuz süreç veya araçların yarattığı direnç. |
| frontend | ön uç | Kullanıcıya görünen taraf; frontend. |
| Frozen Caveman Anti-Pattern | Donmuş Mağara Adamı Anti-Deseni | Mimarın her mimaride en sevdiği mantıksız endişeye geri dönmesini anlatan davranış anti-deseni; sayfa 30'da ele alınır. |
| fully qualified name | tam nitelikli ad | Bir öğeyi benzersiz biçimde tanımlayan, paket/alan adı zincirini içeren tam ad. |
| functional appropriateness | işlevsel yerindelik | İşlevlerin belirtilen görev ve hedeflerin gerçekleştirilmesini kolaylaştırma derecesi; functional suitability (işlevsel uygunluk) ile karıştırılmamalıdır. |
| functional cohesion | işlevsel bütünlük | En yüksek bütünlük düzeyi; modülün tüm parçaları birbiriyle ilişkilidir. |
| functional completeness | işlevsel tamlık | İşlevler kümesinin belirtilen tüm görevleri ve kullanıcı hedeflerini kapsama derecesi. |
| functional correctness | işlevsel doğruluk | Ürünün sonuçları gereken kesinlik derecesiyle doğru biçimde sağlama derecesi. |
| functional language | fonksiyonel dil | Hesaplamanın fonksiyonlar aracılığıyla yapıldığı programlama dili. |
| functional requirements | işlevsel gereksinimler | Sistemin gerçekleştirdiği alan işlevlerini tanımlayan gereksinimler; mimari özelliklerin karşıtı. |
| functional suitability | işlevsel uygunluk | ISO 25010 kalite özelliği; ürünün işlevlerinin belirtilen ve ima edilen ihtiyaçları karşılama derecesi. |
| functionality | işlevsellik | Sistemin gerçekleştirdiği işlevler; mimari karakteristiklerden bağımsızdır |
| genetic algorithm | genetik algoritma | Çözümü mutasyon ve seçimle evrimleştirerek optimize eden algoritma. |
| global coupling | küresel bağlılık (global coupling) | Paylaşılan üst düzey bileşenlerdeki (Common, Local gibi) bir değişikliğin diğer tüm bileşenleri etkilemesi durumu; teknik bölümlemenin dezavantajı. |
| governance | yönetişim | Yunanca kubernan (yönlendirmek) sözcüğünden türeyen; mimari karar, süreç ve kalitenin yönetilip denetlenmesi. architectural governance (mimari yönetişim) ve governance mechanism (yönetişim mekanizması) ile ilişkilidir. |
| governance check | yönetişim kontrolü | Mimari ilkelere uyumu otomatik olarak denetleyen kontrol; uygunluk fonksiyonları aracılığıyla mimarinin dokusuna (substrate) kodlanır. |
| governance mechanism | yönetişim mekanizması | Mimari özelliklerin tanımlanması ve denetlenmesi için kurulan yapı/araç; architectural governance (mimari yönetişim) ile ilişkilidir. |
| granularity | parçalılık | Bir sistemin parçalara ayrılma incelik derecesi; 'Architectural Quanta and Granularity' kesit başlığında geçer. |
| graph theory | çizge kuramı | Çizge (graf) yapılarını inceleyen matematik dalı. |
| guideline | kılavuz ilke | yol gösteren ama dayatmayan ilke; karşılığı kılavuz/rehber |
| hands-on | uygulamalı | hands-on knowledge bağlamında |
| handshake | el sıkışma | İki tarafın protokol üzerinde anlaştığını doğrulayan karşılıklı el sıkışma adımı; ağ/doğrulama bağlamında. |
| hard-and-fast rule | katı ve kesin kural | istisnası olmayan, koşulsuz uygulanan kural |
| hard-coded | sabit kodlanmış | Değerlerin, adlandırılmış sabitler yerine doğrudan koda yazılması; genellikle bakımı zorlaştırır. |
| hashing | karma | Verinin geri döndürülemez biçimde sabit uzunlukta bir özete dönüştürülmesi; hashing algorithm (karma algoritması) ile ilişkilidir. |
| hashing algorithm | karma algoritması | İki tarafın (sunucu/istemci) aynı sonucu üretmesi gereken özet/karma üretim algoritması. |
| heterogeneous | heterojen | farklı teknolojilerden oluşan ortam |
| heterogeneous contracts | heterojen sözleşmeler | Birbirinden farklı yapıdaki mesaj sözleşmeleri. |
| high-frequency trading | yüksek frekanslı alım satım | Algoritmalarla çok hızlı ve çok sayıda finansal işlem yapan ticaret türü; düşük gecikme süresinin kritik olduğu ve örtük mimari özellik örneği olarak verildiği alan. |
| historical relevance | tarihsel önem | Yalnızca geçmiş bağlamında anlamlı olma durumu |
| holistic metric | bütüncül ölçüt | Bir sistemin bütününü tek bir değerle değerlendiren ölçüt; ana diziden uzaklık bunun örneğidir. |
| hotel reservation system | otel rezervasyon sistemi | Trafiği genellikle tutarlı olan, ölçeklenebilirliği esneklikten ayıran örnek sistem. |
| hybrid architecture | melez mimari (hybrid architecture) | Farklı parçalarının farklı mimari stiller kullandığı, kuantum başına analizle ortaya çıkan mimari. |
| implicit architecture characteristics | örtük mimari özellikler | Sorun alanından (problem domain) ve alan bilgisinden (domain knowledge) çıkarılan, gereksinimlerde açıkça yazılmayan mimari özellikler; esneklik (elasticity) ve güvenlik (security) bu sayfada örnek olarak verilir. |
| implicit characteristics | örtük özellikler | Gereksinimlerde açıkça yazılmayan, alan bilgisinden çıkarılan mimari özellikler; explicit characteristics (açık özellikler) ile karşıtlık oluşturur. |
| implicit knowledge | örtük bilgi | Açıkça ifade edilmeyen, alan (domain) hakkındaki sezgisel/deneyime dayalı bilgi. |
| import | import etmek | Sınıf/bileşen içe aktarma eylemi; geliştirici jargonunda İngilizce hâli korunur. |
| incidental coupling | tesadüfi bağlılık | Birbirinden bağımsız yöntemlerin hiçbir ortak alanı paylaşmadan aynı sınıfta toplanması durumu; LCOM ölçütünün sınıflar içinde ortaya çıkardığı bağlılık. |
| incidentally coupled | tesadüfen bağlanmış | Aralarında gerçek bir ilişki olmamasına rağmen tek bir sınıfta toplanmış; yüksek LCOM ile tespit edilir. |
| incremental change | artımlı değişiklik | Küçük adımlarla, düşük maliyetle yapılan değişiklik |
| independently deployable | bağımsız olarak dağıtılabilir | Mimari kuantum tanımında: başka parçalara bağımlı olmadan kendi başına işlev görebilen ve dağıtılabilen yapı. |
| indirection | dolaylı erişim (indirection) | Zararlı verileri gizlemek için erişimi bir aracı üzerinden dolaylı yapma tekniği. |
| infrastructure | altyapı | Sistemin üzerinde çalıştığı donanım ve ağ hizmetleri. |
| insecure code | güvenli olmayan kod | Güvenlik açığı içerebilecek, üretime sürülmemesi gereken kod; geliştiricilerde diğer önceliklerle rekabet eden güvenlik sorumluluğu bağlamında. |
| instability | kararsızlık | Robert Martin'in I ölçütü; çıkan bağlılığın toplam bağlılığa oranı. |
| installability | kurulabilirlik | Yazılımın belirtilen bir ortama kurulup kaldırılabilmesi. |
| integration architecture | entegrasyon mimarisi | Sistemler arası entegrasyonu düzenleyen mimari yön; iletişim protokolü (communication protocol) seçimleriyle ilgilidir. |
| integration point | entegrasyon noktası | Sistemin başka bir sistemle veya servisle iletişim kurduğu, üzerinde anlaşılmış arayüz/bağlantı noktası; üçüncü taraf ödeme işlemcisiyle kurulan bağlantı bağlamında. |
| integration points | entegrasyon noktaları | Sistemin başka bir sistemle veya servisle iletişim kurduğu, üzerinde anlaşılmış arayüz/bağlantı noktaları. |
| integrity | bütünlük | Yazılımın, yazılıma veya verilere yetkisiz erişimi ya da değişikliği önlemesi; güvenlik özelliği (integrity assessment ile karıştırılmamalıdır). |
| integrity assessment | bütünlük değerlendirmesi | Bir özelliğin veya parçanın durumunun nesnel olarak ölçülüp değerlendirilmesi. |
| interconnectivity | karşılıklı bağlantılılık (interconnectivity) | Mimari özelliklerin birbirini etkileme durumu; helikopter kumandaları benzetmesinde geçer. |
| interoperability | birlikte çalışabilirlik | Uyumluluğun alt ölçütü; iki veya daha fazla sistemin bilgi alışverişi ve kullanım derecesi. |
| interpersonal skills | kişilerarası beceriler | mimarlardan beklenen iletişim ve iş birliği becerileri; 'possess interpersonal skills' beklentisi |
| Inverse Conway Maneuver | Ters Conway Manevrası (Inverse Conway Maneuver) | Jonny Leroy'un ortaya attığı gözlem; istenen mimariyi teşvik etmek için ekip ve kuruluş yapısının birlikte evrilmesi. |
| isolation | yalıtım | Mimari düzeyde, bileşenlerin/katmanların birbirinden bağımsız tutulması; iyi modülerlikle birlikte test edilebilirlik ve dağıtım kolaylığına katkı sağlar. |
| iteration | yineleme | bir projenin tekrarlanan geliştirme çevrimi |
| iterative | yinelemeli |  |
| iterative development | yinelemeli geliştirme | Küçük ve tekrarlı adımlarla ilerleyen geliştirme biçimi |
| iterative process | yinelemeli süreç | Her adımda geri bildirim alarak art arda ilerleyen süreç. |
| Ivory Tower Architect | Fildişi Kule Mimarı (Ivory Tower Architect) | Uygulama ekibinden izole biçimde karar alan, ekiple iletişim kurmayan mimar davranışını anlatan anti-desen. |
| Janitor Monkey | Temizlikçi Maymun | Artık başka servislerin yönlendirmediği, sahipsiz kalan örnekleri üretimden kaldıran araç; Simian Ordusu üyesi. |
| Joint Application Design (JAD) | Ortak Uygulama Tasarımı (JAD) | Resmî, katılımcı gereksinim toplama/analiz yöntemi; mimarların gereksinim kaynağı olarak umursamadığı süreç örneklerinden biri; JAD kısaltması korunur. |
| kata | kata | Japonya'dan ve dövüş sanatlarından gelen, vurgunun doğru form ve teknik üzerinde olduğu bireysel eğitim alıştırması; yerleşik terim olduğu gibi kullanılır. |
| knowledge pyramid | bilgi piramidi | bilgiyi; bilinen, bilinmediği bilinen ve bilinmediği bilinmeyen olarak ayıran model; Şekil 2-3 |
| knowledge triangle | bilgi üçgeni | bilgiyi üç bölüme ayıran kavram; sayfada knowledge pyramid (bilgi piramidi) ile aynı anlamda kullanılır |
| known knowns | bilinen bilinenler | Rumsfeld'ın bilgi modelindeki terim. |
| known unknowns | bilinen bilinmeyenler |  |
| lack of cohesion in methods | yöntemlerde bütünlük eksikliği | LCOM metriklerinin ölçtüğü durum. |
| latency | gecikme süresi | Bir isteğin gönderilmesi ile yanıtın alınması arasında geçen süre; düşük gecikme (low latency), yüksek frekanslı alım satım bağlamında kritik önem taşır. |
| Latency Monkey | Gecikme Maymunu | Yüksek gecikme süresini simüle eden, gecikme sorununa özel yaratılmış araç; Simian Ordusu üyesi. |
| latest trends | güncel trendler | teknoloji ve sektör trendlerini takip etme; 'keep current with latest trends' beklentisi |
| Laws of Software Architecture | Yazılım Mimarisi Yasaları | Bölüm 1'in kesit başlığı ve sayfa 19'un koşu başlığı. |
| layer | katman | Katmanlı mimaride (layered architecture) bağımsız bir sorumluluk düzeyi; sayfada Controller, Service, Persistence katmanları bağlamında geçer. |
| layered | katmanlı | Katmanlı mimari stili |
| layered architecture | katmanlı mimari | Katmanlar halinde düzenlenmiş mimari stili |
| layered monolith | katmanlı monolit | Katmanları olan ancak tek bir dağıtılabilir birim olarak paketlenen monolitik uygulama; Şekil 6-4 bağlamında geçer. |
| LCOM metric | LCOM ölçütü | yöntemlerde bütünlük eksikliği (lack of cohesion in methods) ölçütü. |
| learnability | öğrenilebilirlik | Kullanıcının yazılımı kullanmayı öğrenme kolaylığı; kullanışlılığın alt ölçütü. |
| least worst architecture | en az kötü mimari (least worst architecture) | Tüm mimari özellikler en üst düzeye çıkarılamayacağı için, en az acı veren yan etkilere sahip mimari seçiminin yapılması. |
| legacy systems | eski sistemler | Tek veritabanı kullanılarak dağıtılan, tanım gereği tek bir mimari kuantum oluşturan geleneksel sistemler. |
| legal | yasal | Sistemin çalıştığı yasal bağlam; veri koruma, Sarbanes Oxley, GDPR gibi yasal kısıtlamalarla ilgili yapısal mimari özellik. |
| library | kütüphane | Yeniden kullanılabilir kod koleksiyonu; framework'ten (çerçeve) daha az yapılandırılmıştır. |
| lint test | lint testi | Kodda olası hataları ve biçim sorunlarını denetleyen test; lint terimi korunur. |
| litmus test | turnusol testi (litmus test) | Mimarların bir gereksinimin alan özelliği mi yoksa soyut mimari özellik mi olduğunu belirlemek için kullandığı hızlı ölçüt; uygulamak için alan bilgisi gerekip gerekmediğini sorar. |
| live video stream | canlı video akışı | Gerçek zamanlı olarak yayınlanan video; açık artırma örneğinde geçer. |
| load balancing | yük dengeleme | İş yükünün tüketiciler arasında dağıtılması. |
| locality | yerellik | Eşdoğuşlu öğelerin kod tabanındaki birbirine yakınlığı; Rule of Locality (Yerellik Kuralı) bağlamında. |
| loggability | günlüklenebilirlik (loggability) | Olay ve işlemlerin kayıt altına alınabilme özelliği; denetlenebilirlik (auditability) ile birlikte katılımcı izleme bağlamında geçer. |
| logical cohesion | mantıksal bütünlük | Modüldeki verinin işlevsel değil mantıksal olarak ilişkili olduğu uyum türü; örn. StringUtils gibi aynı tür veri üzerinde çalışan ilişkisiz statik yöntemler. |
| loose coupling | gevşek bağlılık | Bileşenler arası bağımlılığın az olması |
| machine learning | makine öğrenmesi | Gezgin satıcı probleminin temel olarak kullanıldığı alan; yaygın yerleşik terim, yaygın karşılığıyla verilir. |
| machine provisioning | makine sağlama | Sunucu ve kaynakların otomatik olarak hazırlanması. |
| magic value | sihirli değer | Adlandırılmış bir sabite bağlanmamış, kaynak kod içinde doğrudan yazılmış sayı/dizge değeri. |
| main sequence | ana dizi | Soyutluk–kararsızlık grafiğinde A+I=1 doğrusu; bu doğrudan uzaklık (distance from the main sequence) ile ölçülür. |
| maintainability | bakım yapılabilirlik | ISO 25010 kalite özelliği; yazılımın iyileştirilebilme, düzeltilebilme ve uyarlanabilme kolaylığı. |
| maturity | olgunluk | Yazılımın normal işleyişte güvenilirlik ihtiyaçlarını karşılaması; güvenilirliğin alt kategorisi. |
| memory address | bellek adresi | Kütüphanelerin çağıran kodla aynı bellek adresinde çalışma ve işlev çağrısı mekanizmalarıyla iletişim kurma bağlamında geçer. |
| mentoring | rehberlik | mimarın geliştiricilere yol göstermesi; coaching (koçluk) ile birlikte anılır. |
| mergers and acquisitions | birleşme ve satın almalar | Şirket evlilikleri ve devralmaları; M&A kısaltması da yaygındır. |
| message ordering | mesaj sıralaması | Mesajların verildikleri sırayla işlenmesi gereği; güvenilirlik (reliability) kaygısı olarak açık artırma örneğinde geçer. |
| messaging model | mesajlaşma modeli | yayınla-abone ol ve noktadan noktaya dahil mesajlaşma biçimleri |
| metaobject protocol | meta nesne protokolü (metaobject protocol) | Geliştiricilere ek genişletme mekanizmaları sağlayan programlama yapısı. |
| metrics | ölçütler | Ölçülebilir performans ve değer göstergeleri. |
| metrics suite | ölçüt takımı | Bir arada sunulan, birbiriyle ilişkili ölçütler dizisi; Chidamber ve Kemerer takımı gibi. |
| microkernel | mikro çekirdek | Bir mimari stil türü |
| microservice | mikroservis | Çoğulu: mikroservisler. |
| microservices | mikroservisler | Küçük, bağımsız dağıtılabilir servislerden oluşan mimari stil |
| microservices architecture | mikroservis mimarisi | mimari stil türü; servisler arası asenkron mesajlaşma örneği verilir |
| mindmap | zihin haritası |  |
| mission critical | görev açısından kritik | Arızası yaşamı veya büyük maddi sonuçları etkileyen sistem. |
| mixed cohesion | karma bütünlük | Bir sınıfın yöntem kümelerinin bazı alan gruplarını paylaşıp bazılarını paylaşmadığı ara bütünlük durumu; Şekil 3-1'deki Class Z örneği. |
| mnemonic | anımsatıcı | Bilgiyi hatırlamaya yardımcı olan sözcük ya da ipucu; burada afferent/efferent ayrımı için geliştirilen ipuçları. |
| Model-View-Controller | Model-Görünüm-Denetleyici (Model-View-Controller) | Katmanlı mimariyle örtüşen, yaygın tasarım deseni; MVC kısaltması da yaygındır. |
| modifiability | değiştirilebilirlik | Hata oluşturmadan ya da mevcut ürün kalitesini düşürmeden yazılımı değiştirebilme derecesi. |
| modular monolith | modüler monolit | Simon Brown'ın popülerleştirdiği; alanlar etrafında bölümlenen, tek dağıtım birimi olan mimari stil. |
| modular programming | modüler programlama | Kodu modül adı verilen bağımsız birimlerde gruplayan programlama yaklaşımı; Modula ve Ada gibi dillerde görülür. |
| modular reuse | modüler yeniden kullanım | Modülleri bağımsız birimler olarak başka bağlamlarda yeniden kullanma. |
| modularity | modülerlik |  |
| module | modül | İlgili kodun mantıksal olarak gruplandığı birim; nesne yönelimli dillerde sınıf grubu, yapısal veya fonksiyonel dillerde fonksiyon grubu olabilir. |
| monitoring | izleme | Sistemin durumunu ölçüp gözlemleme eylemi; monitors (izleyiciler) ile ilişkilidir. |
| monitors | izleyiciler | Sistemin durumunu sürekli izleyen araçlar. |
| monolithic architecture | monolitik mimari | Tüm bileşenlerin tek bir dağıtılabilir birimde toplandığı mimari |
| motivational requirements | motivasyon gereksinimleri | Kitaba göre işlevsel gereksinimler; yazılımı inşa etmeyi motive eden ancak mimari özellik olmayan gereksinimler. |
| moving target | hareketli hedef | Sürekli değişen, sabitlenemeyen konu ya da durum |
| name conflict | ad çakışması | Aynı kapsamda aynı ada sahip iki öğenin çakışması; Java 1.0 tasarımının önlemeye çalıştığı sorun. |
| namespace | ad alanı (namespace) | .NET gibi dillerde ilgili kodun gruplandığı modülerlik mekanizması. |
| nascent architect | yeni yetişen mimar | Kariyerinin başında, deneyimi az olan mimar; aspiring architect (mimar adayı) ile ilişkilidir. |
| negotiation | müzakere |  |
| negotiation skills | müzakere becerileri | Mimarların kararları onaylatmak için kullandığı beceriler |
| node | düğüm | Çizge kuramında (graph theory), kenarların (edges) birleştiği nokta; döngüsel karmaşıklık formülünde kod satırlarını (N) temsil eder. |
| nomenclature | adlandırma | Bir alana özgü terimler bütünü. |
| nonfunctional requirements | işlevsel olmayan gereksinimler | Yazılımın alan işlevselliğiyle doğrudan ilişkili olmayan özelliklerine (performans, kullanılabilirlik vb.) verilen yaygın ad; kitap bu terimi kendini küçültücü bulduğu için kullanmaz. |
| nonpriority debt | imtiyazsız borç | finansal terim; junior debt olarak da bilinir |
| nonrepudiation | inkâr edilemezlik | Eylemlerin veya olayların gerçekleştiğinin kanıtlanabilmesi; güvenlik özelliği. |
| object-oriented | nesne yönelimli | Nesneleri ve kapsüllemeyi temel alan programlama paradigması (OOP). |
| object-oriented language | nesne yönelimli dil | Kodun sınıflar ve nesneler etrafında düzenlendiği programlama dili. |
| object-relational mapping (ORM) | nesne-ilişkisel haritalama (ORM) | Framework'ün veritabanı tablolarını nesnelere ve kullanıcı arayüzüne eşlemesi; Naked Objects ve Isis gibi çerçeveler bağlamında geçer. |
| objective definition | nesnel tanım | Mimari özelliklerin, öznelliğe yer bırakmayan somut tanımı; sayfada 'objective definitions' biçiminde geçer. |
| objective function | amaç fonksiyonu | Uygunluk fonksiyonu tanımında 'çıktının amaca ne kadar yaklaştığını değerlendiren fonksiyon' anlamında geçer; metinde 'object function' olarak yazılmıştır. |
| objective measure | nesnel ölçüm | Bir mimari özelliğin öznelliğe yer bırakmadan otomatik olarak ölçülmesi; objective definition (nesnel tanım) ile ilişkilidir. |
| office politics | ofis politikaları | kurum içi güç ve çıkar dinamikleri |
| online auction | çevrim içi açık artırma | İnternet üzerinden yürütülen açık artırma. |
| online bidders | çevrimiçi teklif verenler (online bidders) | Açık artırma sitesine çevrimiçi olarak teklif veren kullanıcılar; mimari özelliklerin kuantum düzeyinde kapsamlanmasına örnek. |
| open source | açık kaynak | Kaynak kodu serbestçe kullanılabilen ve değiştirilebilen yazılım modeli |
| operating system | işletim sistemi | Donanım ile uygulamalar arasında arayüz sağlayan temel yazılım |
| operational architecture characteristics | operasyonel mimari özellikler | Performans, kullanılabilirlik gibi sistemin işletilmesiyle ilgili mimari özellikler; sayfa 75'te performans bu gruptan en az kritik olan olarak değerlendirilir. |
| operational awareness | operasyonel farkındalık | Sistemin işleyiş ve işletim boyutunu görme yetisi |
| operational concerns | operasyonel kaygılar | Ölçek, performans, esneklik gibi operasyonla ilgili mimari kaygılar |
| operational measure | operasyonel ölçüm | Bir mimari özelliğin işletimsel davranışını doğrudan ölçen ölçüm; sayfanın 'Operational Measures' kesit başlığı. |
| operations group | operasyon grubu | Sistemin işletilmesinden sorumlu ekip. |
| organizing principle | düzenleme ilkesi | Bir sistemin parçalarını düzenleyen temel ilke. |
| orphan service | sahipsiz servis | Artık hiçbir servisin çağırmadığı, üretimde çalışmaya devam eden ve maliyet üreten servis; Janitor Monkey'nin aradığı hedef. |
| orthogonal | ortogonal (bağımsız) | İşlevsellikle ilişkisiz, birbirinden bağımsız |
| outlier | aykırı değer | Ortalamadan belirgin biçimde sapan ölçüm; örn. diğerlerinden 10 kat daha uzun süren istekler. |
| outsourcing | dış kaynak kullanımı | Operasyon gibi işlevlerin maliyet tasarrufu amacıyla başka bir şirkete/ekibe devredilmesi |
| over-specify | aşırı belirlemek | Mimari özellikleri gerekenden fazla tanımlamak; sistem tasarımını gereğinden fazla karmaşıklaştırdığı için eksik belirlemek kadar zararlıdır. |
| package | paket | Java gibi dillerde ilgili sınıfların gruplandığı modülerlik mekanizması; dil anahtar sözcüğü olarak package korunur. |
| page load time | sayfa yükleme süresi | Bir sayfanın yüklenmesi için geçen süre; performans ölçütü. |
| paradigm | paradigma | Programlamada benimsenen model ya da yaklaşım; programlama paradigması bağlamında. |
| pattern | desen | Tasarım desenleri bağlamında; çoğulu: desenler. |
| payment processor | ödeme işlemcisi | Ödeme işlemlerini üçüncü taraf olarak yürüten hizmet; sayfada 'third-party payment processor' ifadesinde geçer. |
| peak times | yoğun saatler | Talebin en yüksek olduğu kullanım saatleri; performans özelliğinin ölçüldüğü koşullar. |
| perceived technical risk | algılanan teknik risk | Gerçekte var olup olmadığına bakılmaksızın mimarların hissettiği/algıladığı teknik risk; sayfa 30'da gerçek teknik riskle karşılaştırılır. |
| performance | performans | Sistemin iş yükü altındaki hız ve yanıt verebilirlik düzeyi; Tablo 4-1'de listelenen operasyonel mimari özellik. |
| performance budget | performans bütçesi | Bir sayfa ya da uygulamanın belirli performans ölçütleri (ör. ilk içerikli boyama) için ayrılan ve uygulanan üst sınır. |
| performance efficiency | performans verimliliği | ISO 25010 özelliği; performansın kaynak kullanımına göre ölçüsü. |
| persistence | kalıcılık | Verilerin kalıcı olarak saklanmasıyla ilgili teknik işlev grubu; teknik bölümlemeye örnek olarak verilir. |
| plain text | düz metin | Şifrelenmemiş, açık biçimde iletilen veri; kredi kartı numaraları bağlamında güvenlik hijyeni ihlali. |
| point-to-point messaging | noktadan noktaya mesajlaşma | Her mesajın tam olarak bir tüketici tarafından işlendiği mesajlaşma modeli. |
| portability | taşınabilirlik | Bir sistemin, ürünün ya da bileşenin bir ortamdan diğerine taşınabilme derecesi. |
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
| QA engineer | QA mühendisi | Kalite güvence (quality assurance) mühendisi; QA kısaltması korunur. |
| quality attributes | kalite özellikleri | Mimari özellikler için kullanılan bir diğer popüler terim; kitap, iş sonrası kalite değerlendirmesi ima ettiği için bu terimi de tercih etmez. |
| quantum | kuantum | Fizikten gelen kavram: bir etkileşime dahil olan herhangi bir fiziksel varlığın en küçük miktarı; mimari kuantumun (architecture quantum) kökeni. |
| queue | kuyruk | Mesajlaşmada, bir mesajı tek bir tüketiciye ulaştıran sıra; point-to-point modelin temel öğesi. |
| race condition | yarış durumu | İki iş parçacığının aynı anda çalışıp ortak işlemin sonucunu etkilemesiyle ortaya çıkan durum. |
| rates rally | oran rallisi | finansal terim; faiz oranlarındaki yükseliş |
| reactive-based framework | tepkisel tabanlı çerçeve | Angular, Elm, React.js, Vue gibi ön uç web çerçeveleri. |
| readability | okunabilirlik | Kodun okunma ve anlaşılma kolaylığı. |
| real-time | gerçek zamanlı | Olayın gerçekleştiği anda işlenmesi; performans özelliğiyle ilişkilidir. |
| recoverability | kurtarılabilirlik | Arıza sonrası sistemin yeniden çalışır duruma gelebilme yeteneği; operasyonel mimari özellik. |
| refactoring | refaktoring (yeniden düzenleme) | Davranışı değiştirmeden kodun iç yapısını iyileştirme. |
| reference architecture | referans mimari | Başkalarının izleyebileceği, örnek alınan mimari. |
| regulatory requirements | düzenleyici gereksinimler | Yasal ya da mevzuat kaynaklı gereksinimler; gün sonu fon fiyatlaması örneğinde geçer. |
| release | sürüm | Yazılımın kullanıcılara yayınlanması. |
| release environment | sürüm ortamı | Sürümün hazırlandığı, doğrulandığı ve yayınlandığı ortam. |
| reliability | güvenilirlik | Sistemin belirli koşullarda hatasız çalışma olasılığı; operasyonel mimari özellik. |
| remote access protocol | uzaktan erişim protokolü | REST, SOAP gibi uzak servis çağrılarında kullanılan protokol |
| replaceability | değiştirilebilirlik (replaceability) | İşlevselliğin başka bir yazılımla değiştirilebilme kolaylığı; modifiability (değiştirilebilirlik) ile karıştırılmamalıdır. |
| reputation index | itibar endeksi | Katılımcıların güvenilirliğini izleyen ölçüt; açık artırma kata'sında geçer. |
| requirements | gereksinimler | Sistemin karşılaması gereken işlevsel ihtiyaçlar. |
| requirements gathering | gereksinim toplama | Sistemin gereksinimlerinin toplanması çalışması; uygulanan yazılım geliştirme sürecine göre değişen tekniklerle yürütülür. |
| requirements specification | gereksinim belirtimi | Gereksinimlerin yazılı olarak tanımlandığı belge. |
| resilient architecture | dayanıklı mimari | Değişime ve arızalara karşı dirençli mimari. |
| resource utilization | kaynak kullanımı | Kullanılan kaynakların miktarı ve türleri; performans verimliliğinin alt ölçütü. |
| response time | yanıt süresi | Bir isteğin gönderilmesi ile yanıtın alınması arasında geçen süre; ortalama (average) ve en yüksek (maximum) yanıt süreleri bu sayfada geçer. |
| responsibility | sorumluluk | Mimarın rol kapsamı bağlamında. |
| restructuring | yeniden yapılandırma | Mimarinin bir desenden diğerine taşınması/değiştirilmesi |
| reusability | yeniden kullanılabilirlik | Bir yazılım varlığının birden fazla sistemde ya da başka varlıkların üretiminde kullanılabilme derecesi. |
| reuse mechanism | yeniden kullanım mekanizması | Kodun farklı yerlerde tekrar kullanılmasını sağlayan platform yeteneği. |
| rippling side effects | zincirleme yan etkiler | Bir değişikliğin bağımlı bileşenler üzerinde dalga dalga yol açtığı yan etkiler; technical partitioning bağlamında. |
| roadmap | yol haritası | Bir sistemi geliştirme sürecini gösteren plan |
| robustness | sağlamlık | Hata ve sınır koşullarında bile çalışmaya devam edebilme yeteneği; operasyonel mimari özellik. |
| rogue service | başıboş servis | Kurallar dışına çıkan, izinsiz davranan servis. |
| Rule of Degree | Derece Kuralı | Jim Weirich'in önerisi: güçlü eşdoğuş biçimlerini daha zayıf biçimlere dönüştürün. |
| Rule of Locality | Yerellik Kuralı | Jim Weirich'in önerisi: öğeler arası uzaklık arttıkça daha zayıf eşdoğuş biçimleri kullanın. |
| runtime | çalışma zamanı | Programın çalıştığı an; execution-time ile eş anlamlı kullanılır (kaynak kod düzeyi analizinin karşıtı). |
| sacrificial architecture | feda edilebilir mimari | Maliyet, zaman gibi kısıtlar nedeniyle bilinçli olarak basit tutulan ve ileride değiştirilmesi beklenen mimari. |
| scaffolding | iskele (scaffolding) | Ruby on Rails'in veritabanı tablo yapısına dayalı varsayılan kullanıcı arayüzü ve eşlemeler üreten özelliği. |
| scalability | ölçeklenebilirlik | Bir mimari özellik (“-ility”) |
| scope (scoping) | kapsam (scoping) | Bir tanımlayıcının görülebildiği ve erişilebildiği bölge; kapsam kuralları. |
| scoping rules | kapsam kuralları | Bir adın hangi bağlamlarda görünür ve erişilebilir olduğunu belirleyen kurallar. |
| seam | eklem (seam) | Kodu değiştirmeden davranışı değiştirebilmek için tasarıma bilinçli olarak yerleştirilen genişletme noktası. |
| Second Law of Software Architecture | Yazılım Mimarisi İkinci Yasası | “Neden, nasıl’dan daha önemlidir.” |
| security | güvenlik | Bir mimari özellik; sistem ve verilerin yetkisiz erişime karşı korunması. Sayfada availability (kullanılabilirlik) ve reliability (güvenilirlik) ile birlikte, neredeyse tüm uygulamaların altında yatan örtük (implicit) özelliklerden biri olarak geçer. |
| security breach | güvenlik ihlali | Güvenliğin ihlal edildiği olay/olay örüntüsü. |
| security hygiene | güvenlik hijyeni | Şifreleme, karma, yamalama gibi her sistemin uygulaması gereken standart, temel güvenlik önlemleri; sayfada 'standard security hygiene' bağlamında kullanılır. |
| Security Monkey | Güvenlik Maymunu | Her servisi bilinen güvenlik kusurlarına (etkin olmaması gereken portlar, yapılandırma hataları) karşı denetleyen araç; Simian Ordusu üyesi. |
| selective typing | seçici tipleme | Bazı dinamik tipli dillerin (Clojure, Clojure Spec) değişkenleri belirli türlerle sınırlama yeteneği. |
| separation of technical concerns | teknik kaygıların ayrıştırılması | Teknik bölümlemenin düzenleme ilkesi; katmanlı mimaride ortak teknik kaygıların ayrı tutulması. |
| sequential cohesion | sıralı bütünlük | Bir modülün çıktısının diğerinin girdisi olduğu bütünlük düzeyi. |
| service-level agreement (SLA) | hizmet düzeyi anlaşması (SLA) | Çalışma süresi, ölçek, yanıt verebilirlik gibi hizmet ölçütlerini tanımlayan sözleşme |
| service-oriented architecture (SOA) | servis odaklı mimari | İşlevleri bağımsız servisler olarak düzenleyen mimari yaklaşım. |
| services layer | hizmet katmanı | Katmanlı mimaride hizmetleri barındıran katman |
| shared artifacts | ortak paylaşılan çıktılar | Kuruluş genelinde ortaklaşa kullanılan, yeniden kullanım amacıyla oluşturulan ortak varlıklar/çıktılar; bağlılık ve koordinasyon sorunlarına yol açabilir. |
| shared resources | paylaşılan kaynaklar | Birden çok uygulamanın birlikte kullandığı altyapı kaynakları |
| shared utility classes | paylaşılan yardımcı sınıflar | Mimari değişiminde sıkıntı yaratan, birden çok sınıfın ortak kullandığı yardımcı sınıflar. |
| side effect | yan etki | Bir işlemin öngörülmeyen ya da istenmeyen sonucu |
| Simian Army | Simian Ordusu | Netflix'in kaos mühendisliği araçlarının genel adı; Conformity, Security, Janitor, Latency Maymunları ve Chaos Kong'u kapsar. Simian sözcüğü 'maymunsu' anlamına gelir. |
| simplicity | basitlik | Karmaşıklıktan kaçınma, tasarımı sade tutma; Tablo 5-1'de zaman ve bütçe kaygısının karşılığı. |
| single responsibility | tek sorumluluk | Her bileşenin tek bir sorumluluğu olması ilkesi |
| single source of truth | tek doğruluk kaynağı |  |
| soft skills | sosyal beceriler | İletişim, iş birliği gibi teknik olmayan beceriler |
| software architect | yazılım mimarı | Meslek/rol adı. |
| software architecture | yazılım mimarisi | Disiplin adı; kitabın ana konusu. |
| software asset | yazılım varlığı | Bileşen, sınıf gibi yeniden kullanılabilir yazılım öğesi. |
| software development ecosystem | yazılım geliştirme ekosistemi | Sektörü etkileyen topluluk, araç ve trendler bütünü. |
| source code-level | kaynak kod düzeyi | Kaynak kod seviyesindeki bağlılığı ifade eder; çalışma zamanı (execution-time) bağlılığının karşıtı. |
| source validator | kaynak doğrulayıcı | Kaynak kodu belirli kodlama kurallarına göre otomatik denetleyen araç. |
| Space-Based Architecture | Alan Tabanlı Mimari | Bölüm 15'te ele alınan, yüksek ölçek için veriyi dağıtan mimari stili. |
| spike | deneme (spike) | Zaman kutusuna alınmış, riskli bir varsayımı hızlıca doğrulamak için yapılan küçük deney/prototip; Extreme Programming kökenli. |
| stakeholders | paydaşlar |  |
| stale expertise | bayat uzmanlık | Güncelliğini yitirmiş bilginin hâlâ en ileri düzey olduğu yanılgısı; uzmanlığın sürdürülmemesi sonucu oluşur. |
| static code analysis | statik kod analizi | Kodu çalıştırmadan kaynak düzeyinde inceleyen analiz; statik eşdoğuşun keşfedilme yöntemi. |
| static connascence | statik eşdoğuş | Kaynak kod düzeyindeki eşdoğuş; Structured Design'daki afferent ve efferent bağlılık ölçütlerinin nesne yönelimli dillere uyarlanmış hâli. |
| static initializer | statik başlatıcı | Java'da sınıf yüklenirken bir kez çalışan, statik alanları başlatan kod bloğu. |
| static typing | statik tipleme | Değişken ve parametrelerin belirli türlerle sınırlandırılması; statik tipli dillerin yaygın özelliği. |
| statically typed language | statik tipli dil | Değişken ve parametrelerin belirli türlerle sınırlandığı programlama dili. |
| Strangler Pattern | Strangler Deseni | Eski sistemi aynı arayüzün arkasında parça parça değiştirerek yeni mimariye geçme deseni |
| strategy pattern | strateji deseni | GoF tasarım deseni |
| stratification | katmanlaşma | Bileşenlerin iç içe yerleştirilerek katmanlar oluşturması; bileşen çeşitlerini gösteren Şekil 8-1 bağlamında geçer. |
| streaming bids | canlı yayınlanan teklifler (streaming bids) | Açık artırma sisteminde tekliflerin ve video akışının canlı olarak yayınlanması; Going, Going, Gone katasında mimari kuantum örneği. |
| streaming video | video akışı (streaming video) | İnternet üzerinden kesintisiz video aktarımı; örnek uygulama türü olarak geçer. |
| stress testing | stres testi | Sistemin sınırlarını zorlayarak davranışını ölçen performans testi; tepe noktası (zirve) analiziyle ilişkilidir. |
| structural change | yapısal değişiklik | Sistemin yapısını ilgilendiren değişiklik |
| structural cohesion | yapısal bütünlük | Bir modülün yapısının (ör. alan erişimi) ölçülebilen bütünlüğü; LCOM gibi yapısal ölçütlerle belirlenir. |
| structural decay | yapısal çürüme | Geliştiricilerin kodlama/tasarım değişiklikleri sonucu mimari özelliklerin bozulması. |
| structural evolvability | yapısal evrilebilirlik (structural evolvability) | Belirli mimari stillerin zaman içinde yapısal olarak evrilebilme yeteneği; Building Evolutionary Architectures kitabında ölçülmek istenen nitelik. |
| structural metric | yapısal ölçüt | Kodun yapısını (alan erişimi, bağımlılıklar gibi) kaynak düzeyinde ölçen ölçüt. |
| structural soundness | yapısal sağlamlık | Sistemin yapısının sağlam ve tutarlı olma durumu; tesadüfen oluşmaz, sürekli enerji gerektirir. |
| structure | yapı | Sistemin mimari stil türüyle ilgili yapısı |
| structure of the system | sistemin yapısı | Mimarinin en görünür parçası; mimari stili ve bileşen düzenini kapsar. |
| structured programming | yapısal programlama | Pascal ve C ile örneklenen, GOTO gibi kontrolsüz sıçramaları reddeden programlama anlayışı. |
| stuff you know you don’t know | bildiğini bilmediğin şeyler | Varlığından haberdar olunan ama uzmanlık gerektiren bilgi düzeyi; known unknowns (bilinen bilinmeyenler) ile ilişkilidir. |
| subcharacteristic | alt özellik | ISO 25010'da bir kalite özelliğini oluşturan alt kategoriler. |
| subcomponent | alt bileşen (subcomponent) | Bir üst düzey bileşenin içinde yer alan, katmanlar dahil daha küçük bileşen; üst düzey bölümleme alanlara odaklanırken bileşenlerin içinde alt bileşenler bulunabilir. |
| subject matter expert | konu uzmanı (subject matter expert) | Belirli bir konuda derin bilgiye sahip kişi; gereksinimi açıklaması için başvurulur, business analyst (iş analisti) ile ilişkilidir. |
| substrate | doku (substrate) | Mimarinin üzerine inşa edildiği temel katman/yapı; yönetişim kontrollerinin mimarinin bünyesine kodlanması bağlamında. |
| success criteria | başarı kriterleri | Sistemin başarılı sayılması için karşılanması gereken ölçütler |
| symbiotic relationship | simbiyotik ilişki | Birbirini tamamlayan ve destekleyen karşılıklı ilişki. |
| synchronous call | eşzamanlı çağrı | Çağıranın yanıt için beklediği, bloklayıcı çağrı biçimi; synchronous communication (eşzamanlı iletişim) ile ilişkilidir. |
| synchronous communication | eşzamanlı iletişim | Gönderenin yanıt beklediği, çağrının engelleyici (bloklayıcı) olduğu iletişim biçimi; asenkron mesajlaşmanın (asynchronous messaging) karşıtı. |
| synchronous connascence | eşzamanlı eşdoğuş | Dinamik eşdoğuşun (dynamic connascence) türü; uygulama bağlamı içindeki veya dağıtık servisler arasındaki eşzamanlı çağrıları ifade eder. |
| teamwork | takım çalışması |  |
| tech lead | teknik lider | Ekibin mühendislik kararlarını yönlendiren kişi; technical leader (teknik lider) ile aynı anlamda kullanılır. |
| technical breadth | teknik genişlik |  |
| technical capabilities | teknik yetenekler | Sunum, iş kuralları, servisler, kalıcılık gibi teknik işlev grupları; domain (alan) bölümlemesinin karşıtı. |
| technical debt | teknik borç | Kısa vadeli ya da acele çözümlerin biriktirdiği, sonradan ödenmesi gereken kod/tasarım borcu. |
| technical depth | teknik derinlik |  |
| technical leader | teknik lider | Ekibin mühendislik kararlarını yönlendiren kişi. |
| technical partitioning | teknik bölümleme (technical partitioning) | Mimarinin sunum, iş kuralları, kalıcılık gibi teknik yeteneklere göre bölümlenmesi. |
| technical top-level partitioning | teknik üst düzey bölümleme | Mimariyi sunum, iş kuralları, servisler, kalıcılık gibi teknik yeteneklere göre en üst düzeyde bölümleme; alan bölümlemesinin (domain partitioning) karşıtı. |
| technologist | teknoloji uzmanı | teknolojik bilgiyi kullanan, geliştirici veya mimar gibi teknik profesyonel |
| Template Method design pattern | Şablon Yöntemi (Template Method) tasarım deseni | Üst sınıfın bir iş akışının iskeletini tanımlayıp adımlarını alt sınıfların geçersiz kılmasına olanak tanıyan davranışsal tasarım deseni; üst sınıfların tanımladığı iş akışının alt sınıflarda geçersiz kılınabildiği bağlamda geçer. |
| temporal cohesion | zamansal bütünlük | Modüllerin zamanlama bağımlılıklarına göre ilişkili olduğu uyum türü; örn. sistem başlangıcında başlatılan görünüşte alakasız görevler. |
| test-first development | önce test geliştirme | Kod yazılmadan önce testin yazıldığı geliştirme yaklaşımı. |
| testability | test edilebilirlik | Geliştiricilerin ve diğer kişilerin yazılımı test edebilme kolaylığı. |
| testing environment | test ortamı | Değişikliklerin test edildiği ortam. |
| third party | üçüncü taraf | Sistemin dışında, işlemleri üstlenen bağımsız hizmet sağlayıcı (ödeme işlemcisi gibi). |
| third-party system | üçüncü taraf sistem | Sistemin güvendiği, dışarıda barındırılan başka bir sistem; arızası çağıran sistemin güvenilirliğini etkiler. |
| thread | iş parçacığı | Bir süreç içinde eşzamanlı çalışabilen en küçük yürütme birimi. |
| threshold | eşik (threshold) | Bir ölçüt için kabul edilebilir sınır değer; 'threshold value' bağlamında kullanılır. |
| throwaway code | atılacak kod | Yalnızca hızlı doğrulama için yazılan, üretime girmesi amaçlanmayan kod. |
| tightly coupled | sıkı bağlı | Birbirinin iç yapısına bağımlı, birlikte değişmek zorunda kalan öğelerin durumu. |
| time behavior | zaman davranışı | Yanıt, işlem süresi ve işleme hızı oranlarının ölçüsü; performans verimliliğinin alt ölçütü. |
| time to market | pazara çıkış süresi | Bir ürünün fikirden pazara ulaşması için geçen süre. |
| timebox | zaman kutusu | Bir alıştırmaya ya da etkinliğe ayrılan sınırlı süre; bu sayfada kata alıştırmasının zaman kutusuna alınması (timeboxed exercise) bağlamında geçer. |
| timeout | zaman aşımı (timeout) | Bir çağrının yanıt için beklediği azami süre; eşzamanlı çağrılarda güvenilirlik (reliability) kaygısı olarak geçer. |
| top-level component | üst düzey bileşen (top-level component) | Mimarinin en üst düzeyinde, seçilen bölümlemeye göre oluşturulan bileşen; üst düzey bölümleme (top-level partitioning) ile ilişkilidir. |
| top-level partitioning | üst düzey bölümleme | Mimarinin en üst düzeyde, stili belirleyen biçimde bölümlenmesi; katmanlı (layered) ya da modüler (modular) olabilir. |
| topic | topic | Yayınla-abone ol modelinde birden çok abonenin aynı mesajı aldığı kanal. |
| topology | topoloji | Sistem bileşenlerinin bağlantı ve dağılım yapısı. |
| trade-off | ödünleşim | Bir fayda için başka bir özellikten vazgeçme; metinde İngilizcesiyle de kullanılır |
| trade-off analysis | ödünleşim analizi | Rakipli seçenekler arasındaki ödünleşimleri (trade-off) değerlendirme; mimarın rolünün önemli bir parçası olarak mimari özelliklerin desteklenme maliyetini karşılaştırma. |
| transaction | işlem (transaction) | Bir bütün olarak gerçekleştirilmesi gereken; tüm değerlerin birlikte değiştiği atomik veri işleme birimi. |
| traveling salesperson problem | gezgin satıcı problemi | Çeşitli şehirler arasındaki en kısa rotayı bulmayı amaçlayan klasik optimizasyon problemi. |
| trigger-happy | düşünmeden davranan (trigger-happy) | Geliştirici davranışı için kullanılan deyim; önce davranıp sonra düşünme. |
| ubiquitous language | ortak dil (ubiquitous language) | Alan odaklı tasarımdan gelen; tüm ekip üyelerinin aynı terimleri aynı anlamda kullandığı ortak dil. |
| under-specify | eksik belirlemek | Mimari özellikleri gerekenden az tanımlamak; aşırı belirlemenin (over-specify) karşıtı. |
| unit testing library | birim testi kütüphanesi | Uygunluk fonksiyonlarının örtüştüğü mevcut doğrulama mekanizmalarından biri; unit tests (birim testleri) ve library (kütüphane) ile ilişkilidir. |
| unit tests | birim testleri | Tek bir kod birimini izole biçimde doğrulayan testler. |
| unknown unknowns | bilinmeyen bilinmeyenler |  |
| uptime | çalışma süresi | Sistemin kullanılabilir olduğu süre oranı |
| usability | kullanışlılık | ISO 25010 özelliği; availability (kullanılabilirlik) ile karışmaması için kullanışlılık olarak çevrilir. |
| user error protection | kullanıcı hatası koruması | Kullanıcıların hata yapmasına karşı koruma; kullanışlılığın alt ölçütü. |
| user satisfaction | kullanıcı memnuniyeti |  |
| user story | kullanıcı hikâyesi | Çevik geliştirmede, kullanıcı ihtiyacını kısa ve iş dilinde anlatan iş öğesi. |
| variance | sapma | bir standarda veya mimari karara incelenip onaylanan istisna/muafiyet |
| variance model | sapma modeli | sapma talep sürecini biçimlendiren kurumsal model |
| verification mechanism | doğrulama mekanizması | Bir özelliğin veya parçanın durumunu otomatik olarak doğrulayan mekanizma. |
| volatility | değişkenlik | Bir kod tabanının değişikliklerden etkilenme eğilimi; kararsızlık ölçütüyle belirlenir. |
| waterfall | şelale | şelale (waterfall) modeli; eski, sıralı yazılım geliştirme yaklaşımı |
| well-factored | iyi yapılandırılmış (well-factored) | Küçük, mantıklı ve sorumluluğu net metotlara bölünmüş kod; refactoring ile ilişkili. |
| whitepaper | teknik rapor | Beyaz rapor; teknik belge türü. |
| wiretap | izinsiz dinleme | Gizlice dinleme; mesaj akışını izinsiz gözlemleme. |
| workflow | iş akışı | İşlerin yapılandırılmış akışı. |
| working knowledge | çalışma bilgisi | Bir konuyu pratikte kullanabilecek düzeyde bilme. |
| zone of pain | acı bölgesi | Ana diziden sol alt köşeye çok sapan, aşırı somut ve kırılgan kodun bulunduğu bölge. |
| zone of uselessness | işe yaramazlık bölgesi | Ana diziden sağ üst köşeye çok sapan, fazla soyut ve kullanımı zor kodun bulunduğu bölge. |
