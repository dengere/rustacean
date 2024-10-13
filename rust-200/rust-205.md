---
layout: course
topic: rust-200
subject_permalink: /rust-200/
permalink: /Rust-205/
sortorder: 500
documentstate: 1
subject: Rust Backend
title: Olay Tabanlı Mimariler
excerpt: >-
   Katılımcılara Rust ile olay tabanlı mimarilerin uygulamasını öğretmeyi amaçlar. Katılımcılar, Kafka ve RabbitMQ gibi asenkron mesajlaşma sistemleri kullanarak gerçek dünya senaryolarında bu teknolojilerin nasıl kullanılacağını öğrenir.  
overview: >-
   Kurs boyunca katılımcılar, Rust ekosisteminde yaygın olarak kullanılan mesajlaşma sistemleriyle olay tabanlı mimarilerin temellerini ve kullanımını öğrenecektir. Kafka ve RabbitMQ ile asenkron uygulama geliştirme üzerine yoğunlaşan bu kurs, hata yönetimi, mesaj kurtarma stratejileri ve olay tabanlı mimari kalıplarını içerir.
audiances:
- Kafka ve RabbitMQ gibi mesajlaşma sistemlerini projelerinde etkin bir şekilde kullanmak isteyen yazılım geliştiricileri.  
- Asenkron sistemler ve yazılım mimarisi konularında güncel teknikleri öğrenerek profesyonel becerilerini geliştirmek isteyen mühendisler.  
goals:
- Rust ile asenkron mesajlaşma sistemlerinin temellerini öğrenmiş olacak,  
- Kafka ve RabbitMQ kullanarak yüksek performanslı uygulamalar geliştirecek,  
- Olay tabanlı mimarilerin kalıplarını ve pratik kullanımını kavrayacak,  
- Hata yönetimi ve mesaj kurtarma stratejilerini Rust ile uygulayabilecektir.  
methodology:
- 72 saat  
- 8 hafta boyunca haftada 9 saat (3 oturum x 3 saat)  
- Online eğitim
- Kurs dışındaki saatlerde etkileşimli ödevler ve tartışma oturumları  
---

##### Entegrasyon
- Kafka
- RabbitMQ

##### Hata Yönetimi ve Mesaj Kurtarma
- Hata Yönetimi Stratejileri
- Mesaj kaybı Yönetimi
- Mesaj saklama ve kurtarma

##### Olay Tabanlı Mimari
- Olayların yönetimi ve kullanım senaryoları  
- Olay tabanlı mimarilerin avantajları ve dezavantajları  

##### Kullanılan Kalıplar

- Event Sourcing (ES)
   - Tanım ve Amaç
   - Avantajları ve Dezavantajları
   - Rust ile Uygulama
     - Rust ile *Event Store* oluşturma  
     - Olayların işlenmesi ve yeniden oynatılması  

- Command Query Responsibility Segregation (CQRS)
   - Tanım ve Temel Fikir
   - Avantajları ve Kullanım Alanları
   - Rust ile Uygulama
     - CQRS modeline uygun *komut ve sorgu servisleri* geliştirme  
     - Kafka ile veri aktarımı ve işleme  

- Event-Driven Architecture (EDA)
   - Tanım
   - Avantajları ve Kullanım Alanları
   - Rust ile Uygulama
     - RabbitMQ ile *olay tabanlı mesajlaşma sistemi* geliştirme  
     - Event Producer ve Event Consumer yapılarının oluşturulması  

- Saga Pattern
   - Tanım ve Kullanım Amacı
   - Avantajları ve Sınırlamaları
   - Rust ile Uygulama
     - Saga Pattern kullanarak *dağıtık işlem yönetimi*
     - RabbitMQ veya Kafka ile Saga koordinasyonu  

- Publish/Subscribe Model
   - Tanım ve Kullanım Alanları 
   - Avantajları ve Dezavantajları
   - Rust ile Uygulama
     - Kafka ve RabbitMQ kullanarak *Pub/Sub yapısının kurulması*
     - Mesajların dinamik olarak yönetimi ve gecikme optimizasyonları  

##### Proje ve Uygulamalar
- Proje geliştirme çalışmaları: Kafka veya RabbitMQ tabanlı asenkron sistemler  
- Geri bildirim oturumları: Ödevlerin ve projelerin tartışılması  

