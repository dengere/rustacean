---
layout: course
topic: rust-200
title: Rust ile  SQL - NoSQL
period: 36
subject: Rust Backend
subject_permalink: /rust-200/
permalink: /Rust-202/
excerpt: >- 
    Bu program, SQL ve NoSQL veri tabanlarını kullanarak modern uygulamalar geliştirmek isteyen Rust geliştiricileri için kapsamlı bir yol haritası sunuyor. ORM kullanımıyla , veri tabanı bağımsız bir yaklaşım benimsenerek esnek ve sürdürülebilir çözümler oluşturulabilecek.
overview: >-
    Katılımcılar, SQL ve NoSQL arasındaki farkları öğrenerek, Object-Relational Mapping (ORM) kavramını ve Rust’ta popüler ORM araçlarını (Diesel, SeaORM gibi) keşfedeceklerdir.Rust ile SQL entegrasyonu üzerinde durulacak ve PostgreSQL kullanarak CRUD uygulamaları geliştirilecektir. NoSQL temelleri ve MongoDB entegrasyonu ile katılımcılar, modern veri yönetimi tekniklerini uygulamalı olarak öğrenme imkanı bulacaklardır. Ayrıca, ORM kullanarak SQL ve NoSQL veri tabanları arasında veri geçişi yapmayı, veri güvenliğini sağlamak için gerekli önlemleri almayı ve test stratejilerini uygulamayı öğreneceklerdir. Bu kurs, katılımcıların veri tabanı programlama konusundaki bilgi ve becerilerini geliştirmeyi hedeflemektedir.
sortorder: 200
audiances:
    - Temel Rust Bilgisine Sahip Geliştiriciler
    -  Veri tabanı yönetimi ve uygulama geliştirme süreçlerine ilgi duyan, özellikle SQL ve NoSQL sistemlerini öğrenmek isteyenler.
goals:
    - SQL ve NoSQL veri tabanları arasındaki temel farkları anlayarak, her iki tür veri tabanının kullanım senaryolarını belirleyebilecek.
    - Rust programlama dili ile SQL entegrasyonu yaparak, Diesel kütüphanesi aracılığıyla CRUD uygulamaları geliştirebilecek.
    - NoSQL veri tabanları, özellikle MongoDB ile çalışarak veri modelleme ve yönetimi konularında pratik bilgi edinecek.
    - ORM (Object-Relational Mapping) kavramını kullanarak, veri tabanı bağımsız veri modelleri oluşturmak ve veri güvenliğini sağlamak için gerekli önlemleri alabilecek.
documentstate: 0
---

# Temel Kavramlar
   - Veri Tabanlarının Tanımı ve Önemi
   - SQL ve NoSQL Arasındaki Farklar
   - ORM (Object-Relational Mapping) Nedir?
     -  ORM’in Avantajları ve Dezavantajları
     -  Rust'ta Popüler ORM Araçları (Diesel, SeaORM, etc.)

# SQL Tabanlı Veri Tabanlarıyla Çalışmak
   - Rust ile SQL Entegrasyonu
      - Diesel Kütüphanesi ile Çalışma
      - Diesel ile Veri Tabanı Bağlantısı Kurma
      - Tabloları ORM ile Modelleme
   - PostgreSQL İle Uygulama Geliştirme
      - CRUD Uygulaması Geliştirme
      - Diesel ile Transaction Yönetimi

# NoSQL Veri Tabanlarıyla Çalışmak
   - NoSQL Temelleri
      - NoSQL Mimarisi ve Veri Modelleme
      - NoSQL Türleri
   - Rust ile NoSQL Entegrasyonu
      - Rust’ta MongoDB CRUD İşlemleri
      - MongoDB ile CRUD Uygulaması Geliştirme

# ORM ile SQL ve NoSQL Arasında Geçiş
   - ORM ile SQL ve NoSQL Veri Modellerini Yönlendirme
      - Veri Tabanı Bağımsız ORM Modelleri
      - ORM Kullanarak SQL ve NoSQL Veri Tabanları Arasında Veri Geçişi
   - Çok Katmanlı Mimari ile Veri Tabanı Yönetimi
      - Repository Pattern
      - Servis 

# Güvenlik ve Test
   - Veri Güvenliği
      - SQL ve NoSQL’de Veri Güvenliği (Şifreleme, Erişim Yönetimi)
   - Test ve Hata Ayıklama
      - Unit Test ve Integration Testler
      - ORM ile Test Stratejileri

