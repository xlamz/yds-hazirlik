# Owleno — Codex talimatları

Projede değişiklik yapmadan önce `docs/project-memory/README.md` dosyasını oku. Ürünle ilgili kalıcı bilgileri ve ortak kararları orada tut; araca özgü çalışma kurallarını bu dosyada tut.

## Çalışma kuralları

- Önemli bir değişiklikten önce mevcut durumu ve planı açıkla; uygulamaya geçmeden önce kullanıcının onayını bekle.
- Kullanıcı açıkça yetki vermedikçe commit, push veya yayın yapma; GitHub ayarlarını değiştirme ve veritabanı şemasına dokunma.
- Canlı `owleno.com` uygulamasını koru. `codex/*` dalında çalış ve kullanıcı istemedikçe bu dalı push etme.
- Düzenleme yapmadan önce mevcut kodu ve yayın varsayımlarını incele. Çalıştırılmayan testleri başarılıymış gibi anlatma.
- Teknik tercihleri anlaşılır Türkçeyle açıkla; belirsizlikleri ve alternatifleri belirt.
- Kimlik bilgilerini, API anahtarlarını veya özel kullanıcı verilerini depoya koyma.

## Ortak çalışma

- GitHub'ı Claude ile ortak kod aktarım noktası olarak kullan. Düzenleme öncesinde dalı ve commit durumunu kontrol et; diğer aracın çalışma alanının eşitlendiğini varsayma.
- Kalıcı kararları `docs/project-memory/README.md` dosyasında tut; önemli kararların tarihini ve gerekçesini yaz.
- Commit veya yayın öncesinde kullanıcıya somut farkı incelemesi için sun.
