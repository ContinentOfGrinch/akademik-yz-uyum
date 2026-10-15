# Kurum Yönergeleri

Bu klasör üniversitelerin, enstitülerin ve dergilerin kendi yapay zekâ kurallarını
tutar. Kurumun kuralı her zaman YÖK ve TÜBİTAK genel kurallarının önüne geçer
(SKILL.md, "Üstünlük sırası").

## Skill bu klasörü nasıl kullanır

Kullanıcının kurumu belli olduğunda (`.yz-beyan/baglam.md` ya da sohbet), bu
klasörde o kuruma ait bir dosya var mı diye bak. Varsa:

- Kırmızı/sarı/yeşil ayrımında kurumun daha katı ya da farklı bir hükmü varsa onu
  uygula ve kullanıcıya kurumun kuralı olduğunu söyle.
- Beyanı kurumun formuna ve istediği yere göre üret.

Dosya yoksa genel kurallarla devam et ve kullanıcıya kurumunun yönergesini
kontrol etmesini öner. Bir kurumun kuralını tahmin etme.

## Dosya biçimi

Dosya adı: kurumun kısaltması, küçük harf, Türkçe karaktersiz.
Örnek: `atauni-sbe.md`, `gantep-tip.md`.

```markdown
# <Kurum ve birim tam adı>

**Belge:** <belgenin tam adı>
**Tarih / sürüm:** <kabul veya değişiklik tarihi>
**Kaynak:** <resmî bağlantı>
**Doğrulama:** <kim, ne zaman, tam metin okunarak>

## Genel kurallardan farkı
- <YÖK/TÜBİTAK'tan daha katı veya farklı olan hükümler, madde numarasıyla>

## Beyanın yeri ve biçimi
- <form adı, nereye konacağı, istenen alanlar>

## Doğrudan alıntılar
> <belgenin kendi sözcükleri, madde numarasıyla>
```

## Ekleme kuralı

Yalnızca **resmî belgenin tam metni okunarak** doğrulanmış hükümler eklenir;
ikincil kaynak, haber veya forum yazısı yeterli değildir. Katkı için depoda
"Kurum yönergesi ekle" issue şablonunu kullan.
