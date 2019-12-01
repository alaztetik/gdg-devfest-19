# Express Session Backed by Hazelcast Cloud

* Hüseyin Babal

## Notlar

1. Hazelcast: `in-memory data grid`, `distributed cache`, `distributed computing`
2. `session`: sunucu tarafında kullanıcı bilgisi saklama, login ile
3. `cookie data`
4. birden fazla sunucu varsa problem oluşabiliyor
5. `load balancer`: sunuculara dağıtımı yapan araç
6. birden fazla sunucuda kullanıcı verisi saklamada ortaya çıkan sorunun çözümü:
   1. `sticky session`
   2. `central session store`
7. NodeJS module: `express session` (from npm)
8. `cloud.hazelcast.com`, ücretsiz cluster açabiliyorsun
9. uygulama için kullanılan teknolojiler (bunları power user yetkisi ile yapmalı):
   1. NodeJS
   2. Express
   3. Express Sessions
   4. Hazelcast store
10. npm modules to install:
    1. `express`
    2. `body-parser`
    3. `cookie-parser`
    4. `ejs`
11. `template engine` 
12. `app.use` kullanımı `middleware` olarak sınıflandırılıyor
13. `Twitch` online coding çok yararlı oluyor
14. `GitHub Feed` yararlı
15. `HackerRank` pratik için çok yararlı bir site
16. Hazelcast'te remote çalışıyor