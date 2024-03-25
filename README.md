
# Üniversite Sınıf Diyagramı
### Soru : Bir üniversite sistemi için aşağıdaki bilgiler doğrultusunda bir sınıf diyagramı çiziniz:


```bash
  Üniversite
    - sınıflıklar
    - çalışma ofisleri
    - departmanlar

Departman
    - ofisler

Çalışan
    - profesör
    - memur

Ofis
    - çalışanlar
```
### İlişkiler:

* Üniversite ile Departman arasındaki ilişki "birden çok" ("1..*") ilişkisidir. Bir üniversitede birden fazla departman olabilir.
* Departman ile Ofis arasındaki ilişki "birden çok" ("1..*") ilişkisidir. Bir departmanda birden fazla ofis olabilir.
* Çalışan ile Ofis arasındaki ilişki "birden bire" ("1..1") ilişkisidir. Her çalışanın bir ofisi vardır ve her ofiste bir çalışan çalışır.
* Çalışan ile Departman arasında "birden çok" ("1..*") ilişki olabilir. Bir çalışan birden fazla departmanda görev alabilir.

### Sınıf Diyagramı Görselleştirmesi:

```bash
                                    Üniversite
                                    /   |   \
                                  sınıflıklar   çalışma ofisleri  departmanlar
                                         /           |
                                      Departman       Ofis
                                        /               |
                                    profesör         memur   çalışanlar
```

### Not: 

* Sınıflara ait nitelik ve davranışların belirtilmesine gerek yok.
* Diyagramın görsel olarak daha iyi anlaşılması için oklar ve isimlendirmeler özelleştirilebilir.