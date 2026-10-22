# Owleno — ortak proje hafızası

Son gözden geçirme: 2026-10-22

Bu belge, Claude ve Codex için araçlardan bağımsız kalıcı proje bağlamıdır. Yalnızca depoyu kontrol edip doğrulanmış bilgileri kaydettikten sonra güncelle. Kimlik bilgilerini ve kişisel verileri bu dosyaya yazma.

## Ürün hedefi

Owleno; genel İngilizce öğrenimini ve YDS, YÖKDİL gibi sınavlara hazırlığı destekleyen bir eğitim platformudur. Hedef; öğrenme kalitesi yüksek, arayüzü profesyonel, özgün ve sevimli bir baykuş maskotu olan, oyunlaştırmayı ölçülü kullanan bir deneyim oluşturmaktır.

## Ürün alanları

- Ana uygulama ve öğrenme akışı
- Grafik arayüzü ve kullanıcı deneyimi
- Kelime, okuma, gramer ve konuşma
- Altyapı, güvenlik ve yayın süreci
- Test ve hata inceleme
- Telif ve içerik kaynağı araştırması
- Ortak geliştirme planı

## Depodaki doğrulanmış mevcut durum

- GitHub deposu: `https://github.com/xlamz/yds-hazirlik`
- Depo 2026-10-22 tarihinde herkese açık olarak görüntülendi.
- Görüntülenen varsayılan dal: `claude/github-pages-z2a9cu`.
- Deponun kökünde `index.html`, `README.md`, `CNAME`, `robots.txt`, `owl3d/` ve `test/` bulunuyor.
- `CNAME` dosyasında `owleno.com` yazıyor. Canlı alan adı 2026-10-22 tarihinde YDS Hazırlık giriş sayfasını gösterdi.
- README, tek dosyalı uygulamanın `yds-app/build.py` dosyasından üretildiğini söylüyor; incelenen herkese açık dalda bu kaynak yolu bulunamadı. Uygulama kodunu değiştirmeden önce asıl kaynağı doğrula.
- Yerel Codex çalışma kopyası `codex/owleno` dalında. Bu çalışma dalı GitHub'a gönderildi; varsayılan dala push yapılmadı.

## Ortak çalışma ve yayın güvenliği

- GitHub, Claude ile Codex arasındaki ortak kod aktarım noktasıdır. Claude ve Codex varsayılan olarak aynı canlı çalışma kopyasını paylaşmaz.
- Her kodlama oturumundan önce mevcut dalı ve uzak commit'leri kontrol et. Aynı dosyalarda eşzamanlı düzenleme yapmaktan kaçın; özellik dalları ve incelemeye açık farklar kullan.
- Kullanıcı açıkça onaylamadıkça varsayılan dala push yapma; GitHub Pages, DNS, Cloudflare, Supabase veya üretim ayarlarını değiştirme.
- `owleno.com` canlı kabul edilmelidir. Kaynak/derleme yolu ve yayın akışı anlaşılmadan kullanıcıya dönük dosyalarda değişiklik yapma.
- Bu belge başlangıç fotoğrafıdır; depo yayın ayarlarının veya Supabase durumunun kanıtı değildir.

## Araçlar ve varlıklar

- Kullanıcının Meshy AI aboneliği var ve 3D baykuş maskotu için kullanmayı planlıyor. Meshy API/MCP kimlik bilgisi ve API kredi durumu yapılandırılmadı veya doğrulanmadı.
- Kimlik bilgilerini yalnızca onaylı yerel gizli bilgi deposunda veya ortam değişkeninde sakla; Git'e ya da bu ortak notlara koyma.

## Karar günlüğü

Doğrulanmış kararları tarih, karar, gerekçe ve etkilenen dosya/hizmet bilgileriyle ekle. Tahminleri gerçek gibi kaydetme; çözümlenmemiş konuları “Açık sorular” bölümünde tut.

## Açık sorular

- Asıl düzenlenebilir kaynak nerede (`yds-app/build.py` veya başka bir konum) ve `index.html` nasıl üretiliyor?
- `owleno.com` sitesini şu anda hangi GitHub Pages iş akışı veya dal kuralı yayınlıyor?
- Canlı giriş akışında hangi Supabase hizmetleri ve şema kullanılıyor?
- Kullanıcı Claude.ai Projects mi, Claude Code mu, yoksa ikisini birden mi kullanıyor? Bağlantı seçenekleri buna göre değişir.
- Kullanıcı Meshy API erişimi mi istiyor (ayrı ön ödemeli API kredisi kullanır), yoksa Meshy web uygulaması üzerinden elle varlık üretmek yeterli mi?
