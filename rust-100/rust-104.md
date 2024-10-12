---
layout: course
topic: Rust-100
subject: Rust'in Temelleri
subject_permalink: /rust-100/
title: Paralel Programlama (Parallelism)
permalink: /rust-104/
category: course
sortorder: 400
excerpt: >-
   Bu kurs, paralel programlama yöntemlerini anlamak ve uygulamak için gerekli bilgi ve becerileri kazandırmayı hedefler. Teorik bilgiler ve uygulamalarla, iş parçacıkları ve görev dağılımı üzerinde odaklanılacaktır.
overview: >-
   Paralel programlama, birden fazla işlemin aynı anda gerçekleştirilmesini sağlamak için gerekli olan teknikleri içerir. Bu kurs, bu teknikleri etkili bir şekilde kullanabilmek için gereken temel bilgileri sağlar. Katılımcılar, iş parçacıklarıyla paralel işlem yapma, görevleri bölümlendirme ve verimlilik optimizasyonu konularında derinlemesine bilgi edineceklerdir.
   <br/><br/>
   Kurs süresince, katılımcılar paralel programlamada karşılaşabilecekleri senkronizasyon sorunlarını ve çözümlerini öğrenecekler. Ayrıca, performans analizi ve hata ayıklama gibi konulara da değinilecektir. Gerçek dünya uygulamalarında paralel sistemler geliştirme yetkinliği kazanacaklardır.
goals: 
- Paralel programlama tekniklerini anlayip kullanabilecek.
- Rust ile paralel iş parçacıkları oluşturma ve yönetme becerisi kazanacak
- Performans optimizasyonu ve senkronizasyon sorunlarını çözme yetkinliği elde edecek.
audiances:
- Rust 101 ve Rust 102 kurslarını tamamlamış olanlar
- Orta ve ileri düzey programlama Rust deneyimi olan yazılımcılar  
- Paralel programlama konusunda bilgi edinmek isteyen Rust geliştiricileri  
prerequests:
  - Rust 102’yi tamamlamış olmak veya eşdeğer bir bilgiye sahip olmak.
  - Rust'ın sahiplik, borçlanma ve ömür süreleri gibi temel kavramlarına hâkim olmak.
methodology:
    - 30 saat,
    - 3'ser saatlik oturumlar ile 5 hafta,
    - Online ve
    - Ders saatleri dışında etkileşimli ödevler ve ödev tartışmaları.

period: 30
---


##### Giriş
   - ##### *Paralellik ve Eşzamanlılık Farkı*
      - Eşzamanlılık (Concurrency) ve paralel programlama ve kavramlarının tanımı
      - Her iki paradigmanın avantajları, dezavantajları ve kullanım alanları
   - ##### *Temel Kavramlar*  
     - Thread, işlem (process), ve görev (task) arasındaki farklar
     - CPU, çekirdek ve multi-core işlemciler hakkında bilgi
     - Paralel programlama modelleri ve frameworkler hakkında genel bakış

#####  Thread Yönetimi ve Görev Dağılımı
   - ##### *`std::thread::spawn` ile Paralel İş Parçacıkları*
     - thread’ler nasıl başlatılır ve yönetilir
     - `std::thread::spawn` ile iş parçacıklarının başlatılması
     - Thread'lerin yaşam döngüsü ve kaynak yönetimi
   - ##### *Görevlerin Bölümlendirilmesi (Chunking, Striding)*
     - Görevlerin verimli bir şekilde bölümlendirilmesi (chunking) teknikleri
     - Striding ile görevlerin iş parçacıklarına dağıtılması
     - Paralel görev dağılımı stratejileri

#####  Veri Paylaşımı ve Senkronizasyon
   - ##### *`Arc`, `Mutex`, ve Atomik İşlemler*
     - `Arc` ve `Mutex` kullanarak veri paylaşımı ve senkronizasyon
     - Paralel iş parçacıkları arasında veri tutarlılığı sağlama
     - Atomik işlemler ve veri yarışını önleme yöntemleri
     - Performans üzerinde `Arc` ve `Mutex`’in etkileri

#####  Performans Optimizasyonu
   - ##### *Cache Mimarisi ve CPU Performansı Optimizasyonları*
     - CPU cache yapısı, bellek hiyerarşisi ve performans üzerindeki etkileri
     - Cache dostu algoritmalar geliştirme
     - Paralel programlamada bellek erişimi ve veri yerleşiminin optimizasyonu
   - ##### *İş Parçacıkları Arasında Yük Dengeleme*
     - İş parçacıkları arasında görevlerin adil şekilde dağıtılması
     - Yük dengesizliğinin performansa etkisi ve çözüm yolları

#####  Paralel Programlamada Senkronizasyon Sorunları
   - ##### *Deadlock ve Race Condition Sorunlarını Önleme*
     - Deadlock nedir ve nasıl oluşur?
     - Deadlock önleme ve tespit etme teknikleri
     - Race condition problemlerini tespit etme ve çözme
     - Senkronizasyon hatalarından kaçınma yöntemleri
   - ##### *Lock-Free ve Wait-Free Algoritmalar*
     - Lock-free ve wait-free algoritmaların avantajları ve kullanım alanları
     - Veri yarışını engelleyen algoritmalar geliştirme teknikleri

#####  Paralel Kodların Test Edilmesi ve Debugging
   - ##### *Paralel Kod Testleri ve Performans Analiz Araçları*
     - Paralel programların test edilmesinde karşılaşılan zorluklar
     - Unit test ve entegrasyon testlerinin paralel programlar için uygulanması
     - Performans analiz araçları kullanarak darboğazları tespit etme
   - ##### *Debugging Teknikleri*
     - Paralel kodların debugging süreçleri ve araçlar
     - Thread’ler arası hataları tespit etme teknikleri