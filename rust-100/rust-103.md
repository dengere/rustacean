---
layout: course
topic: Rust-100
subject: Rust'in Temelleri
subject_permalink: /rust-100/
title: Eşzamanlı Programlama (Concurrency)
permalink: /Rust-103/
category: course
sortorder: 300
excerpt: >-
  Bu kurs, Eşzamanlı programlama kavramlarını anlamak ve uygulamak için gereken bilgi ve becerileri kazandırmayı amaçlamaktadır. Teorik bilgiler ve uygulamalarla, iş parçacıklarını yönetme, veri paylaşımı ve senkronizasyon yöntemleri üzerine calisilacaktir.
overview: >-
  Eşzamanlı programlama, bir programın birden fazla işlemi aynı anda gerçekleştirme yeteneğini ifade eder. Bu kurs, bu konsepti etkili bir şekilde uygulamak için gerekli olan temel bilgileri sağlar. Katılımcılar, iş parçacıklarını oluşturma, yönetme ve senkronizasyon konularında derinlemesine bilgi edinerek, yüksek performanslı uygulamalar geliştirmeye yönelik pratik deneyimler kazanacaklardır. <br/><br/>
  Kurs boyunca, iş parçacıklarının nasıl oluşturulacağı, veri paylaşımının nasıl yönetileceği ve mesajlaşma yöntemlerinin nasıl uygulanacağı gibi konular ele alınacaktır. Ayrıca, eşzamanlı kodların test edilmesi ve performans optimizasyonu hakkında da bilgi sahibi olunacaktır. Katılımcılar, gerçek dünya senaryolarında eşzamanlı sistemler geliştirebilecek yetkinliğe ulaşacaklardır.
audiances:
- Rust 101 ve Rust 102 kurslarını tamamlamış olanlar
- Orta ve ileri düzey Rust programlama deneyimi olan yazılımcılar  
- Eşzamanlı programlama konusunda bilgi edinmek isteyen Rust geliştiricileri
goals: 
- Eşzamanlı programlamayi konseptlerini anlayacak  
- Rust ile iş parçacıkları oluşturma ve yönetme becerisi kazanacak
- Veri paylaşımı ve senkronizasyon yöntemlerini etkili bir şekilde kullanabilecek  
period: 30
---
##### Eşzamanlı Programlamaya Giriş  
   - Eşzamanlılık ve paralellik farkı  
   - Temel kavramlar  

##### Thread Yönetimi  
   - `std::thread` ile iş parçacıkları oluşturma  
   - Join ve spawn yöntemleri  

##### Veri Paylaşımı ve Senkronizasyon  
   - `Arc` ve `Mutex` kullanımı  
   - `RwLock` ile paylaşım yönetimi  

##### Message Passing  
   - `std::sync::mpsc` ile mesaj iletimi  
   - Üretici-tüketici modeli  

##### Async/Await vs. Thread-based Concurrency  
   - Farklar ve uygun kullanım senaryoları  

##### Eşzamanlı Kodların Test Edilmesi  
   - Deadlock ve race condition sorunlarını önleme  

##### Performans Optimizasyonu  
   - Lock-free veri yapıları ve atomik işlemler  

##### Proje Çalışması  
   - Eşzamanlı bir sistem geliştirme  

