---
title: Gizlilik Politikası ve KVKK Aydınlatma Metni
---

# Anluvo — Gizlilik Politikası ve KVKK Aydınlatma Metni

Son güncelleme: 25 Kasım 2026

Bu metin, 6698 sayılı Kişisel Verilerin Korunması Kanunu'nun (KVKK) 10. maddesi kapsamında aydınlatma
metni ve Anluvo uygulamasının gizlilik politikasıdır.

## 1. Veri sorumlusu

- **Veri sorumlusu:** Seyko Studio
- **Adres:** Gaziosmanpaşa Mahallesi, İlkbahar Sokak, Merkez / Yalova
- **E-posta (KVKK başvuruları dahil):** info@ghoso.app

## 2. Kısaca

- Dostların, anların, notların, planların, fotoğrafların, sesli notların ve İlişki Karnesi cevapların
  **yalnız telefonunda** durur. Bizim sunucumuza gelmez.
- Hesap açman gerekmez. Ad, e-posta, telefon numarası istemeyiz.
- **Sesle anlat** özelliğini kullanırsan, anlattığın şeyin yazıya çevrilmiş metni ve dostlarının adları
  anları çıkarmak için sunucumuza ve yapay zekâ sağlayıcımıza (Anthropic) gönderilir; sunucumuzda **saklanmaz**.
- **İlişki koçu** (Premium) ile konuşursan, mesajların ve telefonunda hazırlanan kısa bir özet (dostlarının
  adları, son görüşme zamanları, görüşme sıklığı, genelde sana nasıl geldikleri, İlişki Karnesi türleri, yaklaşan planlar)
  aynı yoldan gönderilir; **saklanmaz**. Anlarının metni varsayılan olarak gönderilmez; yalnız sen izin verirsen
  (Ayarlar > Anlu ya da Anlu sorduğunda) konuşulan kişiyle son 20 anın ve o kişiye yazdığın not gider. Kendine
  yazdığın kişisel notlar hiçbir zaman gönderilmez. İstersen Ayarlar > Anlu > "Hakkımda" alanına kendinden bahsedebilirsin;
  doluysa bu metin de Anlu'ya gönderilir. Sohbet geçmişi telefonunda kalır.
- Reklam yok, analitik ya da izleme aracı yok. Verini satmayız, başkalarıyla pazarlama için paylaşmayız.
- Verilerin yapay zekâ modeli eğitmek için kullanılmaz. Yapay zekâ özelliklerini (sesle anlat, koç, karne yorumu)
  ilk kullandığında **tek bir onay** istenir; onay vermezsen bu özellikler çalışmaz, uygulamanın geri kalanı çalışır.
- Bir yapay zekâ çıktısını **Bildir** ile bildirirsen o metin şifreli olarak saklanır ve en geç 90 gün sonra silinir.

## 3. Yalnız telefonunda kalan veriler

Aşağıdakiler cihazındaki uygulama veritabanında tutulur ve bize gönderilmez. Uygulamayı silersen ya da
uygulamanın verilerini temizlersen silinir. Kendi aldığın yedek dosyası, onu nereye kaydettiysen orada kalır.
Android'de bu veritabanı, telefonunun kendi yedeğine (Google hesabına) de eklenir; böylece telefon
değiştirdiğinde kendiliğinden geri gelir. Bu yedek bize değil, Google hesabına gider ve Google'ın gizlilik
politikasına tabidir. Fotoğraf ve sesli notlar bu yedeğe girmez. İstemezsen Ayarlar > Yedekleme > "Telefon
yedeğine dahil et" seçeneğini kapatabilirsin.

- Dostların (ad, fotoğraf, doğum günü, notlar, etiketler, yakınlık ve ilişki türü)
- Anlar (açıklama, tarih, his puanı, ruh hali, konum metni, etiketler, fotoğraflar, sesli notlar)
- Kişisel notlar, planlar ve hatırlatmalar, iddialar
- İlişki Karnesi test cevapları ve sonuçları
- Uygulama ayarların, öğrenilen takma adlar

Uygulama izin verirsen **rehberini** (dost eklemek için), **takvimini** (buluşma önerisi ve plan eklemek
için) ve **fotoğraf bilgilerini** (anı önerisi için) telefonunda okur; bunlar da telefonundan çıkmaz.
Hatırlatma bildirimleri telefonunda kurulur.

## 4. Telefonundan çıkan veriler

| Veri | Amaç | Hukuki sebep | Alıcı ve yer |
| --- | --- | --- | --- |
| **Ses → yazı:** sesle anlatırken konuşman | Konuşmanı yazıya çevirmek | Sözleşmenin ifası (KVKK m. 5/2-c) | Telefonun destekliyorsa telefonda işlenir, hiçbir yere gitmez. Desteklemiyorsa telefonunun konuşma tanıma servisi (Google ya da Apple) işler; o servisin kendi gizlilik politikası geçerlidir. Ses kaydı bize gelmez. |
| **Anlatım metni**, aktif dostlarının adları (ve uygulama içi numaraları), kullandığın etiketlerin adları, bugünün tarihi | Anlatımdan anları, notları, planları ve diğer kayıtları çıkarıp sana onay kartı olarak göstermek | Sözleşmenin ifası (m. 5/2-c); yurt dışına aktarım için bkz. bölüm 6 | Sunucumuz (Supabase, AB — İrlanda) üzerinden yapay zekâ sağlayıcısı Anthropic'e (ABD). Sunucumuz metni ve adları **saklamaz ve kayda geçirmez**. |
| **Anonim kullanıcı kimliği** (rastgele üretilen numara) | Aboneliği ve yapay zekâ kullanım sınırlarını bu cihaza bağlamak | Sözleşmenin ifası (m. 5/2-c) | Supabase (AB), RevenueCat (ABD) |
| **Kullanım kayıtları:** her yapay zekâ isteğinin zamanı, kullanılan model, işlenen metin uzunluğu (token sayısı), tahmini maliyet, sonuç türü, çıkarılan kayıt sayısı (içerik ve ad içermez) | Kota ve adil kullanım sınırı, kötüye kullanımı önleme, maliyet takibi | Meşru menfaat (m. 5/2-f) | Supabase (AB); en fazla 13 ay |
| **İlişki koçu ve Premium karne yorumu:** mesajların, son mesajların geçmişi, telefonunda üretilen özet (dost adları, ilişki türü ve yakınlığı, son görüşme, görüşme sıklığı ve genel his — sayı olarak değil, anlamıyla —, İlişki Karnesi türü, yorum oluşturulurken ve koçla tartışılırken seçilen kişinin boyut puanları, yakınlık ve romantik çerçeve bulguları, güvenlik işareti, değişimler ve kayıtlı anların toplu temaları ve eğilimleri, tartışırken okunan yorum, doğum gününe kalan gün, yaklaşan planların başlığı ve tarihi); **isteğe bağlı:** izin verdiysen konuşulan kişiyle son 20 anının metni (tarih, tür, his, açıklama) ve kişi notu, doldurduysan "Hakkımda" metnin. Kişisel notların hiç gönderilmez | Sana ilişkilerin hakkında öneride bulunmak | Sözleşmenin ifası (m. 5/2-c); yurt dışına aktarım için bkz. bölüm 6 | Sunucumuz (Supabase, AB) üzerinden Anthropic'e (ABD). Sunucumuzda saklanmaz, kayda geçirilmez. Tek yapay zekâ onayıyla açılır. |
| **Bildirdiğin yapay zekâ içeriği:** "Bildir"e bastığın koç yanıtının, karne yorumunun ya da sesle anlat kartının metni, seçtiğin neden, uygulama dili, zaman ve anonim kimliğin (metin dost adı içerebilir) | Uygunsuz, zararlı ya da yanlış yapay zekâ çıktısını incelemek ve düzeltmek | Meşru menfaat (m. 5/2-f); yalnız sen bildirince gönderilir | Supabase (AB), **şifreli** olarak saklanır ve en fazla 90 gün sonra silinir. Geliştiriciye giden e-postada (Resend, ABD) içerik bulunmaz; yalnız kaynak, neden ve zaman yazar. |
| **Abonelik bilgisi:** Premium durumu, plan, mağaza, deneme ve bitiş tarihi, satın alma kayıtları | Premium'u açmak, deneme hatırlatması, geri yükleme | Sözleşmenin ifası (m. 5/2-c) | RevenueCat (ABD), Supabase (AB) |
| **Ödeme bilgisi** | Satın alma | — | Yalnız Apple App Store ya da Google Play işler. Kart bilgin bize ve RevenueCat'e gelmez. |
| **Teknik kayıtlar:** IP adresi, istek zamanı, cihaz ve uygulama sürümü | Hizmetin güvenliği ve çalışması | Meşru menfaat (m. 5/2-f) | Hizmet sağlayıcılarımızın (Supabase, RevenueCat) güvenlik kayıtlarında, kendi saklama sürelerince |

Bu veriler yalnız tabloda yazan amaçlarla işlenir. Anlatımların ve dostlarının adları, senin
bildirdiğin bir içerik dışında, hiçbir yerde saklanmaz; yapay zekâ modeli eğitmek, test etmek ya da ürünü geliştirmek için kullanılmaz.

## 5. Dostlarının bilgileri

Uygulamaya eklediğin kişilerin bilgileri telefonunda durur. Sesle anlat özelliğinde yalnız **aktif
dostlarının adları** gönderilir; söylediğin adı doğru kişiyle eşleştirmek için gereklidir. Telefon numarası,
fotoğraf, doğum günü gibi başka bilgileri gönderilmez. Başkalarına dair anlattıklarında ölçülü olmanı ve
özel hayatlarına saygı göstermeni rica ederiz.

## 6. Yurt dışına aktarım

Yapay zekâ özellikleri ve abonelik altyapısı nedeniyle verilerin Türkiye dışına aktarılır:

- **Supabase** (sunucu ve veritabanı): Avrupa Birliği, İrlanda
- **Anthropic** (yapay zekâ): Amerika Birleşik Devletleri
- **RevenueCat** (abonelik yönetimi): Amerika Birleşik Devletleri
- **Resend** (sistem ve bildirim e-postaları; içerik taşımaz): Amerika Birleşik Devletleri

Aktarım KVKK m. 9 uyarınca standart sözleşme (ilgili sağlayıcılarla imzalanması ve Kişisel Verileri Koruma
Kurumu'na bildirilmesi süreci devam eder) ve bunların tamamlanmadığı durumlar için açık rızana dayanılarak yapılır. Yapay zekâ
özelliklerinden birini ilk kullandığında bu rıza, sağlık ve özel hayata dair yazdıklarının işlenmesine ilişkin
açık rızanla birlikte tek bir onayla sorulur; onay vermezsen yapay zekâ özellikleri çalışmaz, uygulamanın geri
kalanı aynen çalışır. Onayını Ayarlar'dan geri alabilirsin.

## 7. Saklama süreleri

- **Telefonundaki veriler:** sen silene kadar.
- **Anlatım metni, koç mesajları ve dostlarının adları:** sunucumuzda saklanmaz; istek işlendikten sonra
  bellekten silinir. Anthropic, ticari koşulları gereği API verilerini model eğitiminde kullanmaz ve
  girdi ile çıktıları genellikle 30 gün içinde siler. Kullanım politikası ihlali şüphesiyle otomatik
  güvenlik sistemlerince işaretlenen içerikler en fazla 2 yıl tutulabilir.
- **Bildirdiğin içerik:** şifreli saklanır ve en fazla 90 gün sonra otomatik silinir; daha önce silinmesini
  istersen bölüm 8'deki yoldan başvurabilirsin.
- **Kullanım kayıtları:** en fazla 13 ay. Abonelik bilgisi hizmet sürdükçe saklanır. Silinmesini
  istersen bölüm 8'deki yoldan başvurabilirsin. Mağazanın satın alma kayıtları Apple ve Google'ın kendi
  sürelerince tutulur.
- **Sunucudaki veriler:** Supabase'in veritabanı diski AES-256 ile şifrelenir; bağlantılar TLS ile korunur.
  Bildirilen içerik ayrıca uygulama düzeyinde (AES-256-GCM) şifrelenir.

## 8. Hakların ve başvuru

KVKK m. 11 uyarınca; verilerinin işlenip işlenmediğini öğrenme, bilgi isteme, amacını ve amaca uygun
kullanılıp kullanılmadığını öğrenme, aktarıldığı üçüncü kişileri bilme, eksik ya da yanlış işlenmişse
düzeltilmesini, silinmesini ya da yok edilmesini isteme, bunların aktarıldığı kişilere bildirilmesini
isteme, otomatik sistemlerle analiz sonucu aleyhine bir sonuç çıkmasına itiraz etme ve kanuna aykırı işleme
nedeniyle zarara uğradıysan giderilmesini isteme haklarına sahipsin.

Başvurunu **info@ghoso.app** adresine gönderebilirsin. Hesap olmadığı için seni tanıyabilmemiz adına başvuruna
uygulamadaki **Ayarlar → Hakkında** bölümünde görünen kullanıcı kimliğini eklemeni rica ederiz.
Başvurunu en geç 30 gün içinde ücretsiz yanıtlarız.
Telefonundaki verilere biz erişemeyiz; onları uygulamadan sen silebilirsin.

## 9. Çocuklar

Uygulama 18 yaşından küçükler için tasarlanmamıştır ve 18 yaşından küçüklerin kullanımına yönelik değildir.
18 yaşından küçük birinin bize veri ilettiğini öğrenirsek (ör. bir başvuru e-postasıyla) o veriyi sileriz.

## 10. Alt işleyenler

| Hizmet | Ne için | Nerede | Gizlilik politikası |
| --- | --- | --- | --- |
| Supabase | Sunucu, anonim oturum, kullanım ve abonelik kayıtları | AB (İrlanda) | supabase.com/privacy |
| Anthropic | Anlatımdan kayıt çıkarma (yapay zekâ) | ABD | anthropic.com/legal/privacy |
| RevenueCat | Abonelik durumu ve geri yükleme | ABD | revenuecat.com/privacy |
| Resend | Bildirim ve sistem uyarılarını geliştiriciye e-postayla iletmek (içerik taşımaz) | ABD | resend.com/legal/privacy-policy |
| Apple App Store | Ödeme, iOS konuşma tanıma (cihazda değilse) | — | apple.com/legal/privacy |
| Google Play / Google hesabı | Ödeme, Android konuşma tanıma (cihazda değilse), telefon yedeği (açıksa) | — | policies.google.com/privacy |

## 11. Değişiklikler

Bu metni ürün değiştikçe güncelleriz. Önemli bir değişiklik olursa (örneğin yeni bir veri türü ya da yeni
bir alıcı) uygulama içinde haber veririz ve gerekiyorsa onayını yeniden isteriz.
