# Not İstasyonu — Bildirim + Admin Sistemi

## 1. Supabase
1. Authentication > Providers içinden Anonymous Sign-Ins'i aç.
2. İlk yönetici hesabını Authentication > Users üzerinden oluştur.
3. `supabase-admin.sql` dosyasını SQL Editor'da çalıştır.
4. Dosyanın en altındaki ilk-admin INSERT satırını kendi e-posta adresinle açıp bir kez çalıştır.

## 2. Özellikler
- Tek 🔔 bildirim kutusu: herkese gönderilen duyurular ve kişiye özel mesajlar aynı yerde görünür.
- Okunmamış mesaj sayısı yalnızca 🔔 ikonunda görünür.
- Yönetici panelinden herkese veya seçilen kullanıcıya mesaj gönderilebilir.
- Yönetici panelinden istediğin kullanıcıya admin yetkisi verilebilir veya kaldırılabilir.
- Bildirimler 15 saniyede bir yenilenir.

## 3. GitHub Pages
Yeni `index.html`, `manifest.webmanifest`, `sw.js` ve `icons/` dosyalarını mevcut repository'ye yükle. `supabase-admin.sql` dosyasını GitHub'a yüklemen gerekmez; yerelde saklamak daha iyi.
