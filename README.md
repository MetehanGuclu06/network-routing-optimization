# network-routing-optimization
# Ağ Yönlendirme Optimizasyonu (GA - ACO - Q-Learning)

Bu proje, karmaşık ağ yapılarında yönlendirme performansını artırmak ve en uygun rotaları belirlemek amacıyla geliştirilmiştir. Proje kapsamında Genetik Algoritma (GA), Karınca Kolonisi Optimizasyonu (ACO) ve Q-Learning algoritmaları kullanılarak farklı optimizasyon yaklaşımları karşılaştırılmıştır.

## Proje Özeti

Ağ topolojileri üzerinde çalışan bu sistem, düğümler (nodes), bağlantılar (edges) ve talepler (demands) gibi verileri harici dosyalardan okuyarak yönlendirme optimizasyonu gerçekleştirmektedir.

Projenin temel amacı:

* Ağ performansını artırmak
* En uygun yönlendirme rotalarını belirlemek
* Farklı optimizasyon algoritmalarının başarılarını karşılaştırmak
* Ağ maliyetlerini ve verimsizlikleri azaltmaktır

## Kullanılan Algoritmalar

### Genetik Algoritma (GA)

Evrimsel hesaplama yaklaşımını kullanarak çözüm uzayında en uygun rotaları bulmayı hedefler.

### Karınca Kolonisi Optimizasyonu (ACO)

Karıncaların doğal davranışlarından esinlenerek en kısa ve en verimli yolları keşfetmeye çalışır.

### Q-Learning

Pekiştirmeli öğrenme yöntemi kullanarak ağ üzerinde öğrenme tabanlı yönlendirme kararları üretir.


## Katkım

Bu proje 8 kişilik bir ekip tarafından geliştirilmiştir.

Ben projede **Genetik Algoritma (GA)** modülünün geliştirilmesi üzerinde çalıştım. Bu kapsamda çözüm üretme mekanizmaları, seçim süreçleri, çaprazlama (crossover), mutasyon işlemleri ve algoritmanın performans değerlendirme aşamalarında görev aldım.


## Kurulum

Gerekli kütüphaneleri yüklemek için:

```bash
pip install -r requirements.txt
```

## Çalıştırma

Projeyi başlatmak için:

```bash
python main.py
```

## Tekrarlanabilirlik

Algoritmaların her çalıştırıldığında aynı sonuçları üretebilmesi için sabit bir rastgelelik (seed) değeri kullanılmıştır.

* Seed Değeri: **42**

Bu sayede deney sonuçları akademik olarak doğrulanabilir ve yeniden üretilebilir hale gelmektedir.

## Kullanılan Teknolojiler

* Python
* NetworkX
* NumPy
* Pandas
* Matplotlib

## Amaç

Bu çalışma, farklı optimizasyon yöntemlerinin ağ yönlendirme problemlerindeki performanslarını analiz etmek ve en verimli yaklaşımın belirlenmesine katkı sağlamak amacıyla geliştirilmiştir.
