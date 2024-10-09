---
layout: course
topic: Rust-100
subject: Rust'in Temelleri
subject_permalink: /rust-100/
sortorder: 200
title: Rust 102 - Temel Rust II
permalink: /rust-102/
documentstate: 1
excerpt: >-
   Bu kurs Rust 101 devam kursu niteligindedir. Rust 101 de giris duzeyinde islenmis konular detaylandirilir. Bunun yaninda kursta veri yapıları, bellek yönetimi, iteratorlar ve modüler programlama gibi önemli konuları yer alir.
overview: >- 
   Rust 102, Rust dilini temel seviyede öğrenmiş katılımcılar için hazırlanmış ileri düzey bir kurstur. 
   <br /><br />Katılımcılar, modüler yapı ve paket yönetimi ile projelerini organize etmeyi öğrenirler. Kursun sonunda, katılımcılar Rust dilini etkin bir şekilde kullanarak daha büyük ve karmaşık projeler geliştirebilecek seviyeye ulaşırlar.
period: 30
goals:
- Rust dilinde ileri veri yapıları ve bellek yönetimi konularını öğrenecek.
- Rust ile modüler ve büyük projeler geliştirebilecek.

audiances:
- Rust 101’i tamamlamış olanlar.
- Rust dilinde temel becerilere sahip olup daha ileri seviyeye çıkmak isteyenler.
- Rust dilinde temel bilgiye sahip olup daha ileri düzeyde bilgilerini geliştirmek isteyenler.
- Veri yapıları ve bellek yönetimi gibi konularda uzmanlaşmak isteyen Rust geliştiriciler.
methodology:
    - Etkileşimli ders ve tartışmalar.
    - Pratik alıştırmalar
    - Odevler
requirements:
    - Online toplanti icin gerekli ortam
    - VS Code
---
# Veri Yapıları
   - Vektörler  
   - HashMap ve BTreeMap  

# Lifetimes ve Borrowing
   - Lifetimes tanımı ve borçlanma kuralları  
   - Referans döngülerinin çözümü (`Rc`, `Arc`, `Mutex`)  

# Iteratorlar ve Koleksiyonlar
   - Iterator Trait ve kullanımı  
   - Lazy Evaluation ve performans  

# Bellek Yönetimi
   - Stack ve Heap ayrımı  
   - Smart pointer'lar: `Box`, `Rc`, `Arc`, `Mutex`  

# Kontrollü Akış ve Pattern Matching
   - `match` kullanımının ileri düzey örnekleri  
   - `Match Guards` ve Custom Enums  

# Result ve Option Tipleri 
   - Custom error tipleri oluşturma  
   - Result ve Option ile pattern matching  

# Fonksiyonel Programlama Yaklaşımları (*)
   - Closure'lar ve higher-order fonksiyonlar  
   - `Map`, `Filter`, `Fold` fonksiyonları  

# Modüler Yapı ve Paket Yönetimi
   - Crate ve mod yapısı  
   - Cargo ile derleme, test etme ve paketleme  

# Concurrency ve Paralel Programlama (*)
   - Thread'ler ve `std::thread` kullanımı  
   - `Send` ve `Sync` trait'leri  
   - `Arc` ve `Mutex` ile güvenli paylaşım  
