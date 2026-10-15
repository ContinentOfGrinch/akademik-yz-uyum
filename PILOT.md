# Pilot Programı — Bir Hafta Dene, Anlat

Akademik YZ Uyum, yapay zekâyla akademik çalışırken sınırı o anda gösteren ve
beyanı senin yerine tutan bir Claude skill'i. Testleri yapıldı, ama asıl sınav gerçek
çalışmalar. Bu yüzden bir hafta boyunca kendi işinde kullanıp ne gördüğünü
anlatacak 5-10 kişi arıyoruz.

**Kimler:** tez yazan lisansüstü öğrenciler, makale yazan akademisyenler, TÜBİTAK
veya başka bir fon başvurusu hazırlayanlar. Lisans öğrencileri de olur.

**Ne kadar zaman:** normalde zaten yaptığın işler. Ek olarak hafta sonunda 10
dakikalık bir form.

## 1. Kur

**Claude Code** kullanıyorsan:

```
/plugin install akademik-yz-uyum --marketplace ContinentOfGrinch/akademik-yz-uyum
```

**Claude.ai** (web, masaüstü, mobil) kullanıyorsan:

1. [Son sürümün sayfasından](https://github.com/ContinentOfGrinch/akademik-yz-uyum/releases/latest)
   `akademik-yz-uyum.zip` dosyasını indir.
2. Claude.ai'de **Ayarlar → Yetenekler (Capabilities)** sayfasında önce **kod
   çalıştırma ve dosya oluşturma** seçeneğini aç, sonra **Skills** bölümünde
   **Upload skill** ile zip dosyasını yükle. Bu özellik Pro, Max, Team ve Enterprise
   planlarında var; ücretsiz planda yok.
3. Mümkünse çalışman için bir **Claude Projesi** aç. Skill kullanım günlüğünü
   sohbette tutar; tabloyu projeye dosya olarak eklersen sonraki sohbetlerde de
   kaldığı yerden devam eder.

## 2. Bir hafta boyunca

Kendi işini yap; skill kendiliğinden devreye girer. Mümkünse şunlardan birkaçını dene:

- [ ] Bir **dil düzeltmesi** ya da **çeviri** iste (🟢 — sessiz kalmalı)
- [ ] Bir **bölüm taslağı** ya da **proje bölümü** iste (🟡 — yardım etmeli, izini tutmalı)
- [ ] **Tartışma veya sonuç bölümünü yazmasını** iste (🔴 — yolu göstermeli, ret gibi hissettirmemeli)
- [ ] Hafta sonunda **"yapay zekâ kullanım beyanımı hazırla"** de
- [ ] (İstersen) bir kırmızı isteğinde **ısrar et** ve ne yaptığına bak

## 3. Anlat

Hafta sonunda [deneyim formunu doldur](https://github.com/ContinentOfGrinch/akademik-yz-uyum/issues/new?template=pilot-geri-bildirim.yml).
En değerli geri bildirimler:

- Işık yanlış renkte yandığında
- Kırmızı çizgide sunulan yolun işe yaramadığı ya da fazla dolambaçlı olduğu yerler
- Gereksiz uyarılar
- Beyan metninin kurumunun istediğine uymadığı durumlar
- Kurumunun kendi yapay zekâ yönergesi varsa onun bağlantısı

## Gizlilik

Forma **tezinden, makalenden veya katılımcı verinden hiçbir içerik koyma**;
yalnızca deneyimini anlat. Skill'in kendisi verini hiçbir yere göndermez, ama
Claude'a girdiğin her şey Claude'un kullanım koşullarına tabidir. Yayımlanmamış
verini ve kişisel verileri yapay zekâya girmeden önce anonimleştir; skill de bunu
hatırlatır.
