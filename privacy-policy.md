---
title: Meal Match – Gizlilik Politikası / Privacy Policy
---

# Meal Match – Gizlilik Politikası

**Son güncelleme:** 13 Kasım 2026
**Geliştirici:** MegaSpirits (Serhat Yokuşoğlu), Ankara, Türkiye
**İletişim:** syokusoglu1@gmail.com

Meal Match ("Uygulama"), aynı şehirde aynı yemeği canı çeken yetişkinleri tanıştıran bir sosyal/flört uygulamasıdır. Bu politika hangi verileri topladığımızı, neden topladığımızı ve haklarınızı açıklar. Uygulamayı kullanarak bu politikayı kabul etmiş olursunuz.

## 1. Yaş sınırı
Meal Match yalnızca **18 yaş ve üzeri** kişiler içindir. Kayıt sırasında doğum tarihi istenir; 18 yaşından küçükler hesap oluşturamaz. 18 yaşından küçük birine ait olduğunu öğrendiğimiz hesapları sileriz.

## 2. Topladığımız veriler

| Veri | Neden | Nerede saklanır |
|---|---|---|
| Google hesabı kimliği ve e-posta adresi (Google ile Giriş) | Hesap oluşturma ve oturum açma | Google Firebase Authentication |
| Görünen ad, doğum tarihi (profilde yalnızca yaş görünür), kısa biyografi | Profilinizi diğer kullanıcılara göstermek | Google Cloud Firestore |
| Profil fotoğrafları (3–4 adet) | Profilinizde gösterilir | Google Cloud Storage for Firebase |
| **Yaklaşık konum → yalnızca şehir adı** | Sizi sadece aynı şehirdeki kişilerle eşleştirmek | Firestore (yalnızca şehir; **koordinatlar sunucuya gönderilmez ve saklanmaz**) |
| Günlük "Bugün ne yemek istersin?" cevabınız | Aynı şeyi isteyenlerle eşleştirme | Firestore |
| Beğeni / beğenmeme / süper beğeni, eşleşmeler | Eşleştirme hizmeti | Firestore |
| Eşleştiğiniz kişilerle mesajlarınız | Sohbet hizmeti | Firestore |
| Şikâyet ve engelleme kayıtları | Topluluk güvenliği | Firestore |
| Reklam verileri (reklam kimliği, cihaz ve kullanım bilgisi) | Ücretsiz uygulamayı reklamla desteklemek | Google AdMob (bkz. Bölüm 4) |

Konum izni yalnızca **yaklaşık (coarse) konum** içindir ve yalnızca uygulama açıkken kullanılır. Arka planda konum toplamayız. Fotoğraf seçmek için Android'in fotoğraf seçicisi kullanılır; galerinize genel erişim istemeyiz.

Firebase Analytics kullanmıyoruz (uygulamada kapalıdır).

## 3. Verilerin paylaşımı
- **Diğer kullanıcılar:** Aynı şehirdeki kullanıcılar profilinizi (ad, yaş, şehir, biyografi, fotoğraflar) ve günlük yemek cevabınızı görebilir. Mesajları yalnızca eşleştiğiniz kişi görür.
- **Hizmet sağlayıcılar:** Google LLC (Firebase: kimlik doğrulama, veritabanı, depolama, sunucu fonksiyonları; AdMob: reklam). Veriler Avrupa Birliği (Firestore, eur3) ve ABD (fotoğraf depolama) bölgelerindeki Google sunucularında tutulur.
- Verilerinizi **satmayız**. Yasal zorunluluk halinde yetkili makamlarla paylaşabiliriz.

## 4. Reklamlar (Google AdMob)
Uygulama Google AdMob ile banner, geçiş ve ödüllü reklamlar gösterir. AdMob, reklam kimliğinizi ve cihaz bilgilerinizi kişiselleştirilmiş veya kişiselleştirilmemiş reklam için kullanabilir. Ayrıntılar: https://policies.google.com/technologies/ads . Android Ayarlar > Google > Reklamlar bölümünden reklam kimliğinizi sıfırlayabilir veya silebilirsiniz. Ödüllü reklam izlediğinizde, ödülü doğrulamak için Google'ın sunucusu bize bir doğrulama bildirimi gönderir.

## 5. Saklama süresi
Verileriniz hesabınız açık olduğu sürece saklanır. Hesabınızı sildiğinizde profiliniz, fotoğraflarınız, günlük cevaplarınız, beğenileriniz, eşleşmeleriniz ve mesajlarınız silinir. Güvenlik amaçlı şikâyet kayıtları en fazla 12 ay tutulabilir. Ayrıntılar: [Hesap ve Veri Silme](account-deletion.md).

## 6. Güvenlik
Tüm bağlantılar şifrelidir (HTTPS/TLS). Veritabanı erişimi Firebase Güvenlik Kuralları ile sınırlandırılmıştır: kullanıcılar yalnızca izin verilen verileri okuyabilir, yalnızca kendi verilerini değiştirebilir.

## 7. Haklarınız (KVKK / GDPR)
Verilerinize erişme, düzeltme, silme, işlemeye itiraz etme ve veri taşınabilirliği haklarına sahipsiniz. Başvuru için: syokusoglu1@gmail.com. 30 gün içinde yanıt veririz.

## 8. Kullanıcı içeriği ve güvenlik
Uygunsuz profil veya mesajları uygulama içinden **şikâyet edebilir** ve kullanıcıları **engelleyebilirsiniz**. Şikâyetleri inceler, kuralları ihlal eden hesapları kapatırız.

## 9. Değişiklikler
Bu politikayı güncelleyebiliriz; önemli değişiklikleri uygulama içinde duyururuz. Güncel sürüm her zaman bu sayfadadır.

---

# Meal Match – Privacy Policy (English)

**Last updated:** November 13, 2026
**Developer:** MegaSpirits (Serhat Yokuşoğlu), Ankara, Türkiye
**Contact:** syokusoglu1@gmail.com

Meal Match ("the App") connects adults in the same city who are craving the same food. This policy explains what we collect, why, and your rights.

**Age:** The App is for users **18 and older** only. Accounts of minors are deleted.

**Data we collect:**
- Google account ID and email (Google Sign-In) – account and login (Firebase Authentication).
- Display name, birth date (only your age is shown), short bio – your public profile (Cloud Firestore).
- 3–4 profile photos – shown on your profile (Cloud Storage for Firebase).
- **Approximate location, converted on your device to a city name only** – matching people in the same city. Coordinates are never sent to or stored on our servers. Location is used only while the App is open; no background location.
- Daily "What do you want to eat today?" answer, likes/passes/super likes, matches, chat messages with your matches, reports and blocks.
- Advertising data (advertising ID, device and usage info) collected by Google AdMob.

We do not use Firebase Analytics. Photos are chosen with the Android photo picker; we do not request broad gallery access.

**Sharing:** Other users in your city can see your profile and daily food answer; messages are visible only to your match. Service providers: Google LLC (Firebase, AdMob). Data is stored on Google servers in the EU (Firestore, eur3) and the US (photo storage). We do not sell your data. We may disclose data when legally required.

**Ads:** Google AdMob shows banner, interstitial and rewarded ads and may use your advertising ID. See https://policies.google.com/technologies/ads . You can reset or delete your advertising ID in Android Settings > Google > Ads.

**Retention & deletion:** Data is kept while your account exists. Deleting your account removes your profile, photos, answers, likes, matches and messages. Safety reports may be kept for up to 12 months. See [Account & Data Deletion](account-deletion.md).

**Security:** All traffic is encrypted (HTTPS/TLS). Database access is restricted by Firebase Security Rules.

**Your rights (GDPR / KVKK):** access, correction, deletion, objection and portability. Contact syokusoglu1@gmail.com; we reply within 30 days.

**User safety:** You can report and block users inside the App. We review reports and remove violating accounts.

**Changes:** We may update this policy; the current version is always on this page.
