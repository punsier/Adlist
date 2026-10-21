# Adlist — AdGuard Home DNS Blocklists

Super Adblock Test (https://superadblocktest.com/) sayfasında 21 Ekim 2026 tarihinde incelenen **482 test kaydı** temel alınarak hazırlanmış AdGuard Home DNS engelleme listeleri.

- **482** test girdisi, **477** benzersiz alan adına karşılık gelir.
- Test sırasında **460** kontrol engellenmiş, **22** kontrol erişilebilir görünmüştür.
- DNS, URL'nin yolunu (`/rtrg`, `/gampad/ads` vb.) hedefleyemez; bu girişler alan adı kuralına dönüştürülmüştür.

## Abonelik URL'leri

| Liste | Kural | Doğrudan URL |
|---|---:|---|
| Tam test listesi | 477 | [adguard-home-tam-477.txt](https://raw.githubusercontent.com/punsier/Adlist/main/adguard-home-tam-477.txt) |
| Testte erişilebilir kalanlar | 22 | [adguard-home-erisilebilir-22.txt](https://raw.githubusercontent.com/punsier/Adlist/main/adguard-home-erisilebilir-22.txt) |
| Erişilebilir kalanlar, `vk.com` hariç | 21 | [adguard-home-erisilebilir-21-vk-haric.txt](https://raw.githubusercontent.com/punsier/Adlist/main/adguard-home-erisilebilir-21-vk-haric.txt) |

Kayıtların kategori ve test sonucunu görmek için [482 kayıtlık CSV raporunu](superadblocktest-482-kayit.csv) inceleyebilirsiniz.

## AdGuard Home'a ekleme

1. **Filters / Filtreler → DNS blocklists / DNS engelleme listeleri** bölümüne gidin.
2. **Add blocklist / Engelleme listesi ekle → Add a custom list / Özel liste ekle** seçin.
3. Yukarıdaki **raw.githubusercontent.com** URL'lerinden **yalnızca birini** yapıştırın.
4. Kaydedin, filtreyi güncelleyin ve isterseniz testi yeniden çalıştırın.

**Önemli:** Tam liste, reklam izleme yanında giriş, çerez onayı, video ve e-ticaret analitiği gibi meşru özellikleri de bozabilir. 22/21 adreslik listeler de sıfır riskli değildir; özellikle Google Tag Manager, OneTrust, Usercentrics, OneSignal ve benzeri alanların engellenmesi işlev kaybı yaratabilir. Önce kullandığınız uygulamaları kontrol edin; gerektiğinde AdGuard Home izin listesine istisna ekleyin.

**Not:** Test, tarayıcı/VPN/DNS engellemelerinin birleşik durumunu gösterir; AdGuard Home'un tek başına aynı oranı sağlayacağı veya DNS filtresinin YouTube reklamlarının tamamını engelleyeceği garanti değildir. Bu repo test anlık görüntüsüdür; kendiliğinden yeni alan adları eklemez.
