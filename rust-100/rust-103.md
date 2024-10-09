---
layout: course
topic: Rust-100
subject: Rust'in Temelleri
subject_permalink: /rust-100/
title: Eşzamanlı Programlama (Concurrency)
permalink: /rust-103/
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

# Giriş
   - *Eşzamanlılık ve Paralellik Arasındaki Farklar*
     - Teorik farklılıklar ve kavramsal açıklamalar  
     - Eşzamanlı programlamanın avantajları ve zorlukları  
     - Paralel programlamanın gerçek hayatta kullanıldığı yerler  
   - *Temel Kavramlar*  
     - İş parçacıkları, süreçler, paylaşılan bellek  
     - Durumsuz (stateless) ve durumlu (stateful) eşzamanlılık  
     - Yarış koşulu (race condition) ve deadlock kavramları  

# Thread Yönetimi
   - *`std::thread` ile İş Parçacıkları Oluşturma*
     - Temel iş parçacığı oluşturma ve kullanım senaryoları  
     - Gerçek hayat senaryolarından iş parçacığı kullanımı  
   - *Thread Join ve Spawn Yöntemleri*
     - İş parçacıklarının yönetimi: `join` ve `detach`  
     - İş parçacıklarının yaşam döngüsünü kontrol etme  

# Veri Paylaşımı ve Senkronizasyon
   - *`Arc` ve `Mutex`*
     - Paylaşılan verilerde senkronizasyon teknikleri  
     - `Arc` ve `Mutex` kullanarak veri paylaşımını yönetme  
   - *`RwLock` ile Paylaşım Yönetimi*
     - Okuma-yazma kilitlerinin kullanımı  
     - `RwLock` ile yüksek performanslı veri paylaşımı  

# Mesaj Geçirme (Message Passing)
   - *`std::sync::mpsc` ile Mesaj İletimi*
     - Üretici-tüketici modelini mesajlaşma ile yönetme  
     - Tek yönlü ve çok yönlü mesajlaşma mekanizmaları  
   - *Üretici-Tüketici Modeli*
     - Üretici-tüketici modelinin çalışma prensipleri  
     - Kuyruk tabanlı iş parçacığı yönetimi  

# Async/Await ve Thread Tabanlı Eşzamanlılık
   - *Farklar ve Uygun Kullanım Senaryoları*  
     - Async/await vs. thread tabanlı eşzamanlılık farkları  
     - Hangisini ne zaman kullanmalıyız?  
   - *Async ile Thread Yönetimi Karşılaştırması*
     - Performans ve kaynak kullanımı karşılaştırması  
     - Eşzamanlılık problemlerine farklı yaklaşımlar  

# Eşzamanlı Kodların Test Edilmesi
   - *Deadlock ve Race Condition Sorunlarını Önleme*
     - Yarış koşulu ve deadlock tespit yöntemleri  
     - Araçlar ve kütüphanelerle eşzamanlı kodları test etme  
   - *Araçlar ve Test Kütüphaneleri*
     - Rust’ta eşzamanlı kodları test etmek için kullanılan araçlar  

# Performans Optimizasyonu
   - *Lock-free Veri Yapıları ve Atomik İşlemler*
     - Lock-free veri yapıları kullanmanın avantajları  
     - Atomik işlemler
   - *Verimlilik İçin İpuçları*
     - Thread ve async performans optimizasyonu  
