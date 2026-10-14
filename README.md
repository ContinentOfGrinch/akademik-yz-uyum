# Akademik YZ Uyum

Claude Code / Claude.ai için bir skill. Akademik çalışmalarda yapay zekâ kullanımını
**YÖK**, **TÜBİTAK** ve uluslararası yayıncı kurallarına (ICMJE, COPE) uygun
yürütmeni sağlar.

Bir yasak listesi değil. Çalışma biçimi.

## Ne yapar

**1. Sınırı anlık olarak görünür kılar.** Her isteği üç bölgeye ayırır:

| | |
|---|---|
| 🟢 **Serbest** | Kaynak tarama, dil düzeltme, çeviri, kod, veri temizleme |
| 🟡 **Beyan gerektiren** | Taslak oluşturma, veri analizi yorumu, görsel üretimi |
| 🔴 **Yasak** | Bulgular/tartışma/sonuç yazdırma, veri uydurma, hakemlik, uydurma kaynak |

Bu ayrım uydurma değil — TÜBİTAK'ın kendi rehberi tam olarak bu üç başlığı kullanıyor
("Destekleyici / Dikkat Edilmesi Gereken / Yasaklanan Kullanımlar").

**2. Kırmızı bölgede kapıyı kapatmaz, yolu değiştirir.** "Tartışma bölümünü yaz"
dediğinde reddedip seni başka bir araca göndermez. Bulgularını tek tek sorar, her biri
için "bu literatürdeki hangi beklentiyi bozuyor?" diye sorar, iskeleti senin kendi
cümlelerinden çıkarır. Sonra o iskeleti düzenler — bu artık meşru bir kullanım.

**3. Arka planda kullanım günlüğü tutar.** Ne yaptığını `.yz-beyan/gunluk.md`
dosyasında biriktirir.

**4. Beyan metnini üretir.** Günlükten, hedef mercie göre hazır metin: tez, TR Dizin
dergisi, uluslararası dergi, TÜBİTAK proje başvurusu, etik kurul başvurusu —
Türkçe ve İngilizce.

Asıl fikir bu: **kısıtlama bir çıktıya dönüşüyor.** Uyum bir maliyet olmaktan çıkıp
işin bir parçası oluyor.

## Kimin için

- Tez yazan yüksek lisans ve doktora öğrencileri
- Makale yazan akademisyenler
- TÜBİTAK 1001/2209, Horizon gibi proje başvurusu hazırlayanlar
- Lisans öğrencileri
- Hakemlik yapanlar (burada kurallar çok daha katı — skill bunu bilir)

## Kurulum

### Claude Code

```
/plugin marketplace add KULLANICI_ADIN/akademik-yz-uyum
/plugin install akademik-yz-uyum
```

### Elle kurulum

`skills/akademik-yz-uyum/` klasörünü şuraya kopyala:

- **Windows:** `%USERPROFILE%\.claude\skills\`
- **macOS / Linux:** `~/.claude/skills/`

## Kullanım

Ayrıca bir şey yapman gerekmiyor. Akademik bir iş yapmaya başladığında kendiliğinden
devreye girer. İlk seferinde bağlamı sorar (tez mi makale mi, hangi dergi/enstitü,
rolün ne) ve bunu hatırlar.

Beyanını istediğinde sor:

> "Bu çalışma için yapay zekâ kullanım beyanı hazırlar mısın?"

## Kaynaklar

Referans dosyaları resmî belgelerden doğrudan çıkarılmıştır:

- [YÖK — Yükseköğretim Kurumları Bilimsel Araştırma ve Yayın Faaliyetlerinde Üretken Yapay Zekâ Kullanımına Dair Etik Rehber](https://eski.yok.gov.tr/Documents/2024/yapay-zeka-kullanimina-dair-etik-rehber.pdf) (7 Mayıs 2024)
- [TÜBİTAK — Destek Süreçlerinde ÜYZ'nin Sorumlu ve Güvenilir Kullanımı Rehberi](https://tubitak.gov.tr/sites/default/files/2025-10/UYZ_Rehberi_v03_TR.pdf) (Eylül 2025)
- ICMJE Recommendations (Nisan 2025 güncellemesi)
- COPE — Authorship and AI tools

## Sınırları

Bunu açıkça söylemek gerekiyor:

- **Bu bir uyum garantisi değildir.** Kurallar kurumdan kuruma değişir ve hızla
  güncellenir. Skill'in kendi içinde "senin kurumunun kuralı her zaman üsttedir"
  ilkesi yazılıdır.
- **Hukuki tavsiye değildir.** Bir etik soruşturma söz konusuysa kurumunun etik
  kuruluna danış.
- **Referans dosyaları eskiyebilir.** Kritik bir karar öncesi yukarıdaki
  bağlantılardan güncel metni kontrol et.

Skill'in amacı seni düşünmekten kurtarmak değil — sınırın nerede olduğunu, orada
olduğun anda göstermek.

## Katkı

Kurumunun yönergesi farklıysa, bir dergi politikası değiştiyse ya da bir kullanım
senaryosu eksikse issue aç. Özellikle değerli olanlar:

- Üniversite/enstitü tez yönergelerindeki farklı hükümler
- Alan-spesifik dergi politikaları
- Rehberlerin güncellenmesi

## Lisans

MIT
