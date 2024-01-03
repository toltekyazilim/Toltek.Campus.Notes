## 1. Genel iyileştirmeler
- Sistem genelinde kullanılmayan kaynakların serbest bırakıldığı temizlik ve performans iyileştirmeleri yapıldı
    - Artık kullanılmayan veritabanı tablo, sütun ve prosedürleri temizlendi
    - SQL Tuning ile performans iyileştirmeleri ve Indexleme yapıldı
- HtmlEditor'üne MathML ve resim yükleme desteği eklendi

## 2. Sisteme Giriş Uygulamasında yapılan iyileştirmeler
- Kullanıcı girişinde ReturnUrl desteği eklendi (daha iyi bir açıklama eklenmeli)

## 3. Yönetim Uygulamasında yapılan iyileştirmeler
- Proliz toplu öğrenci eşitleme yaparken timeout hatasına düşmemesi için Cache yapısı değiştirildi (1 saatten uzun süre sürecek şekilde güncellendi)
- Önbellek ayarları dağılmış (redis vb) olmayan kurulumlarda ayarlar bölümünde yapılan değişikliklerin diğer uygulamalara anında yansıması için MessageBus servisi devreye alındı.
- Ayarlar bölümüne Proliz (OBS) sayfası eklendi
- Ayarlar bölümüne Kion (OBS) sayfası eklendi
- Ayarlar bölümüne Mergen (OBS) sayfası eklendi
- Ayarlar bölümüne Subu-BYS (OBS) sayfası eklendi

## 4. Eğitmen Uygulamasında yapılan iyileştirmeler
- Eğitmenler soru havuzunda birbirinin sorularını görmeseler de, sınava eklenmiş sorular bölümünden kendina ait olmayan soruyu değiştirebiliyordu, bu eksik düzeltildi.
- İçerik eklerken youtube embed özelliği eklendi. Link olarak eklenen içeriğin youtube videosu olduğunu algılayıp youtube playerda oynatmasını sağlar. (resim olmalı)
- Sınav notlarını aktar sayfasında aktarımı başlatan kişinin bilgileri kaydedilmeye başlandı.
- Sınav notlarını aktar sayfasında aktarım yapılırken aktarımı yapılamayan kayıtlar işlem sonunda gösterilecek şekilde loglama işlevi eklendi. (resim olmalı)
- Sınav detay sayfası eklendi (resim olmalı)
- Ödev toplu değerlendirme sayfası eklendi (resim olmalı)
- Aktivie detay sayfaları toplu olarak elden geçirildi. Ekranlar genel bir standarta uyarlandı.Tüm detay sayfalarında aşağıdaki maddeler standart hale getirildi.
    - Standart bilgi tablosu
    - Yayınla - Askıya Al butonları
    - Katılım pasta grafiği
    - İlerleme yüzdesi
    - Günlük katılım-ilerleme çizgi grafiği (dönem başından bugüne)
    - Ödev ve Sanal Sııf için dosyalar listesi
- İçerik modülünde Text/Markdown/Html içerik desteği eklendi. Eğitmen dosya yada link eklemek içinde doğrudan editör arayıcılığı ile metin içeri de ekleyebilir. Karakter limiti olmayacak şekilde konfigüre edildi.
- İçerik modülünde dosya yada içerikler için revizyon desteği eklendi
- Eğitim Dosya Havuzu sayfası eklendi


## 5. Öğrenci Uygulamasında yapılan iyileştirmeler
- Öğrencilerin Bigbluebutton sanal sınıflarına katıldığı süreleri kaydeden servis eklendi.
- Öğrencilerin Zoom sanal sınıflarına katıldığı süreleri kaydeden servis eklendi.
- Öğrenci sınava girdiğinde sınav soru sayısı ile ekrana yüklenen soru sayısı eşit değilse mesaj gösterip sayfayı yenileyecek fonksiyon eklendi (resim olmalı)
- Video Player'a ilerleme takip desteği tekrar eklendi
- Öğrenci mobil cihazla ödev teslim ederken birden fazla dosya seçince oluşan hata giderildi

## 6. Canlı Yayın Uygulamasında yapılan iyileştirmeler
- Canlı Yayın uygulamasında herhangi bir değişiklik yapılmadı


