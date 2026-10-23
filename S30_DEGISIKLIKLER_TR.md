# S30 – Supabase gönderme/alma ve manuel eşitleme

S29 baz alınmıştır. `lib/main.dart` dışında uygulama kaynak dosyaları değiştirilmedi.

- Ayarlar > Senkronizasyon Durumu: Telefon ↔ PC + Supabase ve Telefon ↔ Supabase manuel butonları.
- Ortak kayıtlar otomatik 10 saniyede bir eşitlenir. Kasa/stok 3 saniyelik mevcut yenilemesi değiştirilmedi.
- Supabase HTTP/giriş hataları Ayarlar'da görünür.
- Supabase şifresi ayarlar kaydedilirken güvenli depoya yazılır.
- Başarılı bekleyen olaylar doğru olay nesnesine göre listeden çıkarılır.

NOT: Flutter derleme ve gerçek cihaz testi yapılmadı. Önce çalışan APK'yı saklayın. SQL Server yazma işlemi eklenmedi.
