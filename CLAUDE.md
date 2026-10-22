# Owleno — Claude talimatları

Çalışmaya başlamadan önce `docs/project-memory/README.md` dosyasını oku. Bu dosya, Claude ve Codex için ortak proje bağlamını içerir; Claude'a özgü kullanım notlarını burada tut.

## Çalışma kuralları

- Önemli bir değişiklikten önce mevcut durumu ve planı açıkla; uygulamaya geçmeden önce kullanıcının onayını bekle.
- Kullanıcı açıkça yetki vermedikçe commit, push veya yayın yapma; GitHub ayarlarını değiştirme ve veritabanı şemasına dokunma.
- Canlı `owleno.com` uygulamasını koru. Git dalları üzerinden eşgüdüm kur ve düzenleme öncesinde uzak depodaki son durumu kontrol et.
- Düzenleme yapmadan önce mevcut kodu ve yayın varsayımlarını incele. Çalıştırılmayan testleri başarılıymış gibi anlatma.
- Teknik tercihleri anlaşılır Türkçeyle açıkla; belirsizlikleri ve alternatifleri belirt.
- Kimlik bilgilerini, API anahtarlarını veya özel kullanıcı verilerini depoya koyma.

## Ortak çalışma

- GitHub'ı Codex ile ortak kod aktarım noktası olarak kullan. Bu Claude oturumunun Codex'i doğrudan çalıştırabildiğini varsayma; incelemeye açık bir dal, commit veya pull request üzerinden aktarım yap.
- Kalıcı kararları `docs/project-memory/README.md` dosyasında tut; önemli kararların tarihini ve gerekçesini yaz.
- Commit veya yayın öncesinde kullanıcıya somut farkı incelemesi için sun.
