# Beyan Metni Şablonları

Günlükten (`.yz-beyan/gunluk.md`) beyan üretirken bu şablonları kullan.

## Beyanı iyi yapan şey

İki beyanı karşılaştır:

> ❌ "Bu çalışmanın hazırlanmasında yapay zekâdan yararlanılmıştır."

> ✅ "Bu çalışmanın literatür taraması aşamasında, ilgili yayınların taranması ve
> özetlenmesi amacıyla [Model adı] ([sürüm kimliği], Anthropic) kullanılmıştır.
> Araç tarafından önerilen tüm kaynaklar yazar tarafından orijinal metinlerinden
> doğrulanmış, özetler karşılaştırılarak kontrol edilmiştir. Çalışmanın bulgular,
> tartışma ve sonuç bölümleri tamamen yazar tarafından kaleme alınmıştır. Metnin
> tüm içeriğinin sorumluluğu yazara aittir."

Birincisi hiçbir bilgi vermez ve şeffaflık ilkesini karşılamaz. İkincisi dört soruyu
da cevaplar: **hangi araç, hangi aşama, ne yapıldı, nasıl doğrulandı.**

Dördüncü unsur — doğrulama ve sorumluluk — çoğu beyanda atlanıyor ama en değerlisi
odur: kullanımın meşru olduğunu gösteren şey, doğrulamanın yapılmış olmasıdır.

**Ne beyan edilmez:** Rutin imla ve dilbilgisi denetimi, standart istatistik
yazılımları, yazım tamamlama. YÖK, ICMJE ve büyük yayıncılar bunları kapsam dışı
tutar. Her şeyi beyan eden bir metin, önemli olanı görünmez kılar.

---

## 1. Tez (yüksek lisans / doktora)

Yöntem bölümüne veya enstitünün istediği beyan sayfasına. Enstitünün kendi şablonu
varsa önce onu kullan.

```
Yapay Zekâ Kullanım Beyanı

Bu tez çalışmasının hazırlanması sürecinde üretken yapay zekâ araçlarından
aşağıda belirtilen kapsamda yararlanılmıştır:

• Araç: [Araç adı] ([model/versiyon], [geliştirici])
• Kullanım dönemi: [AA.YYYY – AA.YYYY]

Kullanım alanları:
1. [Bölüm adı] — [yapılan iş]. [Nasıl doğrulandığı.]
2. [Bölüm adı] — [yapılan iş]. [Nasıl doğrulandığı.]

Tezin araştırma sorusu, yöntem tasarımı, bulguların yorumlanması, tartışma ve
sonuç bölümleri tamamen tarafımdan oluşturulmuştur. Yapay zekâ araçları hiçbir
aşamada özgün katkının yerine kullanılmamış, yalnızca destekleyici araç olarak
işlev görmüştür. Araç tarafından üretilen tüm çıktılar tarafımca gözden
geçirilmiş ve doğrulanmıştır. Tezin tüm içeriğinin bilimsel ve etik
sorumluluğu bana aittir.

[Ad Soyad] — [Tarih]
```

**Örnek (doldurulmuş):**

```
• Araç: [Model adı] ([sürüm kimliği], Anthropic)
• Kullanım dönemi: 03.2026 – 09.2026

Kullanım alanları:
1. Literatür taraması — İlgili alanyazının taranması ve İngilizce kaynakların
   özetlenmesi. Önerilen tüm kaynaklar DOI üzerinden doğrulanmış ve orijinal
   metinlerinden okunmuştur.
2. Yöntem bölümü — Veri analizinde kullanılan Python betiklerinin yazımı ve hata
   ayıklaması. Betiklerin çıktıları sentetik veri setiyle manuel olarak test
   edilmiştir.
3. Dil — Tez metninin tamamında dilbilgisi ve anlatım akıcılığı denetimi. Her
   öneri tarafımca değerlendirilmiş, anlamı değiştirenler reddedilmiştir.
```

---

## 2. TR Dizin / ulusal hakemli dergi

Yöntem bölümünün sonuna veya derginin istediği beyan bölümüne.

```
Yapay Zekâ Kullanım Beyanı: Bu çalışmanın [aşama] aşamasında [amaç] amacıyla
[araç adı] ([versiyon]) kullanılmıştır. Araç çıktıları yazar(lar) tarafından
doğrulanmış ve gerekli düzeltmeler yapılmıştır. Çalışmanın özgün katkısını
oluşturan [bulgular / tartışma / sonuç] bölümleri tamamen yazar(lar) tarafından
oluşturulmuştur. Makalenin tüm içeriğinin sorumluluğu yazar(lar)a aittir.
```

Dergi ayrıca "Etik Beyan", "Yazar Katkı Oranı" ve "Çıkar Çatışması" bölümleri
istiyorsa, yapay zekâ beyanı bunlardan ayrı tutulmalı — yazar katkı oranına yapay
zekâ **eklenmez.**

---

## 3. Uluslararası dergi (ICMJE / COPE)

### İngilizce

```
Declaration of Generative AI Use in Scientific Writing

During the preparation of this work, the author(s) used [tool name] ([version],
[developer]) for [specific purpose, e.g. "language editing and improving
readability" / "summarising literature" / "generating code for statistical
analysis"]. After using this tool, the author(s) reviewed and edited the content
as needed and take(s) full responsibility for the content of the publication.

The study design, data interpretation, discussion and conclusions are entirely
the work of the author(s). No AI tool is listed as an author.
```

### Türkçe karşılığı

```
Bilimsel Yazımda Üretken Yapay Zekâ Kullanımı Beyanı

Bu çalışmanın hazırlanması sürecinde yazar(lar), [amaç] amacıyla [araç adı]
([versiyon], [geliştirici]) kullanmıştır. Araç kullanıldıktan sonra yazar(lar)
içeriği gözden geçirmiş ve gerektiği şekilde düzenlemiş olup yayının içeriğinin
tüm sorumluluğunu üstlenmektedir.

Çalışmanın tasarımı, verilerin yorumlanması, tartışma ve sonuçlar tamamen
yazar(lar)a aittir. Hiçbir yapay zekâ aracı yazar olarak gösterilmemiştir.
```

**Not:** Elsevier bu beyanın kaynakçadan önce ayrı bir bölüm olarak konulmasını
önerir. Springer Nature yöntem bölümünde belgelenmesini ister. Hedef dergi belliyse
yerini ona göre ayarla.

---

## 4. TÜBİTAK proje başvurusu

Başvuru sisteminde bu amaçla ayrılmış **özel bölüme** girilir; metnin içine değil.
TÜBİTAK rehberi üç bilgi ister:

```
Kullanılan araç ve versiyon:
[Araç adı], [versiyon], [geliştirici]

Kullanıldığı aşama/bölümler:
• [Bölüm] — [ne yapıldı]
• [Bölüm] — [ne yapıldı]

Kullanımın niteliği ve kapsamı:
[Kısa açıklama. Rehberin kendi örnek ifadeleri: "ilk taslak oluşturma",
"metin iyileştirme", "kod parçacığı üretme".]

Doğrulama:
Üretilen tüm çıktılar proje ekibi tarafından kontrol edilmiş, referanslar
birincil kaynaklardan doğrulanmıştır. Gizli, yayımlanmamış veya kişisel
nitelikteki hiçbir veri araca girilmemiştir.
```

Son satır önemli: TÜBİTAK rehberinin en sert yasağı gizli veri girişidir; beyanda
buna açıkça değinmek güven oluşturur.

---

## 5. Etik kurul başvurusu

YÖK rehberi, etik kurul başvurusunda yapay zekâ kullanımının bildirilmesini ister —
araştırma protokolünde **amaç, kapsam ve nitelik** belirtilir. Sık atlanan bir
yükümlülüktür; kullanıcıya hatırlat.

```
Araştırmada Üretken Yapay Zekâ Kullanımı

Amaç: [Neden kullanılacak]
Kapsam: [Hangi aşamalarda, hangi veriler üzerinde]
Nitelik: [Hangi araç, hangi işlev]

Veri güvenliği: Katılımcılara ait kişisel veriler [anonimleştirilerek /
hiçbir şekilde] yapay zekâ araçlarına aktarılacaktır. [Anonimleştirme yöntemi.]

Doğrulama: Araç çıktıları araştırmacı tarafından [yöntem] ile doğrulanacaktır.
```

---

## 6. Lisans / dönem ödevi

Ders kapsamında sadeleştirilmiş biçim yeterlidir. Ama önce dersin kendi kuralına
bak — bazı dersler yapay zekâ kullanımını tamamen yasaklar, o zaman beyan değil
kullanmama gerekir.

```
Yapay Zekâ Kullanım Beyanı

Bu ödevin hazırlanmasında [araç adı] şu amaçlarla kullanılmıştır:
• [Yapılan iş]
• [Yapılan iş]

Ödevin [argümanı / analizi / çözümü] tarafımdan oluşturulmuştur. Araç
çıktıları kontrol edilmiş ve doğrulanmıştır.

[Ad Soyad] — [Tarih]
```

---

## 7. Kullanılmadığı durumda

Bazı dergiler ve enstitüler, kullanılmadığında da beyan ister:

```
Bu çalışmanın hiçbir aşamasında üretken yapay zekâ aracı kullanılmamıştır.
```

Bunu yalnızca **gerçekten kullanılmadıysa** yaz. Günlükte 🟡 veya 🔴 kayıt varken
bu beyanı üretme — kullanıcıya günlüğü göster ve doğru şablona yönlendir.

---

## Dikkat: iki yaygın hata

**Yazar katkı oranına yapay zekâ eklemek.** Yapay zekâ yazar değildir, katkı oranı
tablosunda yeri yoktur. Beyan ayrı bir bölümdür.

**Yeri ezbere seçmek.** Doğru yer merciye göre değişir:

- **Tez:** YÖK yöntem bölümünü işaret eder; enstitünün kendi beyan formu varsa o
  geçerlidir.
- **ICMJE'ye bağlı dergiler:** yazım desteği **teşekkür** bölümüne, veri toplama /
  analiz / şekil üretimi **yöntem** bölümüne yazılır; kapak mektubunda da belirtilir.
  (ICMJE, "Defining the Role of Authors and Contributors" — doğrulandı: Ekim 2026.)
- **COPE:** yöntem bölümü (veya muadili).
- **Elsevier:** kaynakçadan önce ayrı beyan bölümü.

Derginin yazar yönergesi her zaman belirleyicidir.

---

## 8. Günlükte 🔴 kayıt varsa

Yukarıdaki şablonların hepsi "özgün katkı tamamen yazara aittir" diye biter. Bu cümle
yalnızca günlükte o bölüm için 🔴 kayıt **yoksa** doğrudur. Varsa bu cümleyi kullanma:
gerçeğe aykırı bir beyan, beyan etmemekten ağırdır.

Bunun yerine o bölümü ayrıca ve somut olarak yaz. Kullanıcının metni sonradan nasıl
ele aldığı burada belirleyicidir; günlükteki doğrulama sütununa bak.

```
[Bölüm adı] bölümünün ilk taslağı, yazarın bulguları ve yönlendirmesiyle
[araç adı] ([sürüm]) tarafından oluşturulmuştur. Taslak yazar tarafından
[baştan yeniden yazılmış / kapsamlı biçimde düzenlenmiş]; yorumların seçimi,
literatürle ilişkilendirme ve tüm atıflar yazara aittir ve yazar tarafından
doğrulanmıştır.
```

```
The initial draft of the [section] was generated by [tool] ([version]) based on
the author's findings and direction. The author [rewrote it in full /
substantially revised it]; the choice of interpretations, the links to the
literature and all citations are the author's own and were verified by the author.
```

Kullanıcı taslağı yeniden yazmadıysa köşeli parantezdeki seçeneklerden hiçbiri doğru
değildir. O durumda bunu olduğu gibi yaz ve kullanıcıya, teslimden önce metni
yeniden yazmanın hem beyanı hem de savunmasını güçlendireceğini bir kez söyle.

Enstitü veya dergi böyle bir kullanımı tümden yasaklıyorsa beyan sorunu çözmez.
Bunu kullanıcıya açıkça söyle.
