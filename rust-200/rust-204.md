---
layout: course
topic: rust-200
title: Rust ile gRPC
subject: Rust Backend
subject_permalink: /rust-200/
permalink: /Rust-204/
sortorder: 400
documentstate: 1
excerpt: >-
   gRPC ve Protobuf ile sistemler arasında hızlı, güvenli ve verimli iletişim sağlamak için tasarlanmış bir kurstur.
overview: >-
   Google tarafından geliştirilen bu açık kaynak protokol gRPC (Google Remote Procedure Call), sistemler arasında yüksek performanslı, esnek ve güvenilir iletişim sağlamayı hedefler.
   Bu kurs, Rust ile gRPC'nin avantajlarını ve kullanımını kapsamaktadır. Streaming özellikleri ve REST ile entegrasyonu ele alınırken, Protobuf ile veri modelleme de önemli bir konu olarak işlenmektedir. Rust dilinin güçlü yönleriyle gRPC uygulamalarını nasıl geliştirebileceğinizi öğreneceksiniz.
audiances:
   - Performans odaklı uygulama geliştiren yazılımcılar
   - Büyük veri ve yüksek trafikli uygulamalar üzerinde çalışan Rust geliştiricileri
goals:
  - gRPC’nin avantajlarını anlayacak,
  - Rust kullanarak Protobuf ile veri modelleme yapacak,
  - Streaming yöntemlerini Rust ile uygulayacak,
  - gRPC kimlik doğrulama mekanizmalarını uygulayacaktir.
methodology:
   - 30 saat,
   - 3'ser saatlik oturumlar ile 5 hafta,
   - Online ve
   - Ders saatleri dışında etkileşimli ödevler ve ödev tartışmaları.
---

#### gRPC Nedir?
   - gRPC mimarisi ve temel bileşenler
   - gRPC’nin avantajları

#### gRPC ve REST Farkları
   - gRPC ve REST arasındaki temel farklar
   - Rust ile REST API'lerinin gRPC ile entegrasyonu

#### Protobuf ile Veri Yapıları
   - Protobuf nedir ve nasıl çalışır?
   - Rust ile Protobuf kullanımı (prost kütüphanesi)
   - Protobuf dosyası yazma ve derleme

#### Streaming
   - Streaming yöntemleri:
     - Unary
     - Server-streaming
     - Client-streaming
     - Bidi-streaming
   - Rust ile streaming uygulamaları geliştirme (tonic kütüphanesi)

#### gRPC Kimlik Doğrulama
   - gRPC'de kimlik doğrulama yöntemleri(*)
   - Token tabanlı kimlik doğrulama uygulamaları(*)
   - Rust ile kimlik doğrulama mekanizmalarının uygulanması(*)

#### REST ile Entegrasyon
   - gRPC Gateway kullanımı
   - Rust ile REST ve gRPC entegrasyonu sağlama yöntemleri