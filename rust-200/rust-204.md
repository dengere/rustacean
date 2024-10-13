---
layout: course
topic: rust-200
subject_permalink: /rust-200/
permalink: /Rust-204/
sortorder: 400
documentstate: 1
subject: Rust Backend
title: Rust ile gRPC Uygulamaları
excerpt: >-
   Bu kurs, gRPC ve Protobuf kullanarak sistemler arasında hızlı, güvenli ve verimli iletişim kurmayı hedefleyen bir programdır. 
overview: >-
   Rust dilinin güçlü yanları ile gRPC uygulamaları geliştirmeyi ve streaming yöntemleriyle REST entegrasyonunu sağlamayı öğrenmek isteyen yazılımcılara yöneliktir. <br/>
   gRPC, sistemler arasında yüksek performanslı ve esnek iletişim sağlamayı amaçlayan bir açık kaynak protokolüdür. Bu kurs, Rust kullanarak gRPC’nin avantajlarını, Protobuf ile veri modelleme yöntemlerini ve streaming işlemlerini öğretir. REST entegrasyonu ve kimlik doğrulama konularına da odaklanarak, katılımcıların **gerçek dünyada uygulanabilir** projeler geliştirmelerini amaçlar.
audiances:
- Performans odaklı uygulama geliştiren yazılımcılar  
- Büyük veri veya yüksek trafikli uygulamalarda çalışan Rust geliştiricileri  
- Mikroservis mimarisi ve dağıtık sistemler üzerinde çalışan yazılımcılar
goals:
   - gRPC'nin avantajlarını ve dezavantajlarını anlayacak  
   - Protobuf ile veri modelleme yapacak  
   - Streaming** yöntemlerini uygulamayı öğrenecek  
   - Kimlik doğrulama ve güvenlik mekanizmalarını gerçekleştirecek  
   - gRPC ve REST API entegrasyonu yapacaktır  
methodology:
- 18 saat  
- 3 hafta boyunca 3’er saatlik oturumlar
- Kurslar Online yapılacak  
- Ders saatleri dışında, ödevler ve proje bazlı tartışma oturumları
---

##### gRPC Nedir?
- gRPC'nin Mimarisi ve Temel Bileşenleri  
- gRPC’nin Avantajları ve Dezavantajları  
- Hangi senaryolarda gRPC kullanılmalı?  

##### Protobuf ile Veri Yapıları
- Protobuf Nedir ve Nasıl Çalışır?  
- *prost* ile Protobuf Kullanımı
- Protobuf Dosyası Yazma ve Derleme  
- Protobuf’un Performans Avantajları  

##### gRPC ve REST Farkları ve Entegrasyonu
- Rust ile REST API’lerinin gRPC ile Entegrasyonu  
- *gRPC Gateway* Kullanımı  
- REST ve gRPC Arasındaki Veri Dönüşüm Stratejileri  

##### Streaming Yöntemleri
- gRPC’de *Streaming Türleri*
  - Unary  
  - Server-streaming  
  - Client-streaming  
  - Bi-directional (Bidi) streaming  
- *tonic* Streaming Uygulamalarının Geliştirilmesi

##### Kimlik Doğrulama ve Güvenlik
- gRPC’de *Kimlik Doğrulama Yöntemleri*
- TLS ve Şifreleme ile Güvenlik Sağlama  
- gRPC Güvenlik Mekanizmalarının Uygulanması  

##### Hata Yönetimi ve Performans
- *Status ve tonic* ile Hata Yönetimi 
- Retry ve Fallback Mekanizmaları  
- Rust ile Asenkron Programlama ve Concurrency  (*)
- Performans İyileştirme Teknikleri 
   - Bağlantı havuzu
   - Protobuf optimizasyonları



Rust ile Asenkron Programlama ve Concurrency, konu basligi Resut Temel Programlama serisinde birer kurs olarak hazirlanmistir. Bu bolumde giris seviyesinde bilgi ve ornekler verilecektir.