---
layout: course
topic: Rust-100
subject: Rust'in Temelleri
subject_permalink: /rust-100/
title: Paralel Programlama (Parallelism)
permalink: /Rust-104/
category: course
sortorder: 400
excerpt: >-
   Bu kurs, paralel programlama yöntemlerini anlamak ve uygulamak için gerekli bilgi ve becerileri kazandırmayı hedefler. Teorik bilgiler ve uygulamalarla, iş parçacıkları ve görev dağılımı üzerinde odaklanılacaktır.
overview: >-
   Paralel programlama, birden fazla işlemin aynı anda gerçekleştirilmesini sağlamak için gerekli olan teknikleri içerir. Bu kurs, bu teknikleri etkili bir şekilde kullanabilmek için gereken temel bilgileri sağlar. Katılımcılar, iş parçacıklarıyla paralel işlem yapma, görevleri bölümlendirme ve verimlilik optimizasyonu konularında derinlemesine bilgi edineceklerdir.
   <br/><br/>
   Kurs süresince, katılımcılar paralel programlamada karşılaşabilecekleri senkronizasyon sorunlarını ve çözümlerini öğrenecekler. Ayrıca, performans analizi ve hata ayıklama gibi konulara da değinilecektir. Gerçek dünya uygulamalarında paralel sistemler geliştirme yetkinliği kazanacaklardır.
audiances:
- Rust 101 ve Rust 102 kurslarını tamamlamış olanlar
- Orta ve ileri düzey programlama Rust deneyimi olan yazılımcılar  
- Paralel programlama konusunda bilgi edinmek isteyen Rust geliştiricileri  
goals: 
- Paralel programlama tekniklerini anlayip kullanabilecek.
- Rust ile paralel iş parçacıkları oluşturma ve yönetme becerisi kazanacak
- Performans optimizasyonu ve senkronizasyon sorunlarını çözme yetkinliği elde edecek.
prerequests:
    - Rust 102’yi tamamlamış olmak veya eşdeğer bir bilgiye sahip olmak.
    - Rust'ın sahiplik, borçlanma ve ömür süreleri gibi temel kavramlarına hâkim olmak.
methodology:
    - Etkileşimli ders ve tartışmalar.
    - Pratik alıştırma ve projeler.
requirements:
    - Online toplanti icin gerekli ortam
    - VS Code
period: 30
---
##### Giriş  
   - Paralellik ve eşzamanlılık farkı  
   - Temel kavramlar  

##### Thread Yönetimi ve Görev Dağılımı  
   - `std::thread::spawn` ile paralel iş parçacıkları  
   - Görevlerin bölümlendirilmesi (Chunking, Striding)  

##### Veri Paylaşımı ve Senkronizasyon  
   - `Arc`, `Mutex`, ve atomik işlemler  

##### Performans Optimizasyonu  
   - Cache mimarisi ve CPU performansı optimizasyonları  

##### Paralel Programlamada Senkronizasyon Sorunları  
   - Deadlock ve race condition sorunlarını önleme  

##### Paralel Kodların Test Edilmesi ve Debugging  
   - Paralel kod testleri ve performans analiz araçları  

##### Proje Çalışması  
   - Paralel hesaplama gerektiren bir proje geliştirme