# FADA Mühendislik – SWOT Analizi

**Firma:** FADA Mühendislik ve Makina Sanayi ve Ticaret A.Ş. · Arifiye / Sakarya · SAMİB üyesi
**Ne yapar:** Fabrikalarda 5–500 tonluk ağır yükleri taşıyan araçlar üretir: transfer arabaları, otonom araçlar (AGV), hava yastıklı taşıyıcılar.
**İncelenen makine:** Otonom trafo transfer arabası (350 t sınıfı, akülü, uzaktan izlenebilir)
**Hazırlayan:** Muhammed Salih Atiç · Ekim 2026

> Eğitim amaçlı bir çalışmadır. Yalnızca kamuya açık bilgilere dayanır, resmî denetim değildir.

---

## Özet

FADA ağır yük taşımada güçlü bir mühendislik firması ve doğru zamanda doğru pazarda: ABD ve Avrupa'da trafo fabrikaları hızla kuruluyor, bu fabrikalar da tam olarak FADA'nın ürettiği araçlara ihtiyaç duyuyor.

Firmanın araçları artık **yazılımlı ve uzaktan bağlanabilir**. Bu yüzden ürünler yeni AB kurallarının (Makine Tüzüğü, CRA) kapsamına giriyor. Kurallar siber güvenliği zorunlu kılıyor ve son tarih **20 Ocak 2027**. Kamuya açık bilgide firmanın bu konuda bir hazırlığı görünmüyor. Analizin ana bulgusu bu.

---

## SWOT tablosu

| | 👍 Olumlu | 👎 Olumsuz |
|---|---|---|
| **İç** | **GÜÇLÜ YÖNLER**<br>• 500 tona kadar özel tasarım araç yapabiliyor<br>• Üretimin %60'ından fazlasını ihraç ediyor, 20+ ülkede 700+ proje tamamlamış<br>• Ürünleri tamamen elektrikli, enerji sektörüne odaklı<br>• Satış sonrası servis ve uzaktan izleme hizmeti var<br>• ISO 9001, 14001, 45001 ve CE belgeli | **ZAYIF YÖNLER**<br>• Ürünler uzaktan bağlanabilir ama görünür bir siber güvenlik çalışması yok<br>• Her proje sıfırdan tasarlanıyor; büyümek ve hızlı teklif vermek zor<br>• Genç (2018) ve orta ölçekli bir firma; kaynakları sınırlı<br>• Yurt dışındaki müşterilere sahada destek vermek zor<br>• İnternette referans ve katalog bilgisi az |
| **Dış** | **FIRSATLAR**<br>• ABD ve Avrupa'da trafo kıtlığı; yeni trafo fabrikaları kuruluyor<br>• Batarya depolama, rüzgâr ve nükleer projeleri artıyor<br>• Elektrikli ve otonom araç pazarı hızla büyüyor<br>• Yeni AB kurallarına erken uyan firma rakiplerinden ayrışır<br>• ABD'de yerel montaj ve servis kurma planı | **TEHDİTLER**<br>• AB Makine Tüzüğü 20.01.2027'de geçerli oluyor; uymayan ürün AB'de satılamaz<br>• Fidye yazılımı saldırıları en çok imalat firmalarını hedefliyor<br>• 350 tonluk otonom araçta bir siber saldırı fiziksel kazaya dönüşebilir<br>• Türkiye'de maliyetler hızla artıyor<br>• Aynı ilde güçlü bir rakip (Seyiton) ve ucuz Çinli üreticiler var |

---

## Zayıf yön ve tehditlerden çıkan çözüm önerileri

Bu tablo SWOT'un "ne yapılmalı?" kısmıdır. Her öneri, firmanın bir zayıf yönünü ya da tehdidini kapatmaya yöneliktir.

| Sorun | Neden önemli | Önerilen çözüm |
|---|---|---|
| Ürünlerde görünür bir siber güvenlik çalışması yok, AB son tarihi yaklaşıyor | Uyumsuz ürün AB pazarına giremez | **Siber uyum hazırlığı:** ürün risk analizi, güvenli uzaktan erişim tasarımı, yazılım bileşen listesi (SBOM), olay müdahale planı |
| Fabrika fidye yazılımına açık olabilir | Üretim durursa projeler gecikir, tasarımlar sızabilir | Ofis ve üretim ağlarının ayrılması, çevrimdışı yedek, iki adımlı giriş (MFA) |
| Yurt dışındaki müşterilere sahada destek zor | 20+ ülkede servis veriliyor | **Yapay zekâ destekli servis asistanı:** teknisyen kılavuz ve arıza kayıtlarına sorarak çözüm bulur; internetsiz de çalışabilir |
| Her proje sıfırdan tasarlanıyor, teklif hazırlamak uzun sürüyor | Büyümeyi yavaşlatıyor | **Dijital proje arşivi:** geçmiş 700+ projeden benzer tasarımı bulup teklif süresini kısaltan arama sistemi |
| İnternette referans ve katalog az | Yabancı alıcı önce internete bakıyor | Müşteri izinli başarı hikâyeleri ve indirilebilir teknik katalog |

---

## Öncelik sırası

1. **Hemen (0–3 ay):** AB kurallarına hazırlık ve güvenli uzaktan erişim. Son tarih kaçarsa AB satışları durur.
2. **Kısa vade (3–12 ay):** ABD trafo pazarına odaklanmak, servis asistanı ve proje arşivi gibi verimlilik araçlarını devreye almak.
3. **Orta vade (1–3 yıl):** Standart modüllerden oluşan ürün ailesi, bakım ve izleme abonelikleri.

---

## Laboratuvar föyleri

SWOT'taki siber güvenlik konuları, otonom trafo transfer arabası üzerinden 7 föyde ayrıntılı olarak çalışıldı:

| Föy | Konu |
|---|---|
| [Lab 1 · Safety Architecture](pdf/FADA_Lab1_Safety_Architecture.pdf) | Aracın insanı koruyan emniyet sistemi |
| [Lab 2 · IEC 62443](pdf/FADA_Lab2_IEC62443_Zone_Conduit.pdf) | Ağın güvenli bölgelere ayrılması |
| [Lab 3 · Threat & Risk](pdf/FADA_Lab3_Threat_Risk_Matrix.pdf) | Saldırı senaryoları ve risk puanları |
| [Lab 4 · Secure Remote Access](pdf/FADA_Lab4_Secure_Remote_Access.pdf) | Güvenli uzaktan servis erişimi |
| [Lab 5 · SBOM / CVE / Patch](pdf/FADA_Lab5_SBOM_CVE_Patch.pdf) | Yazılım açıklarının yönetimi |
| [Lab 6 · CRA Incident](pdf/FADA_Lab6_CRA_Incident_Simulation.pdf) | Siber olayda ilk 24 / 72 saat |
| [Lab 7 · AI Safety](pdf/FADA_Lab7_AI_Safety_Challenge.pdf) | Yapay zekâ hata yaptığında güvenli davranış |

Tüm föyler tek dosyada: [FADA_Lab_Foyleri_Doldurulmus.pdf](pdf/FADA_Lab_Foyleri_Doldurulmus.pdf)

---

## Kaynaklar

- [FADA – resmi web sitesi](https://www.fada.com.tr/en/)
- [Ekonomi Gazetesi – FADA, enerji sektörü ve ihracat (02.10.2026)](https://www.ekonomigazetesi.com/sirket-haberleri/fada-enerji-sektorunun-agir-yuk-tasima-sureclerine-operasyonel-cozumler-sunuyor-88875)
- [Ekonomi Gazetesi – FADA, 700+ proje (31.07.2026)](https://www.ekonomigazetesi.com/sirket-haberleri/fada-muhendislik-agir-sanayi-lojistiginde-kuresel-buyumesini-hizlandiriyor-84395)
- [SATSO – FADA firma sayfası (belgeler)](https://smmc.satso.org.tr/Firmalar/FADA-Muhendislik/11)
- [Seyiton – rakip firma](https://seyiton.com/en/)
- [Foley – ABD trafo kıtlığı (09.2026)](https://www.foley.com/insights/publications/2026/09/the-grids-bottleneck-isnt-just-money-its-materials/)
- [TÜV NORD – AB Makine Tüzüğü 2023/1230](https://www.tuev-nord.de/en/services/audit-and-expertise/product-certification/machinery-regulation/)
- [McCann FitzGerald – CRA bildirim yükümlülükleri](https://www.mccannfitzgerald.com/knowledge/data-privacy-and-cyber-risk/cyber-resilience-act-reporting-obligations-apply-from-11-september-2026)
- [Manufacturing.net – İmalatta fidye yazılımı (Zscaler 2026)](https://www.manufacturing.net/software/news/22975465/report-manufacturing-remains-most-targeted-industry-for-cyberattacks)
